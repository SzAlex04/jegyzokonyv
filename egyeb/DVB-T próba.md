### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: DVB-T

**Mérés időpontja**: 2025.02.03

**Felelős személy**: Szabó Alex

## 1. Használt eszközök 

 **ISKRA P2845 logper antenna**
 
  <br> 
  <details> 
  <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/ISKRA%20P2845%20UHF%20Antenna.png"/> 
  </details> 
 
 **METEK HDD digitális TV jelmérő**
 
  <br> 
  <details> 
  <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/METEKHD.png"/> 
  </details> 
 
 **Viper 4K set-top box**
 
  <br> 
  <details> 
  <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/amiko_viper_4k_v30_1-550x550w.png"/> 
  </details> 

 **Lemco fejállomás**
 
  <br> 
  <details> 
  <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/lemco.jfif"/> 
  </details>
   
  
 **jelosztó**
 
 **koaxiális kábelek**
 
 **csatlakozók**

## 2. Csatorna

 **Miskolc Városi TV csatorna**
 
  <br> 
  <details> 
  <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/sugfrekv.png"/> 
  </details> 

 Azért mérünk ezen a csatornán, mert ez a leggyengébb.
 
 Amelyik csatornán mgjelenik a kép, az a csatorna ingyenes.
 
## 3. Antenna Beállítások

 **ISKRA P2845 LOGPER antenna**
 
  <br> 
  <details> 
  <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/ISKRA%20P2845%20UHF%20Antenna.png"/> 
  </details> 
 
 **Pozíció**: 233° délnyugati irány, 20° dőlésszög
 
 **Antenna Polarizáció**: Horizontális

 **jel:** 38 dB
 
 ## 4. Időjárási Körülmények

 **időjárás:** 5°C

 **Szélsebesség**: 10 km/h
 
 **Megjegyzés**: Nincs csapadék

## 5. Router beállítása

 **IP cím:** 192.168.50.1

 Új hálózatot hozunk létre!

 **SSID:** iptv

 **jelszó:** 12345678

 **router admin belépés** 

 **felhasználónév:** admin
 
 **jelszó:** admin12345678

 **sebesség mérés:** feltöltés, letöltés 93, a hálózat 100/100-as

 **portok:**  LAN1 Lemco control 1Gbps

              LAN2 üres

              LAN3 Lemco ip stream 1Gbps

              LAN4 set-top box 100Mbps

 **új IP cím:** 192.168.1.1

 **UDP proxy:** 8888

 **https://192.168.1.1:8888/udp/293.168.1.1**
              
## 6. Lemco fejállomás beállítása

 **IP cím:** 192.168.1.200

 **felhasználónév:** admin

 **jelszó:** 12345 
 
 **óra beállítása:** időzona Budapest/Bécs

 **INPUT 1:** 

  **Tuner:** DVB-T/T2

  **Frequency:** 586

  **Channel:** 35

  **Bandwidth:** 8 MHz

  **Bit rate:** 22394 Kbps

  **Multiplex B**
 
 **INPUT 2:**

  **Tuner:** DVB-T/T2

  **Frequency:** 634  

  **Channel:** 41

  **Bandwidth:** 8 MHz

  **Bit rate:** 8043 Kbps

  **Miskolc Városi TV**

 **INPUT 3:**

  **Tuner:** DVB-T/T2

  **Frequency:** 666

  **Channel:** 45

  **Bandwidth:** 8 MHz

  **Bit rate:** 22394 Kbps

  **Multiplex A**
  
 **INPUT 4:**

  **Tuner:** DVB-T/T2

  **Frequency:** 690

  **Channel:** 48

  **Bandwidth:** 8 MHz

  **Bit rate:** 27400 Kbps

  **Multiplex E**
  
 **TS OUT 1:** 87%

 **TS OUT 2:** 63%

 **TS OUT 3:** 1%

 **TS OUT 4:** 2%

 **multicast IP:** 239.1.1.1

 **range:** 39

 **protokoll:** UDP

## 7. Mérések és Eredmények

### 1. **Jelerősség**  

 **Jelszint**: 85 dBμV

### 2. **Jel-Zaj Viszony (SNR)**  

 **SNR**: 32 dB

### 3. **Bit Error Rate (BER)**  

 **BER**: 0.00005

### 4. **Modulation Error Ratio (MER)**  

 **MER**: 37 dB

### 5. **Csillapítás**  

 **Csillapítás**: 3 dB

### 6. **Multiplex Adatok**  

 **Frekvencia**: 474 MHz  
 
 **Polarizáció**: Vertikális (V)  
 
 **Szimbólumráta**: 6900 kSym/s  
 
 **FEC**: 3/4


## . Aláírás
**Jegyzőkönyv vezetője**: Szabó Alex
