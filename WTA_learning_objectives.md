# Úvod do testovania 
## Prečo testovat?

**Účel testovania**

    - riziko = neistota 
    - účel testovania = eliminovať negatívne dopady rizika => čo najhoršie sa môže stať?

**Výhody testovania**

    - redukcia obchodných rizík a finančných strát   
    - včasná identifikácia chýb = nižšie náklady na opravy chýb   
    - lepšia predvídateľnosť dodávky aplikácii   
    - znižovanie závažnosti chýb odhalených v produkcii   
    - potreba overiť funkčnosť čoraz komplexnejších software

**Nedostatočné testovanie**
   
    - zvýšené náklady na zákaznícku podporu   
    - neočakávané náklady na tvorbu a distribúciu servisných opravných balíkov   
    - strata tržieb/zákonné konzekvencie kvôli poruchám alebo výpadkom produkčných systémov   
    - odliv zákazníkov ku konkurencii kvôli výpadkom, zlým skúsenostiam a z toho plynúce straty tržieb

## Čo je to testovanie
   
    - súbor procesov a činností, ktoré slúžia na kontrolu kvality software z hľadiska funkčnosti, spoľahlivosti, použiteľnosti, výkonnosti a bezpečnosti   
    - poskytuje objektívny, nezávislý pohľad na kvalitu software a poukazuje na riziká pri jeho vývoji   
    - môže dokazovať prítomnosť chýba, ale nikdy ich neprítomnosť   
    - nezaručí bezchybnosť,ale dokáže minimalizovať výskyt kritických chýb   
    - dáva dôveru v kvalitu vyvíjaného software

**Úlohy testovania**
    
    - môže merať kvalitu software    
    - môže dať dôveru v kvalitu testovaného software    
    - pomáha zlepšovať kvalitu software    
    - môže zlepšiť kvalitu procesov

**Ciele testovania**
    
    - nájdenie defektov    
    - získanie dôvery s ohľadom na úroveň kvality    
    - poskytunutie informácii pre rozhodovanie    
    - predchádzanie defektom

**7 princípov testovania**
    
    - testovanie ukazuje prítomnosť defektov, ale nikdy ich neprítomnosť    
    - vyčerpávajúce testovanie je nemožné    
    - včasné testovanie    
    - Zhlukovanie defektov = Paretov princíp    
    - pesticídny paradox    
    - závislosť na kontexte    
    - falošná predstava o neexistencii omylov

# Session based testing 

    - kontrolovaný exploratory testing
    - test design sa robí v priebehu testovania
    - okamžité reportovanie a vyhodnotenie testu

**Session Based Testing**

    - Mission = definuje význam testovania
    - Charter = zoznam úloh
    - Session = definuje rámec
    - Report
        - zoznam úloh
        - testovaná oblasť
        - popis ako bol testing vykonaný
        - zoznam nájdených chýb
        - zoznam otázok a nejasností
        - čas
    - Vyhodnotenie = PROOF
        - Past
        - Results
        - Obstacles
        - Outlook
        - Feelings

# Jira and Bug

## Defekt/bug vs Zlyhanie

    - defekt = bug = chyba => žije vlstným životom v software
    - zlyhanie = výsledok činnosti chybného software

**Bug v Jira**

    - titulok
    - popis/kroky
    - actual result
    - expected result
    - version
    - priority
    - severity
    - labels
    - components

# Manažment testovania 

## Persóny

    - analytik
    - dizajnér
    - vývojár
    - test manažér
    - tester

## Proces testovania

    - analýza a návrh testov 
        - plánovanie
        - vstupné a výstupné kritéria
        - estimácia        
    - implementácia a vykonanie testovania
    - vyhodnotenie výstupných kritérií, reportovanie a aktivity na uzatvorenie testovania

 ## TestRail

     - základy využitia Test Railu na manažment Test Casov


# Modely vývoja software

## Sekvenčné vývojové metódy

    - waterfall
    - V-model
    - W-model

## Iteratívny vývoj

    - RAD
    - Spiral model

## Iteratívny a inkrementálny vývoj

    - XP = extreme programming
    - TDD = test driven development
    - scrum
    - kanban
    - crystal

# Techniky tvorby testov

## Proces vývoja testu

    - analýza
    - sledovateľnosť
    - dizajn
    - očakávané výsledky
    - implementácia

# Techniky návrhu testov

**Techniky založené na špecifikácii [Black Box]**

    - rozdelenie ekvivalencie
    - analýza hraničných hodnôt
    - rozhodovacie tabulky
    - testovanie prechod stavov
    - testovanie prípadov použitia

**Techniky založené na štruktúre [White Box]**

    - testovanie pokrytia príkazov
    - testovanie pokrytia rozhodovaní
    - testovanie pokrytia podmienok
    - etovanie pokrytia modulov, etc.

**Techniky založené na skúsenostiach**

    - error guessing
    - exploratory testing

# HTML, CSS, JavaScript 

## HTML
 
    - popisný jazyk => definuje štruktúru

## CSS

    - definuje vizuál

## JavaScript

    - programovací jazyk => rozpohybuje stránku

# Nástroje testovania 

**Nástroje na zápis test casov**

    - Excel
    - Jira
    - TestLink
    - TestRail
    - XRay

**Nástroje na vytváranie testovacích dát**

    - generovanie
    - anonymizácia
=> Postman    

**Testovanie pokrytia**

    - SonarQube

**Nástroje na testovanie bezpečosti**

    - simulácie útokov na FE, BE, DB
        - HTML injection
        - SQL injection
    

**Nástroje na testovanie výkonu**

    - performance testy => rýchlosť odpovede serveru
    - stress testy => počet chybných odpovedí
    - scalability testy => využitie hardware
=>JMeter
=> LoadRunner

**Statická analýza**

    - vykonáva sa nad kódom, ktorý nie je spustený
    - nástroj per programovací jazyk
=> Java => Checkstyle, IntelliJ IDEA 

**Selenium IDE**

    - nástroj pre automatické testovanie webových aplikacií
    - nezáleží na poradí
    - spustiteľné nezávisle


# Testovanie API 

## API

    - application programming interface = set of rules that software can follow to communicate
    - REST API = representional state transfer => stateless clien-server communication protocol
    - HTTP = hypertext transfer protocol

**HTTP Request Metódy**

    - GET
    - POST
    - PUT
    - DELETE

**HTTP Response Status Kódy**

    - 1xx => informational
    - 2xx => success
    - 3xx => redirect
    - 4xx => client error
    - 5xx => sever error

## Postman

    - nástroj na manuálne a automatizované testovanie rozhraní
        - collection
        - environment
        - snippets
        - iterations
        - console
        - random
        - export

# SQL 

## Základy databáz

**Relačné databázy**

    - DML
    - DDL

**DML Syntaktické konštrukcie SQL**

    - SELECT
    - INSERT
    - UPDATE
    - DELETE

**DDL CRUD Operácie**

    - CREATE
    - READ
    - UPDATE
    - DELETE

# Robot Framework 

    - open source automation framework na akceptačné testovanie
    - keyword based
    - Python