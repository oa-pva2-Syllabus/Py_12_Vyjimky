# PVA2 - Programování a vývoj aplikací
## Cvičení 12: Výjimky

## Pravidla
- Program nesmí spadnout (nesmí skončit tracebackem).
- Vždy vypiš srozumitelnou hlášku pro uživatele.
- Nezachytávej všechno přes holé except: pokud to není výslovně požadováno.
- Používej cyklus, pokud má uživatel zadat vstup „znovu“.

### 1 Načtení čísla
Deklaruj funkci nacti_int, která zobrazí výzvu uživateli pro načtení vstupu od uživatele. Pokud uživatel zadá neplatné číslo, vypíše hlášku a zeptá se znovu. Funkce bude vracet platné celé číslo.

Hodnoty pro otestování: Uživatel zadá: abc, 12.5, -7, 10 → funkce vrátí -7 a pak 10 podle běhu.

### 2 Dělení
Napiš program pro dělení dvou celých čísel. Program vypíše výsledek ve tvaru `Výsledek v Celé dělení x a zbytek y`. Například pro 6/4 `Výsledek 1.5 Celé dělení 1 a zbytek 2`

Ošetři špatný vstup a dělení nulou.

### 3 Neexistující index
Ošetřete situaci v souboru `neexistujici_index.py`, aby program nespadnul při přístupu na neexistující index.

### 4 Přetypování

Ošetřete situaci v souboru `pretypovani.py`, která může nastat při pokusu o přetypování. Vyzkoušetje zadat řetětec, který se nebude skládat pouze z čísel desítkové číselné soustavy.

### 5 Game
V programu `game.py` zapracujte zpracování výjimek. V zprávě uživateli zobrazte taktéž i hodnotu, jakou se uživatel pokusil zadat.

Funkčnost ověřte zadání textových vstupů a desetinných hodnot.

### 6 Zachycení více druhů výjimek
V programu `math.py` naprogramujte funkci `calcDivAbyB`, která bude mít dva vstupní atributy `a,b`. Funkce bude provádět výpočet dle vzorce:

`((a + b) // (a - b))`. 

Do funkce zapracujte zpracování výjimek a ošetřete situace:
* dělení nulou
* zadání textu do atributu

### 7 Validace věku

- Vytvoř vlastní výjimku `InvalidAgeError`
- Deklaruj funkci pro ověření věku, která:
  - pokud je vek menší než 0 nebo větší než 130 → vyhodí InvalidAgeError
  - jinak vrátí True


