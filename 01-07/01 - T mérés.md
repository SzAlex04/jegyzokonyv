### Mérési Jegyzőkönyv

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum 

**Mérés helyszíne**: Labor V3

**Mérés tárgya**: T Ellenállás-hálózat

**Mérés időpontja**: 2024.12.11.

**Felelős személy**: Szabó Alex Máté

**Csoport**: 13.E Gyak2

**Cél**: A kísérlet célja a **T ellenállás-hálózat** jellemzőinek meghatározása, különös figyelmet fordítva az impedancia illesztésére és a jel csillapítására. A T-hálózat segítségével meg kívántuk mérni a bemeneti és kimeneti impedanciát, a csillapítást, valamint az átviteli arányt, hogy ellenőrizzük, a hálózat hogyan befolyásolja a jel erősségét.

## 1. Ellenállások értékei
- **R1:** 0 Ω 
- **R2:** 0 Ω 


## 2. Kapcsolási rajz 
<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/kapcsolasi rajz.svg"/>
</details>

## 3. Szimuláció
<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/K%C3%A9perny%C5%91k%C3%A9p%202024-12-11%20090144.png"/>
</details>

## 4. Megépítve

<br>
<details>
<img src="https://github.com/SzAlex04/jegyzokonyv/blob/main/01-07/beolvasott_20241211-0947.png"/>
</details>

## 5. Számolások, értékek
 **Ellenállások értékei:** R1 és R2 mért értékei.
 
 R1, R2: 264 Ω, 264 Ω ,
 
 R3: 900 Ω
 
 Rg: 680 Ω

 **Mérési eredmények:** Rm= 338.4 Ω Rs=Rl=2045.9 Ω
 
 **Bemeneti impedancia:** 1784.8 Ω
 
 **Kimeneti impedancia:** 1784.8 Ω
 
 **Átviteli arány:** -1.33 dB
 
 **Csillapítás:** 1.33 dB
 
 2045.9(2722.72384.3)≈2045.9×0.8746≈1784.8Ω
 
 TdB=20log10(T)=20log10(0.8585)≈−1.33dB
 
 A=−TdB =1.33dB
 
## 6. T-tag Ellenállások Számítása

**Adatok:**

**Impedancia ((Z)):** 680 Ω

**Csillapítás ((A)):** 6 dB

## 7. Eredmények összehasonlítása

**Bemeneti és Kimeneti Impedancia:**

**Számított:** 1784.8 Ω

**Mért:** 1784.8 Ω

**Átviteli Arány és Csillapítás:**

**Számított csillapítás:** 1.33 dB

**Mért csillapítás:** A csillapítás mért értéke kisebb eltéréseket mutathat a mérési hibák és környezeti tényezők miatt.
Megjegyzések

**Mérési hibák:** A mérőeszközök kalibrálása és a csatlakozások hatással lehetnek az eredményekre.

**Alkatrész variációk:** Az ellenállások tűrései miatt az elméleti és mért értékek eltérhetnek.

**Feszültség és áram mérések:** A mérési eszközök pontossága, mint a jelgenerátor és az oszcilloszkóp, befolyásolhatják az eredményeket.
Az eredmények összehasonlítása segít a mérési környezet és eszközök hatásainak megértésében.

## 8. Aláírás
**Jegyzőkönyv vezetője**: Szabó Alex
