
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Illés Balázs <br>
**A mérés tárgya:** Frekvencia vs. moduláció mérés <br>
**A mérés száma:**  - <br>
**A mérés dátuma:**  2024.11.13 <br>
**A mérést vezette:** Szabó Tamás, Illés Balázs  <br>

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3-Labor

---

## Mérés célja
A frekvencia- és modulációmérés a rádiófrekvenciás jelek elemzésének alapvető módszerei közé tartozik.

---

## ELméleti háttér
1. Frekvencia mérése

A frekvencia egy periodikus jel ismétlődési sebessége, amit Hertzben (Hz) fejeznek ki.

Mérés módjai:

Frekvenciamérő műszerrel:

Ez a műszer közvetlenül méri a bemenő jel frekvenciáját, ahol a jel ismétlődéseit egy adott időintervallumban megszámolják.

2. Moduláció mérése

A moduláció egy jel (általában egy vivőhullám) tulajdonságának (amplitúdó, frekvencia vagy fázis) változtatása egy információs jel hatására.

Típusai és mérési módszerek:

1. Amplitúdómoduláció (AM) mérésekor az amplitúdóváltozás mértékét vizsgáljuk

2. Frekvenciamoduláció (FM) mérésekor az eltérési sávszélességet () és a moduláló frekvenciát mérjük. 

3. Fázismoduláció (PM) mérésekor a fáziseltérést vizsgáljuk az idő függvényében.


---

## Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| Metek HDD                           | 240003     |211110001346          |
| Antenna                             | Iskra P-20  | ...            |
| DVB-T modulátor                     |  Johansson 8202  | ...            |
| Sky RF kábel                        | RG-6 Coaxial Cable   | -          |

Spektrum analizátor: Az összes típusú moduláció mérésére alkalmas.

Oszcilloszkóp: Egyszerű modulációs vizsgálatokhoz és frekvenciaméréshez.

Frekvenciamérő: Pontos frekvenciamérésekhez.


---

### **Mérési helyszín és környezet**
- **Antenna magassága**: 3 méter.
- **Környezet jellemzői**: Zavaró emberi tényezők.
- **Adó távolsága**: kb 5 méter.

---

## Mért értékek különböző modulációkon és frekvenciákon

706 MHz
| Mérési paraméter   | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|--------------------|---------------------|------------------|--------------------|----------------|--------------------|
| Mérési eredmény 1   |    QPSK                |  8                |       -62.6   |      4.2          |       22.3      |
| Mérési eredmény 2   |       16-QAM              |         8      |     -65       |     9             |          21       |
| Mérési eredmény 3   |       64-QAM              |         8      |     -77         |      14.5          |       20.8      |

---

746 MHz
| Mérési paraméter   | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|--------------------|---------------------|------------------|--------------------|----------------|--------------------|
| Mérési eredmény 1   |          QPSK           |         8      |        -59.5      |       4.2         |        28.5   |
| Mérési eredmény 2   |           16-QAM          |        8       |    -65.1    |      9          |          26          |
| Mérési eredmény 3   |              64-QAM       |         8      |      -64.5  |     14.2           |        23.7       |

---

858 MHz
| Mérési paraméter   | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|--------------------|---------------------|------------------|--------------------|----------------|--------------------|
| Mérési eredmény 1   |             QPSK        |      8        |          -61       |    3.9         |            27.5   |
| Mérési eredmény 2   |            16-QAM         |        8          |      -61.2              |        8.6        |             27.8       |
| Mérési eredmény 3   |            64-QAM         |    8              |        -59.5            |         13.8       |      28.4              |

---

## Grafikus ábrázolás
<p>A jelszint, a bitsebesség és MER értékek vizuális ábrázolása:</p>

<img src="https://github.com/balumester/attachments/blob/main/MER%20ertek%20vs%20modulacio.jpg" width="700px">

A kép egy mérési eredmények táblázatát mutatja, amelyben különböző modulációs technológiák (QPSK, 16-QAM, 64-QAM) alapján mért paramétereket (frekvencia, sávszélesség, jel/szint, bitsebesség, MER érték) tartalmaz.

---

## Mérési eredmények elemzése

### 1. Frekvencia:

Az adatokat három frekvencián mértékük

706 MHz, 746 MHz, 858 MHz

### 2. Modulációs típus és bitsebesség:

QPSK 

Bitsebesség: ~4 Mbps

Alacsonyabb bitsebesség, jobban ellenáll a zajnak.

16-QAM

Bitsebesség: ~9 Mbps

Nagyobb bitsebesség, de érzékenyebb a jel/zaj arányra.

64-QAM:

Bitsebesség: ~14 Mbps

A legnagyobb bitsebesség, viszont a legérzékenyebb a jel minőségére.

### 3. MER érték:

A MER az adott modulációs technológia teljesítményét jelzi:

QPSK:

MER: 22–28 dB között mozog.

Ez a modulációs típus alacsony MER mellett is működőképes.

16-QAM:

MER: 21–26 dB.

Érzékenyebb az alacsony MER-re.

64-QAM:

MER: 20–28 dB.

Magas MER szükséges a stabil működéshez. A legérzékenyebb a hibákra.

### 4. Jel szint (dBm):

A különböző modulációs szinteken mért jelszintek -59 dBm és -77 dBm között mozognak.

QPSK jobban teljesít alacsonyabb jelszint mellett is.

64-QAM esetén alacsonyabb jelszinten (~-77 dBm) az MER csökken, ami ronthatja az adatátvitel minőségét.

  
---

## Összefoglalás:
QPSK stabil, zajálló, de alacsony bitsebességű.

64-QAM a legnagyobb bitsebességet nyújtja, de magasabb jelminőséget (MER) igényel.

A grafikonok három fő mért paramétert ábrázolnak a különböző modulációs technológiák (QPSK, 16-QAM, 64-QAM) és frekvenciák (706 MHz, 746 MHz, 858 MHz) függvényében:

### 1. Jel/szint (dBm):

A QPSK moduláció esetén a jel/szint a legmagasabb, míg a 64-QAM érzékenyebb az alacsonyabb jel/zaj arányra, és ennek megfelelően alacsonyabb jelszinttel rendelkezik.

### 2. Bitsebesség (Mbps):

A 64-QAM nyújtja a legnagyobb bitsebességet (~14 Mbps), míg a QPSK a legkisebbet (~4 Mbps), de ez stabilabb működést biztosít alacsonyabb MER értékeknél.

### 3. MER érték (dB):

A QPSK moduláció alacsonyabb MER-értékkel is stabilan működik, míg a 64-QAM nagyobb MER értéket igényel a megfelelő adatátvitelhez, 64-QAM MER értéke nő a frekvencia emelkedésével.


---

<br>

**Aláírás:** Illés Balázs

**Dátum:** 2024.11.13
