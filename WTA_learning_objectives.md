##Úvod do testovania##

**Testovanie je súbor procesov a činností, ktoré kontrolujú:**
*funkčnosť
*spoľahlivosť
*použiteľnosť
*výkonnosť
*bezpečnosť

**Testovanie zabezpečuje:**
*kvalitu produktu / softvéru
*znižovanie nákladov na opravu
*znižuje riziko neúspechu a finančnej straty
*včasne identifikuje bug

**Typ testov :**
*repetitívne
*regresné
*funkčné
*nefunkčné

#7 princípov testovania:#
-vyčerpávajúce testovanie je nemožné
-včasné testovanie
-ukazuje na prítomnosť defektov
-zhlukuje defetky
-pesticídny paradox
-testovanie je závislé na kontexte
-falošná predstava o neexistencii omylov

##Session based testing##
**MISSION**

**CHARTER**
**Session**
**REPORT**
-REPORT
-Zoznam chýb
**VYHODNOTENIE**

##Jira and Bug##
*priarita
vs.
*severita

Výsledky testovania:
-passed
-blocked
-retest
-failed


##Manažment testovania##
**Proces testovania:**
-Plánovanie testovania
-Vstupné kritériá
-Výstupné kritériá
-Odhadovanie
*na metrikách
*na expertíze

*Incident vs.defekt*
*incident(je problém na produkcii)
*defekt(je BUG)


##Modely vývoja software-u##
**Waterfall**
**V-Model**
**W-model**

Modely:
*iteratívny
*inkrementálny

Agilné metódy:
*SCRUM
*Kanban
*TDD(Test Driven Development)
*Crystal metodika
*XP(eXtreme Programming)


##Techniky tvorby testov##

**založené na špecifikácii** tzv.**_čierna skrinka_**
*rozdenie ekvivalencie
- jeden
- dva
- tri
*analýza hraničných hodnôt
*prechody stavov 
-stavový diagram
-stavové tabuľky

**založené na štruktúre** tzv.**_biela skrinka_**
*keď poznáme štruktúru kódu

**založené na skúsenostiach**
*error guessing
*fault attack
*exploratory testing


##HTML, CSS, JavaScript##
**HTML**
-tvorí základnú štruktúru stránky
*head
*body


**CSS**
-tvorí vizuál stránky

##Nástroje testovania##

**Čo sa dá testovať:**
*pokrytie
*bezpečnosť
*výkon

##Testovanie API##

HTTP request metódy:
GET
POST 
PUT 
DELETE 

Chybové hlášky na webe sú:
**4**00-client error 
**5**00-server error 

##SQL##
**Príkazy:*
SELECT
FROM 
WHERE
AND 
OR 
NOT 
LIKE
IN 
BETWEEN

**Typy Joinov:**
-left
-right
-inner
-full outer


##Robot Framework##
***Settings***
***Variables***
***Keywords***
***Test cases***


# Úvod do testovania 

**Riziko**

= neistota ako niečo dopadne

**Účel testovania** - znížiť negatívne riziko

**Výhody testovania** 
- redukcia obchodných rizík a finančných strát
- včasná identifikácia chýb = nižšie náklady na opravu chýb
- lepšia predvídateľnosť dodávky aplikácií
- znižovanie závažnosti chýb odhalených v produkcii
- komplexnosť

**Nedostatočné testovanie**
- zvýšené náklady na zákaznícku podporu
- neočakávané náklady na tvorbu a distribúciu servisných opravných balíkov
- strata tržieb/zákonné konsekvencie kvôli poruchám alebo výpadkom produkčných systémov
- odliv zákazníkov ku konkurencii kvôli výpadkom, zlým skúsenostiam a z toho plynúce straty tržieb

**Čo je to testovanie?**
- súbor procesov a činností, ktoré slúžia na kontrolu kvality softvérového produktu z hľadiska funkčnosti, spoľahlivosti, použiteľnosti, výkonnosti, či bezpečnosti
- poskytuje objektívny, nezávislý pohľad na kvalitu softvéru a poukazuje na riziká pri jeho vývoji
- môže dokázať prítomnosť chýb, ale nikdy ich neprítomnosť
- nezaručí bezchybnosť, ale dokáže minimalizovať výskyt kritických chýb 
- dáva dôveru v kvalitu vyvýjaného softvéru

# Session based testing 

- kontrolovaný exploratory testing
- rýchle objavenie chýb
- test dizajn v priebehu testovania
- okamžité reportovanie a vyhodnotenie

**MISSION**
- definuje význam testovania
- jednoduchý popis na čo sa má tester zamerať

**CHARTER**
- zoznam toho, čo sa bude testovať v rámci jednej session

**SESSION**
- definuje rámec, v rámci ktorého sa bude testovať
- trvá obvykle 45-120 minút
- nepretržité a nerušené testovanie
- zamerané na úlohy z charteru
- testovanie na základe nápadov, skúseností, heuristike (návodu,...)

**REPORT**
- zreportujem v ňom bugy
- mal by obsahovať: 
1. charter = zoznam úloh
2. oblasť, ktorá bola testovaná
3. popis, ako bol testing vykonávaný
4. zoznam chýb (najčastejšie v .xls)
5. zoznam problémov, otázok, nejasností
6. podiel z celkového času strávenom na testovaní: popisovanie a dohľadávanie bugov, príprava na session a iné aktivity nesúvisiace s testovaním
7. čas začiatku a celkovo strávený čas

**VYHODNOTENIE**
- diskusia medzi manažérom a testerom o reporte
- čo sa udialo počas testovania
- výsledky - čo ste dosiahli počas jednej session
- prekážky - čo bránilo testovaniu
- čo treba ešte otestovať, vykonať
- osobný pocit zo softvéru

# Jira and Bug
**JIRA**

Spoločná platforma pre projekt

Úlohy pre programátorov, bugy, reporty

Každá úloha má svoj stav

**Ako zadať bug**

1. Titulok - z názvu musí byť jasné o akú chybu ide
2. Popis/kroky - info ako sme sa k bugu dostali
3. Screenshot/video (odporúčajú sa pre rýchlejšie odhalenie chyby)
4. Vezia/prostredie
5. Verzia prehliadača - treba testovať vo viacerých prehliadačoch a vždy označiť, v ktorej verzii sme testovali
6. Chybová hláška - keď spravíme screenshot chybovej hlášky, skráti čas developverovi v hľadaní bugu
7. Priorita vs Severita
8. Labels, Components

**Priorita vs Severita**

*Severita* - aký dopad má chyba (väčšinou na zisk firmy)

*Priorita* - ako rýchlo má byť opravená

**Verzia vs Prostredie**

*Verzia* - vývoj softvéru v čase

*Prostredie* - Developérske, Testerské, Produkcia

**Chybová hláška**

![Chybová hláška](ERROR.jpg)

**Retest vs Regresné testovanie**

*Retest* - bola chyba opravená?

*Regresné testovanie* - nepokazilo sa opravou niečo iné?
# Manažment testovania 

**Postavenie QA v štruktúre projektu**

V štruktúre projektu sa väčšinou vytvára agilný tím v zložení: 
- Analytik 
- Vyvojár 
- Dizajnér 
- Tester

**Plánovanie a odhadovanie testovania**
- Definícia rizík, rolí a testovacej dokumentácie
- Integrácia v rámci životného cyklu softvéru
- Výber metrík pre monitoring

**Sledovanie a riadenie postupu testovania**
- Účel
- Monitorované informácie môžu byť zbierané manuálne alebo automaticky
- Metriky

**Riziko a testovanie**

Riziko delíme na:
- Projektové - ohraničujú schopnosť projektu dosiahnuť jeho ciele
- Produktové - ohrozujú kvalitu produktu

**Incident**
- problém na produkcii

**Technická špecifikácia**
- Dokument popisujúci 
požiadavky na aplikáciu
- Architektúru aplikácie
- Požiadavky na vzhľad
- Budúca verzia aplikácie

# Modely vývoja software-u 

**Sekvenčný vývoj**
- lineárny, sekvenčný tok činností
- nová fáza začína až po konci predchádzajúcej
- testovanie štandardne až na konci

**Waterfall - kaskádový model**

1. Requirement (požiadavka)
2. Design - akým spôsobom navrhneme systém
3. Implementation - vývojári tvoria kód
4. Verification - keď je kód napísaný, testeri testujú
5. Maintenance - údržba, nasadenie, kontrola chýb, optimalizujú sa procesy, najčastejšie u zákazníka

**V-model**

- ku každej fáze Waterfallu, existuje testovacia fáza

**W-model**

- implementujem včasné testovanie, už keď sa tvoria požiadavky
- keď overíme na začiatku požiadavky, či to viem podľa nich testovať, vieme dať pripomienky a chyby = ušeetríme neskôr náklady na vývoj a testing

**Iteratívny vývoj**

- vývoj sa opakuje v krátkych cykloch = iteráciách
- výsledkom iterácie by mal byť funkčný produkt, alebo jeho časť
- testovanie prebieha štandardne zároveň s vývojom

a) RAPID APPLICATION DEVELOPMENT 
b) ŠPIRÁLA 


# Techniky tvorby testov

# HTML, CSS, JavaScript 

**HTML**

- Hyper Text Markup Language
- popisný jazyk!!!
- definuje štruktúru stránky
- obsah stránky
- má dve časti: head a body

**CSS**

- popisný jazyk!!!
- definuje ako má stránka vyzerať: farby, písmo, odsadenia,...
- rozmiestnenie elementov na stránke
- vizuál stránky

**JavaScript**

- programovací jazyk!!!
- vie manipulovať s elementami, vytvárať, odoberať, editovať
- "vdýchne stránke život"

# Testovanie API 
# SQL 

# Robot Framework 
- jednoduchý genericky testovací automatický framework
- sekcie: 
1. *** SETTINGS ***
- definuje základné nastavenia RF
- aké knižnice používať, aké keywordy

2. *** VARIABLES ***
- definujem premenné

3. *** KEYWORDS ***
- definujem vlastné keywordy

4. *** TEST CASES ***
- definujem testovacie prípady