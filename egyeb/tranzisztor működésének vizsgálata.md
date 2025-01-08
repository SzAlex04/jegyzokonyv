### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: Tranzisztor működésének vizsgálata

**Mérés időpontja**: 2025.01.08

**Felelős személy**: Szabó Alex Máté

## 1. Cél
A mérés célja a tranzisztorok alapvető működésének és jellemzőinek megértése. A vizsgálat során megfigyeljük a tranzisztor különböző működési pontjait, beleértve az erősítést, a feszültség-áram jellemzőket és az áramköri viselkedést.

## 2. Használt eszközök

- **Tranzisztor**: BC 639 típusú NPN tranzisztor áramfeszültség 90
- **Tápegység**: DC 0-30 V
- **Multiméter**: Digitális multiméter (feszültség és áram mérésére)
- **Ellenállások**: 220 Ω (kis ellenállás), 1,47 kΩ (nagy ellenállás)
- **Kábelek, csatlakozók**: Az áramkör összekötésére

## 3. Kísérleti felállás

A tranzisztor működését különböző üzemmódokban vizsgáljuk, például:
- **Bázis áram mérése**: A bázis és kollektor közötti áramot különböző bázis feszültségek mellett.
- **Kollektor áram mérése**: A kollektor feszültség és áram viszonyának meghatározása.
- **Feszültség-áram jellemzők**: A bázis-emitter feszültség és kollektor áram közötti kapcsolat.

### 3.1 Áramkör kapcsolása

      +Vcc (12V)
        |
       [220Ω]
        |
        |-------+-------Vout
      |           |
     (B)         (C) Tranzisztor (90 típus)
     (E)           |
      |            |
     [1.47kΩ]      GND
      |
     GND

- **Rc** és **Rbe** ellenállások a bázis- és kollektoráramok korlátozására szolgálnak.
- A feszültség mérésére a kimeneti feszültséget mérjük.

## 4. Mért értékek és eredmények

### 4.1 Bázis-emitter feszültség (V_BE)

| Bázis feszültség (V) | Kollektor áram (I_C) (mA) |
|----------------------|---------------------------|
| 0.3                  | 0.01                      |
| 0.6                  | 0.4                       |
| 0.9                  | 1.1                       |
| 1.2                  | 2.5                       |

**Megjegyzés:** A tranzisztor csak akkor kezd aktívan működni, amikor a bázis-emitter feszültség meghaladja a 0.7 V-ot.

### 4.2 Kollektor-Emitter feszültség (V_CE)

| Kollektor feszültség (V) | Kollektor áram (I_C) (mA) |
|--------------------------|---------------------------|
| 10                       | 2.3                       |
| 8                        | 2.0                       |
| 5                        | 1.7                       |
| 2                        | 0.4                       |

**Megjegyzés:** A kollektor áram csökkenése a kollektor-emitter feszültség növekedésével párhuzamosan történik.

### 4.3 Erősítési jellemzők

- A tranzisztor erősítése függ a bázis áramtól, és erősen meghatározza az áramkör működését.
- A mérés során különböző bázis áramok mellett figyeltük meg az erősítést. Az erősítés arányos volt a bázis áram növekedésével.

### 4.4 Tranzisztor mérése

<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/IMG_20250108_090321.jpg"/>
</details>

Multiméterrel megmérjük a tranzisztor áramfeszültségét.

### 4.5 Kapcsolási rajz

<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/tranzisztor%20működésének%20vizsgálata.png"/>
</details>

### 4.6 Áramkör megépítve

<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/IMG_20250108_091726.jpg"/>
</details>

<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/mainegyeb/IMG_20250108_091735.jpg"/>
</details>

### 4.7 Táblázat és grafikon

<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/egyeb/táblázat%20és%20grafikon.png"/>
</details>

## 5. Következtetések

- A tranzisztor megfelelő működéséhez a bázis-emitter feszültségnek 0.7 V fölött kell lennie.
- A tranzisztor erősítési jellemzői megfelelnek az elméleti előrejelzéseknek, az áram növekedésével nő az erősítés.
- Az áramkörben a kollektor áram és a kollektor-emitter feszültség között erős összefüggés található, amelyet a mérés során megfigyeltünk.

## 6. Hibalehetőségek és további vizsgálatok

- **Hibák**: A mért értékek torzulhatnak, ha a tranzisztor túlmelegszik, vagy nem megfelelő áramkörben dolgozik.
- **További vizsgálatok**: A tranzisztor különböző típusainak és konfigurációinak vizsgálata, például a PNP tranzisztorok és a jelfeldolgozó alkalmazásokban való felhasználás.

## 7. Aláírás
**Jegyzőkönyv vezetője**: Szabó Alex
