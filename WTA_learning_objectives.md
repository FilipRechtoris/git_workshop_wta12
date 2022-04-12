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
# Session based testing 
# Jira and Bug
**JIRA**

Spoločná platforma pre projekt

Úlohy pre programátorov, bugy, reporty

Každá úloha má svoj stav

**Ako zadať bug**

1. Titulok
2. Popis/kroky
3. Screenshot/video
4. Vezia/prostredie
5. Verzia prehliadača
6. Chybová hláška
7. Priorita vs Severita
8. Labels, Components

**Priorita vs Severita**

*Severita* - aký dopad má chyba

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
# Modely vývoja software-u 
# Techniky tvorby testov
# HTML, CSS, JavaScript 
# Testovanie API 
# SQL 
# Robot Framework 
