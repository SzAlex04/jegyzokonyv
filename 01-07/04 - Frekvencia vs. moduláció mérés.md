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

## 3. Mérés
A mérések a METEK HD spektrum/jelszint analizátor segítségével készültek. Az alábbi paramétereket rögzítettük:

- **Jelszint**: dBm-ben
- **Modulation Error Ratio (MER)**: dB-ben
- **Bitsebesség**: Mbps-ben

### 4. Mérési Paraméterek

| Mérési paraméter      | RF frekvencia (MHz) | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|-----------------------|---------------------|------------------|--------------------|----------------|--------------------|----------------|
| **Mérési eredmény 1** | 474                 | QPSK             | 8                  | -30.7          | -3.85 Mbps         | -39.9 dB       |
| **Mérési eredmény 2** | 474                 | 16-QAM           | 8                  | -31.2          | -7.7 Mbps          | -35.5 dB       |
| **Mérési eredmény 3** | 474                 | 64-QAM           | 8                  | -31.6          | -12.9 Mbps         | -39.9 dB       |

## 5. Mérés képekkel

### 6. Jelszint
A jelszint mérése dBm-ben történt, és az eredmények alapján a legmagasabb jelszintet **64-QAM** modulációval kaptuk, ami jobb vételt biztosított a mérés során.

### 7. Modulációs hiba arány (MER)
Az MER értékei az alábbiak szerint alakultak:
- **QPSK**: MER = 39.9 dB
- **16-QAM**: MER = 35.6 dB
- **64-QAM**: MER = 39.9 dB

A **64-QAM** moduláció esetén az MER értéke a legmagasabb, ami a legjobb jelminőséget eredményezi.

### Bitsebesség
A bitsebesség mérése alapján a **64-QAM** moduláció biztosította a legnagyobb sebességet:
- **QPSK**: Bitsebesség = 3.85 Mbps
- **16-QAM**: Bitsebesség = 7.77 Mbps
- **64-QAM**: Bitsebesség = 12.95 Mbps

## 8. Záróértékelés
A különböző modulációs beállítások hatására megfigyeltük, hogy a **64-QAM** moduláció a legjobb jelszintet és MER értéket biztosította, de a bitsebesség tekintetében is a legjobb eredményt nyújtotta. Ezzel szemben a **QPSK** moduláció alacsonyabb bitsebességgel és MER értékkel rendelkezett, de a jelszint stabilitása miatt hasznos lehet erősebben zajos környezetekben.

**Ajánlás**: A legjobb jelminőséget és sebességet a **64-QAM** moduláció biztosítja, de figyelembe kell venni a környezeti zajt is, amely befolyásolhatja a választott moduláció típusát.

## 9. Aláírás
**Jegyzőkönyv vezetője**: Szabó Alex

**Jegyzőkönyv hitelesítő**: Sándor Péter
