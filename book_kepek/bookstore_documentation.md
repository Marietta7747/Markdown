<center>
Projekt jelentés a következő témában:

BCA-CC-606

“Könyvesbolt Menedzsment Rendszer”

Benyújtva **Smt. K.B. Parekh Számítástechnikai Főiskola-Mahuva** számára

(A Maharaja Krishnakumarsinhji Bhavnagar Egyetemhez társult)

![kep1](1.jpg)

a követelmények részleges teljesítése érdekében a

### SZÁMÍTÁSTECHNIKAI ALKALMAZÁSOK ALAPDIPLOMA megszerzéséhez

Benyújtva:

**MAKWANA DHAVAL N. (BCA 6. félév, ülés szám: 21260256)**

**BARAIYA KUMAR K. (BCA 6. félév, ülés szám: 21260254)**

Vezető:

**ASHSISH PANDYA**

Adjunktus

Smt. K.B. Parekh Számítástechnikai Főiskola, Mahuva

**2019. március**

**Smt.K.B.Parekh Számítástechnikai Főiskola Mahuva-364290**

**(A Maharaja Krishnakumarsinhji Bhavnagar Egyetemhez társult)**

<p style="text-align:right"><b>Dátum:</b> 2019.03.15</p>

**AKIKNEK EZ ÉRINTHETI**

Ez tanúsítja, hogy **Makwana Dhaval** és **Baraiya Kumar**, a Smt.K.B.Parekh Számítástechnikai Főiskola hallgatói sikeresen teljesítették **KÖNYVESBOLT MENEDZSMENT RENDSZER** projektjüket a 2019. decembertől 2019. márciusig tartó időszakban a BCA-CC-606 követelményeinek részleges teljesítéseként.

**Projektvezető neve és aláírása:**

**Az igazgató aláírása és pecsétje.**

**Cím:** Smt.K.B.Parekh Számítástechnikai Főiskola, Prabhat Nagar Road, Parekh College Campus közelében, Cooperative Housing Society, Mahuva, Gujarat 364290 Tel: 02844/228332 E-mail: kbpbcamahuva2000@gmail.com

**KÖSZÖNETNYILVÁNÍTÁS**

Sok erőfeszítést tettünk ebbe a projektbe. Azonban nem lett volna lehetséges a tanáraink kedves támogatása és segítsége nélkül. Őszinte köszönetet szeretnénk mondani mindannyiuknak.

Különösen hálásak vagyunk a K. B. Parekh Számítástechnikai Főiskolának, Mahuvának az iránymutatásukért, folyamatos felügyeletükért, valamint a projekttel kapcsolatos szükséges információk biztosításáért és támogatásukért.

Szeretnénk kifejezni hálánkat szüleinknek és a KBP tagjainak kedvességükért és ösztönzésükért, amely segített a projekt befejezésében. Végül, de nem utolsósorban, sok köszönet illeti a projektvezetőt, Ashsish Pandya urat, aki teljes erőfeszítéssel vezette a csapatot a cél elérésében. Nagyra értékeljük a többi felügyelő és a bizottságok iránymutatását, különösen a projektprezentációnkban, amelynek köszönhetően javultak az előadói készségeink.

Külön köszönetet mondunk minden fent említett személynek, hogy időt és figyelmet szenteltek nekünk. Köszönetet és elismerést mondunk kollégáinknak a projekt fejlesztésében nyújtott segítségükért és azoknak, akik önként segítettek minket képességeikkel.

**ÖSSZEFOGLALÓ**

A Könyvesbolt Menedzsment Rendszer alapvetően egy webalkalmazás, amely segíti az embereket abban, hogy megtalálják és megvásárolják a legújabb dizájnú könyveket különböző kategóriákban, mint például életrajzok, programozás, menedzsment stb. Ez azért hasznos, mert könnyebbé teszi a személyes könyvesbolt vásárlását.

Manapság a legtöbb könyvesbolt weboldalt használ. Az adminisztrátoroknak sok papírmunkájuk van, és olyan asztali, táblázatos alkalmazásokat használnak, mint az MS Excel, hogy kezeljék a felhasználók adatait digitális formában. Az előterjesztett Könyvesbolt Rendszer szerveren fut, és a felhasználók az összes regisztrációs tevékenységet kezelhetik.

Ez az alkalmazás központosított adatbázist tart fenn, így bármilyen módosítás azonnal megjelenik. Ez egy online eszköz, így egyszerre több felhasználó is bejelentkezhet és használhatja az eszközt.

Az alkalmazás célja a tranzakciók és a történeti adatok kezeléséhez szükséges kézi erőfeszítések csökkentése különböző raktárakban. Továbbá ez az alkalmazás felhasználói felületet biztosít a felhasználóknak, hogy megtekinthessék a részleteket és a könyvesbolt dizájnját.
</center>

### Tartalomjegyzék

