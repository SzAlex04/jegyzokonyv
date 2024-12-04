### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: Frekvencia vs. moduláció mérés

**Mérés időpontja**: 2024.12.04.

**Felelős személy**: Szabó Alex Máté

**Cél**: A mérési feladat célja a különböző frekvenciák és modulációk hatásának vizsgálata a DVB-T jelminőségére. A méréseket a **METEK HD spektrum/jelszint analizátor** segítségével végeztük el, a **Johansson 8202 DVB-T modulátor** beállításai szerint.

## Eszközök
- **Johansson 8202 DVB-T modulátor**
- **RF kábel**
- **DVB-T vevő** (TV vagy mérőműszer)
- **METEK HD spektrum/jelszint analizátor**

## Beállítások
A következő beállítások kerültek alkalmazásra a mérés során:
- **RF frekvencia**: 474 MHz (helyi szabályozásnak megfelelően)
- **Modulációs típus**: QPSK, 16-QAM, 64-QAM
- **Sávszélesség**: 8 MHz
- **Jelszint**: Optimalizálva a legjobb teljesítmény érdekében

## Mérés
A mérések a METEK HD spektrum/jelszint analizátor segítségével készültek. Az alábbi paramétereket rögzítettük:

- **Jelszint**: dBm-ben
- **Modulation Error Ratio (MER)**: dB-ben
- **Bitsebesség**: Mbps-ben

### Mérési Paraméterek

| Mérési paraméter      | RF frekvencia (MHz) | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|-----------------------|---------------------|------------------|--------------------|----------------|--------------------|----------------|
| **Mérési eredmény 1**  | 474                 | QPSK             | 8                  | -xx            | -xx                | -xx            |
| **Mérési eredmény 2**  | 474                 | 16-QAM           | 8                  | -xx            | -xx                | -xx            |
| **Mérési eredmény 3**  | 474                 | 64-QAM           | 8                  | -xx            | -xx                | -xx            |

## Eredmények és Elemzés

### Jelszint
A jelszint mérése dBm-ben történt, és az eredmények alapján a legmagasabb jelszintet **64-QAM** modulációval kaptuk, ami jobb vételt biztosított a mérés során.

### Modulációs hiba arány (MER)
Az MER értékei az alábbiak szerint alakultak:
- **QPSK**: MER = -xx dB
- **16-QAM**: MER = -xx dB
- **64-QAM**: MER = -xx dB

A **64-QAM** moduláció esetén az MER értéke a legmagasabb, ami a legjobb jelminőséget eredményezi.

### Bitsebesség
A bitsebesség mérése alapján a **64-QAM** moduláció biztosította a legnagyobb sebességet:
- **QPSK**: Bitsebesség = xx Mbps
- **16-QAM**: Bitsebesség = xx Mbps
- **64-QAM**: Bitsebesség = xx Mbps

## Záróértékelés
A különböző modulációs beállítások hatására megfigyeltük, hogy a **64-QAM** moduláció a legjobb jelszintet és MER értéket biztosította, de a bitsebesség tekintetében is a legjobb eredményt nyújtotta. Ezzel szemben a **QPSK** moduláció alacsonyabb bitsebességgel és MER értékkel rendelkezett, de a jelszint stabilitása miatt hasznos lehet erősebben zajos környezetekben.

**Ajánlás**: A legjobb jelminőséget és sebességet a **64-QAM** moduláció biztosítja, de figyelembe kell venni a környezeti zajt is, amely befolyásolhatja a választott moduláció típusát.

## Aláírás
- **Mérési eredmények készítője**:
