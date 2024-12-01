# MÉRÉSI JEGYZŐKÖNYV
## Dátum és idő:   
> kelt.: 2024. szeptember 25.

## A mérést végző neve:   
- Illés Balázs

## A mérés címe	:	Földfelszíni televíziós vétel kialakítása
## A mérés száma	:	3
## A mérést vezette	:	Sándor Péter 
## Csoport neve:		Gyak 1


## Eszközök
Ezek az eszközök egy földfelszíni televíziós vétel kiépítéséhez és ellenőrzéséhez szükségesek.

<img width="595" src="https://github.com/balumester/attachments/blob/main/eszkozlista.jpg">

A tápegység használatával stabil 12V feszültség biztosítható az antennákhoz, erősítőkhöz vagy egyéb eszközökhöz, amelyek külső táplálást igényelnek.

A modulátor lehetővé teszi, hogy egy bemeneti jelet DVB-T formátumba alakítsunk. 

A spektrum analizátor segítségével pontosan megmérhetjük a jelszinteket, a frekvenciák eloszlását, valamint az interferenciákat a vételi tartományban.

A MER (Modulációs Hibaarány) és BER (Bit Hibaarány) értékek ellenőrzésére is alkalmas.

Az antennák (Iskra P-20, Ikusi Flashd) különböző típusú földfelszíni jelek vételére alkalmasak. Az Iskra P-20 Yagi típusú nagy nyereségű antenna, míg az Ikusi Flashd szintén hatékony eszköz.

A kamera segítségével vizuálisan dokumentálhatjuk a telepítési folyamatot, az antennák pozícióját, vagy a mérési környezetet.

A set-top boxot használjuk a jelek vételére és a csatornák beállítására. Ez segít ellenőrizni, hogy a rendszer megfelelően működik-e.


## Blokkvázlat:
<img width="595" src="https://github.com/balumester/attachments/blob/main/blokkvazlat.jpg">

## Mérések:
<img width="595" src="https://github.com/balumester/attachments/blob/main/meres1.png">

<img width="595" src="https://github.com/balumester/attachments/blob/main/meres2.jpg">

A földfelszíni televíziós vétel kialakítása során figyelembe kell venni a vételi hely adottságait, a jelek minőségét, az antennarendszer megfelelő tervezését, és a szükséges eszközök telepítését.

## 1. Először a vételi körülmények mértük fel
Frekvencia- és jelviszonyok: Ellenőriztük a vételi helyen elérhető televíziós adók frekvenciáit és a jelek erősségét, ehhez jelszintmérő eszközt használatunk.

Távolság az adótoronytól: Az adótól való távolság és a terepakadályok (pl. dombok, épületek) jelentősen befolyásolták a vételt.

Zavaró tényezők: Elektromos berendezések okozta zavarok és más rádiófrekvenciás zajforrások is rontották a jel minőségét.

Beállítottuk a tápegységet és csatlakoztattuk az áramforráshoz az eszközöket.

## 2. Ezután az antennát választottuk ki

<details>
<summary><b> Antennák </b></summary>
<ul>
  <li> <b> Logperiódusos antenna: </b> Megfelelő frekvencia és stabil vétel jellemzi.</li>
  <li> <b> Yagi antenna: </b> Magas nyereségű, de irányított.</li>
  <li> <b> Panelantenna: </b> Szélesebb iránykarakterisztikájú, kisebb nyereséggel.</li>
</ul>
</details>

A környezet adottságainak megfelelő antennát kell választani, magasabb nyereség kell a gyengébb jelek esetén.

A megfelelő polarizációjú antennát választottuk (vertikális vagy horizontális), az adótorony sugárzása szerint.

## 3. Antenna telepítése

Az antennát magas ponton (tető, torony) rögzítettük a jobb vétel érdekében.

Az antennát az adótorony irányába állítottuk, figyeltünk a legjobb jelszintre és MER-re.

Stabilan rögzítettük az antennát, hogy ellenálljon az időjárási viszonyoknak.

## 4. Kábelezés és csatlakozók

Jó minőségű koaxiális kábelt használtunk, amely alacsony jelveszteséggel és árnyékolással rendelkezik.

F-csatlakozókat használtunk a jelveszteség minimalizálása miatt.

## 5. Jelerősítés és szűrés

Ha a jelszint gyenge, jelerősítőt (előerősítőt vagy főerősítőt) kell használnunk A túlzott erősítés torzíthatja a jelet.

Ha zavaró jelek vannak a vételi tartományban, sávszűrőt vagy csatornaszűrőt kell alkalmaznunk.

## 6. Set-top box vagy televízió csatlakoztatása

Ha a televízió nem rendelkezik beépített DVB-T/T2 tunerrel, külön set-top box szükséges. A tuner illeszkedését ellenőrizni kell.

## 7. Beállítások és tesztelés

A set-top box vagy televízió automatikus vagy kézi keresési funkciójával hangoltuk be a csatornákat.

A jelszintet (dBm) és a modulációs hibaarányt (MER) mértük, hogy optimalizáljuk a vételt.

## 8. Karbantartás

Az antennát és a kábelezést rendszeresen ellenőrizni kell az oxidáció, károsodás vagy gyengülő jel elkerülése érdekében.
Mérési eredmények:

Megmértük a jelerősséget, és azonosítottuk a legjobb vételi frekvenciákat.

<details>
<summary><b> Antennák </b></summary>
<ul>
  <li> avasi 53dBuV </li>
  <li> nyugat 255fok </li>
  <li> tokaj 66,5dBuV </li>
</ul>
</details>

## Megjegyzések: 

Ha több televíziót kell kiszolgálni, osztót (splittert) lehet használni, de ez csökkenti a jelszintet. Ilyenkor erősítőt kell beépíteni.

Rossz vételi körülmények esetén vegyünk figyelembe alternatív megoldásokat, például műholdas vagy internetes televíziózást.

A mért jelerősségek zárt helyen és zavaró körülmények között is 30dBuV felett voltak.

30dBuV alatti jelerősségnél romlik a kép és a hang minősége.