- 1 [BEVEZETÉS](#introduction)

    - [1.1 A projekt háttere](#project_background)

    - [1.2 A projekt céljai](#objectives_of_project)

    - [1.3 A projekt célja](#purpose_of_project)

    - [1.4 A projekt terjedelme](#scope_of_project)

    - [1.5 A projekt alkalmazhatósága](#applicability_of_project)

- 2 [KÖVETELMÉNYEK ÉS ELEMZÉS](#requirement_and_analysis)

    - [2.1 Probléma meghatározása](#problem_statement)

    - [2.2 Követelmény specifikációk](#requirement_specifications)

    - [2.3 Hardver követelmények](#hardware_reqiurement)

    - [2.4 Szoftver követelmények](#Software_requirement)

    - [2.5 Tervezés és ütemezés](#planning_and_scheduling)

- 3 [RENDSZER TERVEZÉS](#system_design)

    - [3.1 Általános rendszertervezés tervezési eszközökkel](#over_all_system_design)

    - [3.2 Adatszótár](#data_dictionary)

    - [3.3 Bemenet/Kimenet tervezés](#input_output_design)

- 4 [TESZTELÉS ÉS MEGVALÓSÍTÁS](#testing_and_impementation)

    - [4.1 Alkalmazott tesztelési módszer](#testing_approach_used)

    - [4.2 Tesztesetek](#test_cases)

    - [4.3 Megvalósítási módszerek](#implementation_approaches)

- 5 [KÖVETKEZTETÉS](#conclusion)

    - [5.1 A rendszer korlátai](#limitation_of_system)

    - [5.2 A rendszer jövőbeli lehetőségei](#future_scope_of_system)

    - [5.3 Irodalomjegyzék](#bibliography)

### Ábrák tartalma

| **Ábra szám** | **Ábra neve** |
| --- | --- |
| 1   | Tervezés és ütemezés |
| 2   | Spirál modell |
| 3   | Adatfolyam diagram szimbólumok |
| 4   | 0 szintű adatfolyam diagram |
| 5   | 1<sup>es</sup> szintű adatfolyam diagram |
| 6   | BMS folyamatábra |
| 7   | Felhasználói folyamatábra |
| 8   | Use Case diagram szimbólumok |
| 9   | Felhasználói Use Case diagram |
| 10  | BMS Use Case diagram |
| 11  | Tevékenységi diagram szimbólumok |
| 12  | Felhasználói tevékenységi diagram |
| 13  | Bejelentkezési rendszer tevékenységi diagramja |
| 14  | E-R diagram szimbólumok |
| 15  | E-R diagram a Könyvesbolt Menedzsment Rendszerhez |
| 16  | BMS kezdőlap |
| 17  | BMS kiválasztott kategória |
| 18  | BMS könyvrészletek |
| 19  | BMS bejelentkezési oldal |
| 20  | BMS regisztrációs oldal |
| 21  | BMS "Kapcsolat" oldal |
| 22  | BMS kosár oldal nézőknek |
| 23  | BMS rendelési oldal |
| 24  | Bejelentkezett kezdőlap |
| 25  | BMS felhasználói könyvrészletek |
| 26  | BMS felhasználói kosár oldal |
| 27  | BMS könyv keresés |
| 28  | BMS admin bejelentkezési oldal |
| 29  | BMS admin kezdőlap |
| 30  | BMS új kategória hozzáadása |
| 31  | BMS kategória megtekintése |
| 32  | BMS új könyvek hozzáadása |
| 33  | BMS könyvek megtekintése |
| 34  | BMS kapcsolatfelvételi lista |
| 35  | BMS felhasználói lista |
| 36  | BMS jelszó visszaállítási oldal |
| 37  | Fekete doboz tesztelés |
| 38  | Szürke doboz tesztelés | 
| 39  | Teszteset 1 |
| 40  | Teszteset 2 |
| 41  | Teszteset 3 |
| 42  | Teszteset 4 |



# **1. fejezet**

## [**Bevezetés**](#introduction)

### [1.1 A projekt háttere](#project_background)

- Ez a szoftver lehetővé teszi az admin számára, hogy könyv- és vásárlói adatokat tároljon.
- Könnyebb hozzáférés olyan információkhoz, mint a vásárlói adatok és a könyvek elérhetősége.
- Adattárolási lehetőséget nyújt, csökkentve a papírmunkát.
- A könyvesbolt-kezelő rendszerben a felhasználók vásárolhatnak könyveket, az admin pedig megjelenítheti a vásárlók adatait.
- Új elképzelés a könyvesbolt-kezelő rendszer működéséről.

A rendszer számítógépesítésére.

### [1.2 A projekt céljai](#objectives_of_project)

- A papírmunka csökkentése és a rendszer számítógépesítése.
- Az operatív sebesség növelése. Gyorsabb keresés és pontosság.
- Nagy adattárolás adatbázis használatával.
- A járművásárlások és -eladások manuális feldolgozása nehézkes, e projekt ezt megkönnyíti.
- Gyorsabb információ-visszakeresés.

### [1.3 A projekt célja](#purpose_of_project)

- A könyvesbolt-kezelő rendszer fő célja a papírmunkával kapcsolatos problémák megoldása.
- Egy helyen kezeli az összes tevékenységet, és az admin egyszerre több műveletet is végrehajthat.
- A rendszer képes biztonságosan tárolni a könyvekkel kapcsolatos adatokat.
- Weboldalunk a felhasználói igényekre koncentrál, és az új funkciók egyszerűvé és megbízhatóvá teszik a rendszert.

### [1.4 A projekt hatóköre](#scope_of_project)

- A rendszer célja a túlóra csökkentése és a pontos adatok kezelésének növelése.
- Pontos keresés, amely a keresési műveletekkel eredményeket ad.
- A vásárlók néhány kattintással könyveket foglalhatnak.
- Az admin hatékonyan használhatja az adatbázist, és rugalmasságot biztosít számára.

### [1.5 A projekt alkalmazhatósága](#applicability_of_project)

- Azoknak az ügyfeleknek, akik bármikor és bárhol szeretnének könyvet vásárolni.
- Az admin könyveket adhat hozzá és kezelheti a könyvek listáját.
- Az adatbázis tárolja és visszakeresi az adatokat, így mind az admin, mind a felhasználók hozzáférhetnek az adatokhoz.

# 2. fejezet

## [Követelmények és elemzés](#requirement_and_analysis)

### [2.1 Problémafelvetés](#problem_statement)

- Túl sok papírmunka.
- Az eljárás időigényes.
- Extra költségek a papírmunkával kapcsolatban.
- Nagy adattárolási igény.
- A manuális járművásárlási és eladási folyamat nehézkes.
- Gyorsabb adatvisszakeresés.
- Pontosság és következetesség hiánya a manuális rendszerben.
- Személyes késedelmek.
- Nehéz egy adott rekordot megtalálni a manuális rendszerben.
- Az alkalmazottak időpazarlása.

### [2.2 Követelményspecifikáció](#requirement_specification)

A rendszer két modult tartalmaz:

1) Admin

2) Ügyfél

#### Az admin funkciói

- Ez a modul a következő feladatokat tartalmazza:
  - Kategória hozzáadása.
  - Kategórialista megtekintése.
  - Új könyv hozzáadása.
  - Könyvek megtekintése.
  - Ügyfél üzeneteinek megtekintése.

#### Az ügyfél funkciói

- Ez a modul a következő feladatokat tartalmazza:
  - Könyvek megtekintése.
  - Könyvek kosárhoz adása.
  - Könyvkeresés.
  - Kosár megtekintése vagy tételek hozzáadása.

### [2.3 Hardverkövetelmények](#hardware_requirement)

- 32 bites operációs rendszer.
- Windows 7/8/8.1/10
- Linux Ubuntu / Light Ubuntu
- Mac OS
- 350 MB RAM

### [2.4 Szoftverkövetelmények](#software_requirement)

- Wamp Server
- MySQL
- Böngésző
- PHPMyAdmin

#### Ügyféloldali eszközök

- **Processzor:** PC kettőmagos vagy jobb processzorral (ajánlott: 2,20 GHz).
- **RAM:** 512 MB vagy több (ajánlott).
- **Merevlemez:** Legalább 45 MB szabad hely.
- **Operációs rendszer:** Windows vagy nyílt forráskódú 32/64 bites rendszer.
- Böngésző: Mozilla Firefox 2.0 / Internet Explorer 8.0 / Google Chrome.

### [2.5 Tervezés és ütemezés](#planning_and_scheduling)

Minden fejlesztési szakasz különböző időt igényel. Az alábbi táblázat mutatja az egyes fázisok becsült idejét:

| ID | Feladat neve | Kezdés/Befejezés | Időtartam |
| --- | --- | --- | --- |
| 1   | Elemzés | 2018.12.25 - 2019.01.01 | 8 nap |
| 2   | Tervezés | 2019.01.01 - 2019.01.09 | 9 nap |
| 3   | Kódolás | 2019.01.10 - 2019.02.08 | 4 hét |
| 4   | Megvalósítás | 2019.02.08 - 2019.02.12 | 5 nap |
| 5   | Tesztelés | 2019.02.12 - 2019.02.17 | 6 nap |
| 6   | Dokumentáció | 2019.02.18 - 2019.03.10 | 3 hét |


# 3. fejezet

## [Rendszertervezés](#system_design)

### [3.1 Átfogó rendszertervezés tervező eszközök használatával](#over_all_system_design)

A tervezési fázis célja egy megoldás megtervezése a követelményekben meghatározott problémára. A rendszertervezés célja a rendszer moduljainak azonosítása, ezen modulok specifikációja, valamint azok egymással való interakciója, hogy a rendszer működjön. A tervezési folyamat célja egy modell létrehozása, amely később a rendszer felépítéséhez használható. Ezt a modellt a rendszer tervének nevezzük.

A rendszertervezés folyamata az architektúra, komponensek, modulok, interfészek és adatok meghatározása a meghatározott követelmények kielégítése érdekében.

A tervezés általában két szakaszban zajlik:

- Fizikai tervezés
- Adatbázis tervezés
<center>  

### Fizikai tervezés

A fizikai tervezés grafikus ábrázolása a rendszer belső és külső entitásainak, valamint az ezekbe és ezekből érkező adatok áramlásának. Egy belső entitás olyan entitás, amely a rendszerben található és átalakítja az adatokat.

A rendszer fizikai tervezésének ábrázolására olyan diagramokat használunk, mint az adatfolyam-diagramok, E-R diagramok, esetdiagramok stb.

### 1. Adatfolyam-diagram

Az adatfolyam-diagramok (DFD) egy információs rendszer adatáramlásának grafikus ábrázolása. Ezeket az adatfolyam-diagramokat rendszerelemzés során használják információfeldolgozó rendszerek tervezésére, de egy teljes szervezet modellezésére is alkalmasak. Az adatfolyam-diagramok fő előnye, hogy áttekintést adnak arról, hogy a rendszer milyen adatokat dolgoz fel, milyen átalakításokat végez, milyen adatokat tárol, és ezek az adatok hova áramlanak.

### Az adatfolyam-diagramokban használt szabványos szimbólumok
</center>  

| **Szimbólum** | **Név** | **Funkció** |
| --- | --- | --- |
|   ![kep8](8.JPG)  | **Adatáramlás** | A folyamatok összekapcsolására használják. A nyílfej jelzi az adatáramlás irányát. |
|   ![kep9](9.JPG)  | **Folyamat** | A bemeneti adatokat kimeneti adatokra alakítja át. |
|  ![kep10](10.JPG)   | **Bemenet / Kimenet** | Az adatok bevitelére vagy kivitelére szolgál. |
<center>  

#### (3. ábra: Adatfolyam-diagram szimbólumok)

### 0. szintű DFD (Weboldal áramlás diagram)
</center>  

![kep11](11.jpg)

<center>  

#### (4. ábra: 0. szintű adatfolyam-diagram)


### 1. szintű DFD (Weboldal áramlás diagram)
  

![kep12](12.JPG)

#### (5. ábra: 1<sup>st</sup> szintű adatfolyam-diagram)
  

### Folyamatábra


![kep13](13.jpg)  

#### (6. ábra: BMS folyamatábra)

### Felhasználói áramlás diagram

![kep14](14.jpg)

#### (7. ábra: Felhasználói áramlás diagram)
</center>  

### 2. Esetdiagram

Az esetdiagram egy olyan forgatókönyvek halmaza, amelyek leírják a felhasználó és a rendszer közötti interakciókat. Az esetdiagramok megjelenítik a színészek és az esetek közötti kapcsolatot. Az esetdiagram két fő eleme az esetek és a színészek.
<center>  

![kep15](15.jpg)

#### (8. ábra: Esetdiagram szimbólumok)

Egy színész egy felhasználót vagy egy másik rendszert képvisel, amely interakcióba lép a modellezett elemmel. Az eset a rendszer külső nézete, amely egy olyan műveletet képvisel, amelyet a felhasználó végrehajthat egy feladat teljesítéséhez.

### Felhasználói esetdiagram

![kep16](16.jpg)

#### (9. ábra: Felhasználói esetdiagram)

### BMS esetdiagram

![kep17](17.JPG)

#### (10. ábra: BMS esetdiagram)

### 3. Tevékenységdiagram

A tevékenységdiagram alapvetően egy folyamatábra, amely a tevékenységek közötti áramlást ábrázolja. A tevékenység a rendszer egy művelete.
</center>  

| Szimbólum neve | Szimbólum | Leírás |
| --- | --- | --- |
| Kezdő szimbólum | ![kep18](18.JPG) | A folyamat vagy a munkafolyamat kezdetét jelzi egy tevékenységdiagramon. Használható önmagában vagy egy jegyzet szimbólummal, amely magyarázza a kiindulópontot. |
| Tevékenység szimbólum | ![kep19](19.JPG) | A modellezett folyamat tevékenységeit jelöli. Ezek a szimbólumok, amelyek rövid leírásokat tartalmaznak a formán belül, a tevékenységdiagram fő építőkövei. |
| Csatlakozó szimbólum |  ![kep20](20.JPG)   | A tevékenység irányított áramlását mutatja. A befelé mutató nyíl egy lépést kezd egy tevékenységen belül; a lépés befejezése után az áramlás folytatódik a kifelé mutató nyíllal. |
| Döntési szimbólum | ![kep21](21.JPG) | Döntést jelképez, és mindig legalább két ága van feltétel szöveggel, amely lehetővé teszi a felhasználók számára, hogy megtekintsék a lehetőségeket. Ez a szimbólum a különböző folyamatok elágazását vagy összeolvadását jelöli, ahol a szimbólum keretként vagy tartóként működik. |
| Záró szimbólum | ![kep22](22.JPG) | A tevékenység záró állapotát jelöli, és a folyamat minden ágának befejezését képviseli. |
| Egyesítő szimbólum/Szinkronizációs vonal | ![kep23](23.JPG) | Két párhuzamos tevékenységet egyesít, és visszavezeti őket egy olyan folyamatba, ahol csak egy tevékenység zajlik egyszerre. Vastag függőleges vagy vízszintes vonallal ábrázolva. |
| Elágazás szimbólum | ![kep24](24.JPG) | Egy tevékenység áramlását osztja fel két párhuzamos tevékenységre. Több nyílvonal jelzi az elágazást. |
<center>  

#### (11. ábra: Tevékenységdiagram szimbólumok)

### Felhasználói tevékenységdiagram

![kep25](25.JPG)

#### (12. ábra: Felhasználói tevékenységdiagram)

### Bejelentkezési rendszer tevékenységdiagramja

![kep26](26.JPG)

#### (13. ábra: Bejelentkezési rendszer tevékenységdiagramja)

### E-R diagram

Az entitás-kapcsolat diagram (E-R diagram) egy grafikus ábrázolás az entitások és azok kapcsolatának bemutatására. Leírja, hogyan kapcsolódnak az adatok egymáshoz. Egy entitás egy adatdarab – egy objektum vagy egy fogalom, amelyről adatot tárolunk. Egy kapcsolat pedig azt mutatja meg, hogyan osztják meg az adatokat az entitások között.

Az E-R diagramban három fő komponens található:
</center>  

| Szimbólum | Név | Leírás |
| --- | --- | --- |
|  ![kep27](27.JPG)   | Entitás | Egy entitás lehet bármilyen tárgy, hely, személy vagy bármi más. |
|  ![kep28](28.JPG)   | Attribútum | Az attribútum egy entitás tulajdonságát vagy jellemzőjét írja le. |
|   ![kep29](29.JPG)  | Kapcsolat | A kapcsolat az entitások közötti viszonyt írja le. |
<center>  

#### (14. ábra: E-R diagram szimbólumok)

### E-R diagram egy könyvkereskedés menedzsment rendszerhez

![kep30](30.JPG)

#### (15. ábra: E-R diagram egy könyvkereskedés menedzsment rendszerhez)
</center>  


### [3.2 Adatszótár](#data_dictionary)

### Adatbázis és szerkezettervezés

A rendszerben használt különböző táblák:

1. Admin
2. Könyv
3. Kategória
4. Kapcsolat
5. Regisztráció
6. Rendelés

Az összes tábla részletei és mezői:

#### Tábla neve: Admin

**Elsődleges kulcs:** a_id

**Leírás:** Az adminisztrátori bejelentkezési adatok tárolására szolgál.

| **Mező** | **Típus** | **Leírás** |
| --- | --- | --- |
| A_id | int(4) | Az adminisztrátori azonosító tárolására |
| A_unm | Varchar(3) | Az adminisztrátor felhasználónevének tárolására |
| A_pwd | Varchar(30) | Az adminisztrátor jelszavának tárolására |

#### Tábla neve: Könyv

**Elsődleges kulcs:** b_id

**Leírás:** Könyv adatok tárolása.

| **Mező** | **Típus** | **Leírás** |
| --- | --- | --- |
| B_id | Int(10) | A könyv azonosítójának tárolására |
| B_nm | Varchar(50) | A könyv nevének tárolására |
| B_cat | Int(6) | A különböző kategóriák könyvazonosítójának kiválasztására vagy tárolására |
| B_desc | Longtext | A könyv részletes leírásának tárolására |
| B_price | Int(4) | A könyv árának tárolására |
| B_img | Varchar(50) | A könyv képének nevének tárolására |
| B_time | Int(20) | A könyv beszúrásának idejének tárolására |

#### Tábla neve: Kategória

**Elsődleges kulcs:** cat_id

**Leírás:** A kategórianevek tárolására szolgál.

| **Mező** | **Típus** | **Leírás** |
| --- | --- | --- |
| Cat_id | Int(10) | A kategóriaazonosító tárolására |
| Cat_nm | Varchar(50) | A kategórianév tárolására |

#### Tábla neve: Kapcsolat

**Elsődleges kulcs:** c_id

**Leírás:** Kapcsolatfelvételi adatok tárolása.

| **Mező** | **Típus** | **Leírás** |
| --- | --- | --- |
| C_id | Int(4) | Az ügyfél/felhasználó kapcsolatfelvételi azonosítójának tárolása |
| C_fnm | Varchar(100) | A felhasználó teljes nevének tárolása |
| C_mno | Int(10) | Az ügyfél/felhasználó mobiltelefonszámának tárolása |
| C_email | Varchar(60) | Az ügyfél/felhasználó e-mail címének tárolása |
| C_msg | Longtext | Az ügyfél/felhasználó üzenetének vagy kérdésének tárolása |
| C_time | Varchar(20) | A kapcsolatfelvételi űrlap adatainak beszúrási idejének tárolása |

#### Tábla neve: Regisztráció

**Elsődleges kulcs:** r_id

**Leírás:** Látogatók vagy felhasználók regisztrációs adatai.

| **Mező** | **Típus** | **Leírás** |
| --- | --- | --- |
| R_id | Int(8) | A felhasználó regisztrációs azonosítójának tárolása |
| R_fnm | Varchar(100) | A felhasználó teljes nevének tárolása |
| R_unm | Varchar(50) | A felhasználó felhasználónevének tárolása |
| R_pwd | Varchar(30) | A felhasználó jelszavának tárolása |
| R_cno | Varchar(10) | A felhasználó kapcsolattartási számának tárolása |
| R_email | Varchar(60) | A felhasználó e-mail címének tárolása |
| R_time | Varchar(20) | A felhasználó regisztrációjának idejének tárolása |

#### Tábla neve: Rendelés

**Elsődleges kulcs:** o_id

**Leírás:** A rendelés adatai


| **Mező** | **Típus** | **Leírás** |
| --- | --- | --- |
| O_id | Int(11) | A rendelés azonosítójának tárolása |
| O_name | Varchar(30) | A felhasználó teljes nevének tárolása |
| O_address | Varchar(200) | A felhasználó címének tárolása |
| O_pincode | Int(20) | A város irányítószámának tárolása |
| O_city | Varchar(30) | A város nevének tárolása |
| O_state | Varchar(30) | Az állam tárolása |
| O_mobile | Bigint(20) | A felhasználó mobiltelefonszámának tárolása |
| O_rid | Int(8) | A regisztrációs azonosító tárolása |

### [3.3 Beviteli/Kimeneti Tervezés](#input_output_design)

###### 1. **Főoldal**

A BMS főoldala bejelentkezett felhasználó nélkül.

![kep3](3.jpg)

<center>  

#### (16. ábra: BMS főoldal)
</center>  

###### 2. **Kiválasztott Kategória**

A Nyomozó kategória van kiválasztva.

Megjeleníti a Nyomozó kategória könyveit.

![kep4](4.jpg)

Nyomozó kategória könyvei
  
<center>  

#### (17. ábra: BMS kiválasztott kategória)
</center>  

###### 3. **Könyv Részletek (Bejelentkezés Előtt)**

Könyv részletek látogatók számára.

A látogatók nem tudnak könyveket a kosárba tenni.

<center>  

![kep5](5.jpg)

#### (18. ábra: BMS könyv részletei)
</center>  

###### 4. **Látogató Bejelentkezési Oldal**

Bejelentkezési oldal a nézőknek.

<center>  

![kep6](6.JPG) 

#### (19. ábra: BMS bejelentkezési oldal)
</center>  

###### 5. **Regisztrációs Oldal**

Regisztrációs oldal a nézőknek.

<center>  

![kep31](31.JPG) 

#### (20. ábra: BMS regisztrációs oldal)
</center>  

###### 6. **Kapcsolatfelvételi Oldal**

<center>  

![kep32](32.JPG) 

#### (21. ábra: BMS kapcsolatfelvételi oldal)
</center>  

###### 7. **Kosár Oldal**

<center>  

![kep33](33.JPG)

#### (22. ábra: BMS kosár nézet a nézőknek)
</center>  

###### 8. **Rendelési Oldal**

Csak utánvétes fizetés elérhető a rendelésekhez.

<center>  

![kep34](34.JPG) 

#### (23. ábra: BMS rendelési oldal)
</center>  

###### 9. **Főoldal (Bejelentkezve)**

Automatikusan megváltozott a navigációs sáv.

A felhasználó ki tud jelentkezni.

<center>  

![kep35](35.JPG)  

#### (24. ábra: BMS bejelentkezett oldal)
</center>  

###### 10. **Könyv Részletek (Bejelentkezve)**

A felhasználók hozzáadhatják a könyveket a kosárhoz.

Eltávolítva a bejelentkezés linkje.

<center>  

![kep36](36.JPG) 

#### (25. ábra: BMS felhasználók könyv részletei)
</center>  

###### 11. **Kosárba Tétele (Bejelentkezve)**

A felhasználók könyveket adhatnak a kosárhoz.

Könyvek és árak részletei.

Kattintson a Számítás újraszámítására, hogy a mennyiség, ár és összeg kiszámításra kerüljön.

A felhasználók rendelhetnek könyveket.

<center>  

![kep37](37.JPG)

#### (26. ábra: BMS felhasználók kosár oldala)
</center>  

###### 12. **Könyvek Keresése**

Könyvkereső funkció.

<center>  

![kep38](38.JPG)

#### (27. ábra: BMS könyvek keresése)
</center>  

###### 13. **Admin Bejelentkezési Oldal (Új Sablon)**

<center>  

![kep39](39.JPG)

#### (28. ábra: BMS admin bejelentkezési oldal)
</center>  

###### 14. **Admin Főoldal**

Új sablon.

<center>  

![kep40](40.JPG)

#### (29. ábra: BMS admin főoldal)
</center>  

###### 15. **Kategória Hozzáadása (Admin)**

<center>  

![kep41](41.JPG)

#### (30. ábra: BMS új kategória hozzáadása)
</center>  

###### 16. **Kategória Megtekintése**

Könyvek listája.

<center>  

![kep432](42.JPG)

#### (31. ábra: BMS kategória megtekintése)
</center>  

###### 17. **Könyvek Hozzáadása**

<center>  

![kep43](43.JPG)

#### (32. ábra: BMS új könyvek hozzáadása)
</center>  

###### 18. **Könyvek Megtekintése**

Könyvek listája az admin számára.

<center>  

![kep44](44.JPG)

#### (33. ábra: BMS könyvek megtekintése)
</center>  

###### 19. **Kapcsolatba Lépett Lista Megtekintése**

Azoknak az embereknek a listája, akik kapcsolatba léptek a kapcsolatfelvételi oldalon.

<center>  

![kep45](45.JPG)

#### (34. ábra: BMS kapcsolatba lépett könyvek listája)
</center>

###### 20. **Felhasználók Listája**

<center>  

![kep46](46.JPG)

#### (35. ábra: BMS felhasználók listája)
</center>

###### 21. **Jelszó Elfelejtve**

<center>  

![kep47](47.JPG)

#### (36. ábra: BMS jelszó elfelejtve oldal)
</center>

# 4. fejezet

## [Tesztelés és megvalósítás](#testing_and_impementation)

### [4.1 Használt tesztelési megközelítés](#testing_approach_used)

#### - **Fekete doboz tesztelés**

A fekete doboz tesztelés egy szoftvertesztelési módszer, amely egy alkalmazás funkcionalitását vizsgálja a specifikációk alapján. Specifikáció alapú tesztelésnek is nevezik.

A független tesztelő csapat általában a szoftvertesztelési életciklus során végzi ezt a típusú tesztelést.

Ez a tesztelési módszer alkalmazható a szoftvertesztelés minden szintjén, például egység, integráció, rendszer és elfogadási tesztelés során.

<center>

![kep48](48.JPG)

#### (37. ábra: Fekete doboz tesztelés)
</center>

Ezt a módszert azért nevezzük így, mert a szoftverprogram a tesztelő szemében egy fekete doboznak tűnik; belülről nem lehet látni. Ez a módszer a következő kategóriákban próbál hibákat találni:

- Hibás vagy hiányzó funkciók
    - Felhasználói felületi hibák
    - Hibák az adatszerkezetekben vagy külső adatbázis-hozzáférésben
    - Viselkedési vagy teljesítményi hibák
    - Inicializálási és leállítási hibák

- **A fekete doboz tesztelés előnyei**

A tesztek a felhasználó szempontjából készülnek, és segítenek feltárni a specifikációkkal kapcsolatos eltéréseket.

A tesztelőnek nem szükséges programozási nyelveket ismernie vagy tudnia, hogyan valósították meg a szoftvert.

#### - **Fehér doboz tesztelés**

A fehér doboz tesztelés egy olyan tesztelési technika, amely megvizsgálja a program szerkezetét, és a program logikájából/kódjából származtat tesztadatokat. A fehér doboz tesztelés másik neve az üveg doboz tesztelés, tiszta doboz tesztelés, nyitott doboz tesztelés, logika vezérelt tesztelés vagy útvonalvezérelt tesztelés.

A fehér doboz tesztelés során a kód szerkezetét nézzük. Amikor ismerjük egy termék belső struktúráját, a tesztek elvégezhetők annak biztosítására, hogy a belső műveletek a specifikációnak megfelelően történjenek, és minden belső komponens megfelelően működjön.

- **Fehér doboz tesztelési technikák:**

    - A - Nyilatkozat lefedettség – Ez a technika célja, hogy a lehető legkevesebb teszttel fedje le az összes programozási nyilatkozatot.
    - B - Ág lefedettség – Ez a technika sorozat tesztelését jelenti, hogy biztosítsa, hogy minden ág legalább egyszer legyen tesztelve.
    - C - Útvonal lefedettség – Ez a technika minden lehetséges útvonal tesztelésére vonatkozik, ami azt jelenti, hogy minden nyilatkozatot és ágat le kell fedni.

- **A fehér doboz tesztelés előnyei:**

    - 1 - Kényszeríti a tesztfejlesztőt, hogy gondosan mérlegelje a megvalósítást.
    - 2 - Feltárja a „rejtett” kódban lévő hibákat.
    - 3 - Feltárja a kód vagy más problémákat a legjobb programozási gyakorlatokkal kapcsolatban.

#### - **Szürke doboz tesztelés:**

A szürke doboz tesztelés egy olyan tesztelési technika, amelyet a rendszer belső funkcionalitásáról korlátozott információval hajtanak végre. A szürke doboz tesztelők hozzáféréssel rendelkeznek a követelmények részletes tervezési információihoz.

A szürke doboz tesztek az állapotalapú modellek, UML diagramok vagy a célrendszer alapján készülnek.

A szürke doboz tesztelés egy technika, amely a szoftvertermék vagy alkalmazás tesztelésére szolgál, részleges ismeretekkel az alkalmazás belső működéséről.

<center>

![kep49](49.JPG)

#### (38. ábra: Szürke doboz tesztelés)
</center>

### [4.2 Tesztesetek](#test_cases)

**4.2.1 Admin bejelentkezési részletek**

<table><tbody><tr><th><p>Felhasználónév</p></th><th><p>Admin</p></th><th><p>Jelszó</p></th><th><p>Admin</p></th></tr><tr><td colspan="4"><p>Várt eredmény:</p><ul><li>Ha a mezők üresek, akkor hibaüzenetet ad a mezők kitöltésére</li><li>Ha a jelszó vagy felhasználónév nem létezik, akkor hibaüzenetet ad érvényes adatokra.</li></ul></td></tr></tbody></table>

**4.2.2 Bejelentkezési részletek**

<table><tbody><tr><th><p>Felhasználónév</p></th><th><p>Dhaval</p></th><th><p>Jelszó</p></th><th><p>Dhaval</p></th></tr><tr><td colspan="4"><p>Várt eredmény:</p><ul><li>Ha a mezők üresek, akkor hibaüzenetet ad a mezők kitöltésére</li><li>Ha a jelszó vagy felhasználónév nem létezik, akkor hibaüzenetet ad érvényes adatokra.</li></ul></td></tr></tbody></table>

**4.2.3 Regisztrációs részletek**

<table><tbody><tr><th><p>Felhasználónév</p></th><th><p>ÜRES</p></th><th><p>Jelszó</p></th><th><p>ÜRES</p></th></tr><tr><td><p>Teljes név</p></td><td><p>ÜRES</p></td><td><p>Biztonsági válasz</p></td><td><p>ÜRES</p></td></tr><tr><td colspan="4"><p>Várt eredmény:</p><ul><li>Ha a mezők üresek, akkor hibaüzenetet ad a mezők kitöltésére</li><li>Ha a jelszó kevesebb, mint 8 karakter, akkor hibaüzenetet ad.</li></ul></td></tr></tbody></table>

**4.2.4 Rendelési részletek**

<table><tbody><tr><th><p>Teljes név</p></th><th><p>Cím</p></th><th><p>Kapcsolattartó szám</p></th><th><p>ÜRES</p></th></tr><tr><td colspan="4"><p>Várt eredmény:</p><ul><li>Ha a mezők üresek, akkor hibaüzenetet ad a mezők kitöltésére</li><li>Ha a kapcsolattartó szám nem numerikus, akkor hibaüzenetet ad.</li></ul></td></tr></tbody></table>

<center><u>

**Képernyőfotók**  
</u></center>

1. **Felhasználói bejelentkezés**

<center>

![kep50](50.JPG)

#### (39. ábra: Tesztesetek 1)
</center>

2. **Admin bejelentkezés**

<center>

![kep51](51.JPG)

#### (40. ábra: Tesztesetek 2)
</center>

3. **Könyv hozzáadása**

<center>

![kep52](52.JPG)

#### (41. ábra: Tesztesetek 3)
</center>

4. **Felhasználói regisztráció**

<center>

![kep53](53.JPG)

#### (42. ábra: Tesztesetek 4)
</center>

### [4.3 Megvalósítási megközelítések](#implementation_approaches)

A legnagyobb kihívás, amellyel szembesültünk, az időkorlátok voltak. A megvalósítás rendkívüli mennyiségű időt és sok koordinációt igényel. A projektmegbeszélések ütemezése minden csoporttag időbeosztásához szinte lehetetlennek bizonyult. A csoporttagok közül sokan nem tudtak annyi figyelmet szentelni, amennyire a megvalósítási szakasznak szüksége volt. Az előző és a későbbi probléma talán inkább a tudományos környezetben jelentkezik, ahol a különböző csoporttagok prioritásai különböző irányokba torzulnak. Egy másik felmerült probléma a PHP programozás ismerete volt. Legalább két csoporttag nem volt tisztában a PHP Swing API-val, amely a PHP alapvető felhasználói felület csomagja. Ismételten, ez lehet, hogy nem jelentkezik akkora problémaként a szoftvermérnökség területén kívül, mint az akadémiai környezetben.

Az egyik eszköz, amelyet nagyon hasznosnak találtunk olyan helyzetekben, ahol a tagok felelősségeit tisztázni kell, a felelősségi mátrix. Ez valóban az egyetlen eszköz volt, amely lehetővé tette számunkra a folyamatos előrehaladást. Mindenkinek feladatot osztottunk ki, és mindenki felelős a saját feladatának elvégzéséért. Ez lehetővé teszi számunkra, hogy nyomon kövessük a megvalósítandó feladatokat. A felelősségi mátrix felbecsülhetetlen eszköznek bizonyult a szoftvermérnöki folyamatban.


# 5. fejezet

## [Következtetés](#conclusion)

**Következtetés**

- Első ránézésre elmondhatjuk, hogy a Könyváruház Kezelő Rendszer egy tökéletes rendszer, de számos korlátozással rendelkezik, amelyek a következők:
- Ezt a rendszert a kategóriák és könyvek listázására, valamint a vásárlók és könyvek kezelésére használják.
- A Könyváruház Kezelő Rendszer célja, hogy információt adjon a könyvekről a vásárlóknak.
- Számos problémával szembesültünk, mint például az adatbázis létrehozása, a rendszer folyamata, a frontend és backend eszközök tervezése, kódolás stb.
- A rendszer csak egy felhasználó által használható egyszerre.
- Ebben a rendszerben nem tudunk szolgáltatásmodult hozzáadni.
- Új nyelveket tanultunk, mint például jQuery, PHP, Boot-Strap, HTML, CSS stb.

### [5.1 A rendszer korlátozásai](#limitation_of_system)

- **Segítség**

Jelenleg a segítség funkció nem elérhető. E funkció használatával a felhasználó segítséget kaphat a rendszerrel kapcsolatban.

- **Fizetés**

Jelenleg az online fizetés funkció nem elérhető. A felhasználó nem tud online fizetni.

- **Többnyelvűség**

A többnyelvűség nem támogatott a rendszerünkben. Ezért a felhasználó nem tud különböző nyelveken dolgozni.

- **Biztonsági mentés és visszaállítás**

A felhasználó nem tud biztonsági másolatot készíteni vagy adatokat visszaállítani a rendszerben.

- **Sok más egyéb.**

### [5.2 A rendszer jövőbeli lehetőségei](#future_scope_of_the_system)

- **Segítség modul**

E modul használatával a felhasználó segítséget kaphat a rendszerhez való hozzáférésről. A rendszer minden funkcióját leírják ebben a modulban. A felhasználó könnyen hozzáférhet az összes modulhoz ezen a funkción keresztül.

- **Online fizetési modul**

A felhasználó online végezheti el a fizetést e funkció használatával. A jövőben hozzáadjuk az online fizetést, hogy a felhasználók számára könnyebbé tegyük a kifizetéseket.

- **Többnyelvűség**

Ebben a rendszerben hozzáadjuk a többnyelvűséget, így a felhasználó különböző nyelveken dolgozhat és könnyebben megértheti az információkat.

### [5.3 Bibliográfia](#bibliography)

##### Használt weboldalak

- [www.google.com](http://www.google.com)
- [www.w3cschools.com](http://www.w3cschools.com)
- [www.stackoverflow.com](http://www.stackoverflow.com)
- [www.quora.com](http://www.quora.com)
- [www.Scribd.com](http://www.Scribd.com)

##### Használt appok

- Youtube
- Solo Learn
- Udemy..