### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: Bitsebesség vs. jelminőség mérés mérés

**Mérés időpontja**: 2024.12.09.

**Felelős személy**: Szabó Alex Máté

**Csoport**: 13.E Gyak2

## Cél
A hallgatók megismerjék a Johansson 8202 DVB-T modulátor képességeit, különös tekintettel a többcsatornás jel generálására. A mérés során a résztvevők két programot állítanak be és mérik a jel minőségét különböző bitsebességek mellett.

## Eszközök
- 2 db Johansson 8202 DVB-T modulátor
- DVB-T vevő (pl. TV vagy mérőműszer)
- RF kábelek
- METEK HD spektrum/jelszint analizátor
- Laptop a jegyzőkönyv készítéséhez

---

## Feladatok

### 1. Johansson 8202 Modulátor Konfiguráció
- Kábelezés: A modulátorokat összekötötték egymással, és a kör végén lévő modulátor RF kimenete a spektrumanalizátorhoz csatlakozott.
- A modulátorokat gyári beállításra állították (Factory Reset).
- A hardver vezérlőfelületén keresztül beállították a modulátort.
- Két külön RF frekvencia lett választva: 674 MHz és 682 MHz.
- A többcsatornás jelkimenetet beállították: két program (TV1 és TV2).
- Moduláció: 64-QAM
- Sávszélesség: 8 MHz
- Bitsebesség beállítása:
  - TV1: 15 Mbps
  - TV2: 10 Mbps

### 2. DVB-T Jel Mérés és Stream Ellenőrzés
- Az RF kábelen keresztül csatlakoztatták a DVB-T vevőt a modulátorhoz.
- A METEK HD spektrum/jelszint analizátorral ellenőrizték, hogy mindkét program helyesen vehető-e.
- A következő paramétereket mérték:
  - Jelszint (dBm)
  - Modulation Error Ratio (MER)
  - A két program bitsebessége

### 3. Bitsebesség és Jelminőség Összefüggése
- A következő lépésben változtatták a bitsebességet az egyik programnál (TV2), és figyelték, hogyan változik a jelminőség (MER).
- A TV2 bitsebességét 10 Mbps-ról 21.5 Mbps-ra (MAXIMUM) növelték.
- A mérési eredmények figyelembevételével a jelszintet, MER-t és a vevő reakcióját is dokumentálták.

### 4. Jegyzőkönyv Készítése
A laptopon jegyzőkönyvet készítettek a mért paraméterekről, a következő adatokkal:

---

## 5. Mérési Eredmények

| Mérési paraméter   | RF frekvencia (MHz) | Program neve | Bitsebesség (Mbps) | Jelszint (dBm) | MER érték (dB) |
|--------------------|---------------------|--------------|--------------------|----------------|----------------|
| **Mérési eredmény 1** | 674                 | TV1          | 15                 | 70             | 38             |
| **Mérési eredmény 2** | 682                 | TV2          | 10                 | 70             | 40             |
| **Mérési eredmény 3** | 682                 | TV2          | 21.5 (max)         | 68             | 35             |

---

## Megjegyzések és Kiértékelés

### Mérési eredmény 1 (TV1 - 15 Mbps)
- A jelszint stabilan 70 dBm.
- A MER értéke 38 dB, ami kiváló jelminőséget jelez.

### Mérési eredmény 2 (TV2 - 10 Mbps)
- A jelszint szintén 70 dBm.
- A MER értéke 40 dB, ami szintén megfelelő jelminőséget mutat, és egy kicsit jobb, mint a TV1 programnál.

### Mérési eredmény 3 (TV2 - 21.5 Mbps, maximum bitsebesség)
- A jelszint csökken 68 dBm-re.
- A MER értéke 35 dB, ami már gyengébb jelminőséget eredményez a magasabb bitsebesség miatt.

---

## 6. Összegzés

- A legjobb jelminőséget a 10 Mbps bitsebességgel történő sugárzás biztosította, mivel a jelszint és a MER is optimális tartományban maradt.
- A magasabb bitsebesség csökkentette a jelminőséget, amit a mérés eredményei is alátámasztanak.

---

## További Megjegyzések

A csoportban érdemes megvitatni, hogyan lehetne optimalizálni a többcsatornás jelek sugárzását:
- A bitsebesség és a moduláció megfelelő kombinálásával.
- A frekvenciák okos elosztásával a sávszélesség hatékony kihasználása érdekében.

## 7. Aláírás
**Jegyzőkönyv vezetője**: Szabó Alex
