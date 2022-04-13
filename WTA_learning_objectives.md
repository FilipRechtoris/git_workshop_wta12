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
# Modely vývoja software-u 
# Techniky tvorby testov
# HTML, CSS, JavaScript 
# Testovanie API 
# SQL 
# Robot Framework 
