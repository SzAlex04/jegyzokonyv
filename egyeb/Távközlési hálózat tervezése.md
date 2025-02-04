
### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: Távközlési hálózat tervezése

**Mérés időpontja**: 2025.01.08

**Felelős személy**: Szabó Alex 

## 1. Cél 
 Egy működő távközlési hálózat kiépítése Mikrotik antennák segítségével. 
 
## 2. Használt eszközök 
**Mikrotik LHG18 LTE** 
**Mikrotik nRay 60GHz Master** 
**Mikrotik nRay 60GHz Slave** 
**Router (AP mód)** 
**Switch (opcionális)** 
**Kliens laptop** 

**Router** 
<br> 
<details> 
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/asus_soho_router.jfif"/> 
</details> 

## 3. IP-cím kiosztás 
**Mikrotik LHG18 LTE**: 192.168.88.1 
**Mikrotik nRay 60GHz Master**: 192.168.88.2 
**Mikrotik nRay 60GHz Slave**: 192.168.88.3 
**Router (AP mód)**: 192.168.88.4 
**Switch**: 192.168.88.254 
**Kliens laptop**: 192.168.88.100-250 

## 4. Topológia 

 <br> 
 <details> 
 <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/topologia.drawio.png"/> 
 </details> 

## 5. Laptop  
  Belépünk admin felhasználóval a laptopba. 
  **felhasználó: V3-XX\admin** 
  **jelszó: mzKvsd** 

 ## 6. Mikrotik LHG18 LTE  
 
 <br> 
 <details> 
 <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/Mikrotik%20_LHG18_LTE_antenna.jfif"/> 
 </details> 

 ## 6.1 resetelése 
 
  **Csatlakozz a készülékhez:** Csatlakoztass egy számítógépet vagy okostelefont az LHG 18 LTE-hez Wi-Fi-n keresztül, vagy Ethernet kábellel. 
  **Bejelentkezés:** A bejelentkezési képernyőn add meg a felhasználónevet és jelszót. Alapértelmezetten a felhasználónév: admin, a jelszó pedig üres (nem kell beírni). 
  **Navigálás a beállításokhoz:** A bal oldali menüben keresd meg a System menüpontot, majd kattints rá. 
  **Gyári visszaállítás:** Az új menüben válaszd a Reset Configuration (Visszaállítás) lehetőséget. 
  **Visszaállítás megerősítése:** Kattints a „Yes” (Igen) gombra a megerősítéshez, hogy visszaállítsd a gyári beállításokat. 
  **Újraindítás:** A készülék automatikusan újraindul, és a gyári beállításokkal fog elindulni. 
  **Ugyan ez a folyamat az nRay antennáknál is!** 
  
## 6.2 konfigurálási adatok  

  **APN:** internet 
  **Current Operator:** Telekom 
  **Data Class:** LTE 
  **RSSI:** -54 dBm 
  **RSRP:** -81 dBm 
  **SINR:** 18 dB    
  **RSRQ:** -10.0 dB 

**Internet** 

 IP Address: 10.069.251.191 

**Local Network** 

 IP Address: 192.168.88.1 

 Netmask: 255.255.255.0 (/24) 

 DHCP Server Range: 192.168.88.100-192.168.88.250 

## 7. LTE konfigurálása  

 Nyisson meg egy böngészőt és lépjen be az LTE antenna konfig felületére: 

 **Cím:** http://192.168.188.1 
 **Felhasználónév:** admin 
 **jelszó:** antennán 

 Konfigurálásnál figyelni kell a **dátum és idő** beállítására. Az eszközt be kell állítani a **192.168.88.1** ip címre, **DHCP* szerveren az antenna! **192.168.88.100-250** 
 **NAT:** 255.255.255.0 
 A laptop ip címét át kell állítani **DHCP-re**, utána ping teszt következik! **(8.8.8.8)** 

## 8. Mikrotik nRay 60GHz antennapár  

   <br> 
   <details> 
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/Mikrotik_nRAYG-60_antenna.jfif"/> 
   </details> 
 
## 8.1 MASTER antenna konfigurálása  
 
 **192.168.88.2** 

 **Bejelentkezés:** 
 **Felhasználónév:** admin 
 **jelszó:** antennán 

 Beállítjuk az antennát **MASTER** módba, ezután ellenőrizzük az ip-t, hogy a **SLAVE** antenna tudjon csatlakozni. 
 **DÁTUM ÉS IDŐ BEÁLLÍTÁSA!** 

## 8.2 SLAVE antenna konfigurálása  

 **192.168.88.3** 

 A fentebbi műveleteket megismételjük, az antennát beállítjuk **SLAVE** módba. 
 Ellenőrizzük a kapcsolat minőségét: **WIRELESS 60G STATUS**. 
 **DÁTUM ÉS IDŐ BEÁLLÍTÁSA!** 

 **Frequency:** 58320 
 **Signal:** 90 
 **MCS:** 7 
 **PHY rate:** 1925.0 Mbps 
 **RSSI:** -49 dB 
 **TX Sector:** 60  
 **TX Sector info:** right 04, up 0,6 
 **RX Sector:** 96 
 **Distance:** 2,18 m 
 **Tx/Rx Rate** 42,8 kbps 
 **Tx/Rx Packet Rate** 14 p/s 
 **FP Tx/Rx Rate** 42.8 kbps 
 **Fp Tx/Rx Packet Rate** 14 p/s 
 **Tx/Rx Bytes** 16.4 MiB 

## 9. Router

 Megnyitunk egy böngészőt és elérjük a megfelelő ip címet. 
 Beállítjuk a WiFi és a router adminisztrációját. 
 **SSID/felhasználó:** GazdaXX 
 **jelszó:** G1234567 
 A routert AP módba kapcsoljuk, az **IP cím: 192.88.XXX** 
 **Figyeljünk a többi opcionális beállításra és az átjáróra!** 

## 10. Tesztelés 

 A sávszélesség tesztelésére használjuk az **iperf** szoftvert és rögzítjük a kapott eredményeket. 
 Elvégezzük a ping és traceroute teszteket a hálózati kapcsolatok ellenőrzésére. 
 Ha van még hiba, akkor azt megkeressük és elhárítjuk. 

## 11. Aláírás 

 **Jegyzőkönyv vezetője**: Szabó Alex 
