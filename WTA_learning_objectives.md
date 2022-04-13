# Úvod do testovania 
* Prečo testovať - čo je testovanie, ciele a výhody testovania, riziká
* Omyl, defekt, zlyhanie
* Quality Assurance vs Quality Control vs Testing
* 7 princípov testovania
* Proces testovania
# Session based testing 
* Mission
* Charter

**Report:**
* Charter
* Testovaná oblasť
* Popis testovania
* Zoznam chýb v .xls 
* Otázky a nejasnosti
* Čas začiatku / podiel času stráveného testovaním, spisovaním chýb, písaním repotu a pod. 
 
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

**Životný cyklus bugu** 
(open/in progress/ready for test/reopen/resolved/closed)

# Manažment testovania 
* Postavenie QA v štruktúre projektu (jednotlivé role v rámci teamu, postavenie a úlohy testera)
* Proces testovania (plánovanie testovania, vstupné a výstupné kritéria, odhadovanie testovania, plán testovania)
* Sledovanie a riadenie postupu testovania (metriky testovania)
* Riziká a testovanie (produktové a projektové riziká)
* Incident vs. defekt=bug
* Funkčná a technická špecifikácia

**Testrail** a použitie v praxi (test cases, test run, report, milestone)

# Modely vývoja software-u 
**Waterfall/kaskádový model** a jeho 5 hlavných fáz:
* Requirements
* Design
* Implementation
* Verification
* Maintanance

**V-model**

**W-model**

**Iteratívny vývoj** a jeho metódy

**Agilný vývoj** a jeho princípy, metodiky

* **Scrum** (sprint, role)
* **Kanban** 
* **Crystal metodika**

# Techniky tvorby testov
**Test case** má obsahovať minimálne:

* ID
* Položky testu (čo bude testované a čo je cieľ testu)
* Špecifikácia vstupov
* Špecifikácia výstupov
* Požiadavky na prostredie
* Špeciálne procedurálne požiadavky
* Závislosti na iných test cases

**Techniky návrhu testov:**

* **založené na špecifikácii = black box**

    * rozdelenie ekvivalencie
    * analýza hraničných hodnôt
    * testovanie rozhodovacích tabuliek
    * testovanie prechodu stavov
    
* **založené na štruktúre = white box**

    * testovanie pokrytia príkazov
    * testovanie pokrytia rozhodovaní
    * testovanie pokrytia podmienok a viacnásobných podmienok
    * testovanie pokrytia modulov, komponentov, tried
    
* **založené na skúsenostiach**

    * error guessing
    * exploratory testing

# HTML, CSS, JavaScript 
# Testovanie API 
# SQL 
# Robot Framework 
