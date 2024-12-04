### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: Frekvencia vs. moduláció mérés

**Mérés időpontja**: 2024.12.04.

**Felelős személy**: Szabó Alex Máté

**Csoport**: 13.E Gyak2

**Cél**: A mérési feladat célja a különböző frekvenciák és modulációk hatásának vizsgálata a DVB-T jelminőségére. A méréseket a **METEK HD spektrum/jelszint analizátor** segítségével végeztük el, a **Johansson 8202 DVB-T modulátor** beállításai szerint.

## 1. Eszközök
- **Johansson 8202 DVB-T modulátor**
- **RF kábel**
- **DVB-T vevő** (TV vagy mérőműszer)
- **METEK HD spektrum/jelszint analizátor**
- **Laptop** a jegyzőkönyv készítéséhez

## 2. Beállítások
A következő beállítások kerültek alkalmazásra a mérés során:
- **RF frekvencia**: 474 MHz (helyi szabályozásnak megfelelően)
- **Modulációs típus**: QPSK, 16-QAM, 64-QAM
- **Sávszélesség**: 8 MHz
- **Jelszint**: Optimalizálva a legjobb teljesítmény érdekében
<br>
 Johansson 8202
<details>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/johansson8202.png"/>
</details>

## 3. Mérés
A mérések a METEK HD spektrum/jelszint analizátor segítségével készültek. Az alábbi paramétereket rögzítettük:

- **Jelszint**: dBm-ben
- **Modulation Error Ratio (MER)**: dB-ben
- **Bitsebesség**: Mbps-ben
<br>
 METEK HD
<details>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/METEKHD.png"/>
</details>

**DVB-T jel mérése és értékelése**  
   - A METEK HD spektrum/jelszint analizátorral végzett mérések:  
     - Jelszint QPSK: -30.7 dBm  
     - Jelszint 16-QAM: -31.2 dBm  
     - Jelszint 64-QAM: -31.6 dBm 
### 4. Mérési Paraméterek

| Mérési paraméter      | RF frekvencia (MHz) | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|-----------------------|---------------------|------------------|--------------------|----------------|--------------------|----------------|
| **Mérési eredmény 1** | 474                 | QPSK             | 8                  | -30.7          | -3.85 Mbps         | -39.9 dB       |
| **Mérési eredmény 2** | 474                 | 16-QAM           | 8                  | -31.2          | -7.7 Mbps          | -35.5 dB       |
| **Mérési eredmény 3** | 474                 | 64-QAM           | 8                  | -31.6          | -12.9 Mbps         | -39.9 dB       |

### Mérés képekkel
<br>

       Jelszint QPSK: -30.7 dBm

       
<details>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0001.bmp"/>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0003.bmp"/>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0002.bmp"/>
</details>

<br>

       Jelszint 16-QAM: -31.2 dBm  

     
<details>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0006.bmp"/>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0005.bmp"/>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0004.bmp"/>
</details>

<br>

      Jelszint 64-QAM: -31.6 dBm  
     
<details>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0008.bmp"/>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0009.bmp"/>
   <img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/its_snapshot_0007.bmp"/>
</details>  

### 5. Jelszint
A jelszint mérése dBm-ben történt, és az eredmények alapján a legmagasabb jelszintet **64-QAM** modulációval kaptuk, ami jobb vételt biztosított a mérés során.


## 6. Záróértékelés
A különböző modulációs beállítások hatására megfigyeltük, hogy a **64-QAM** moduláció a legjobb jelszintet és MER értéket biztosította, de a bitsebesség tekintetében is a legjobb eredményt nyújtotta. Ezzel szemben a **QPSK** moduláció alacsonyabb bitsebességgel és MER értékkel rendelkezett, de a jelszint stabilitása miatt hasznos lehet erősebben zajos környezetekben.

**Ajánlás**: A legjobb jelminőséget és sebességet a **64-QAM** moduláció biztosítja, de figyelembe kell venni a környezeti zajt is, amely befolyásolhatja a választott moduláció típusát.

## 7. Aláírás
**Jegyzőkönyv vezetője**: Szabó Alex

**Jegyzőkönyv hitelesítő**: Sándor Péter
