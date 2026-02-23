# Evidence vstupu – zadání

## Popis

Naprogramujte modul s REST API pro evidenci vstupu a výstupu osob pomocí čipových karet.

## Požadavky

### 1. Evidence příchodů a odchodů

Ze vstupního senzoru přichází pouze **ID karty**. API musí zaznamenat každý příchod i odchod spolu s časovým razítkem.

### 2. Historie

Modul si pamatuje historii všech zaznamenaných příchodů a odchodů. Historii musí být možné procházet a filtrovat (např. podle karty nebo časového rozsahu).

### 3. Provázání ID karty s osobou

Každou kartu lze přiřadit konkrétní osobě. API musí umožnit správu osob (vytvoření, čtení, úpravu, smazání) a přiřazení karty k osobě.

### 4. Složitější use-case: Přehled docházky osoby za zvolené období

Pro zvolenou osobu a časový rozsah API vrátí:

- seznam všech jejích příchodů a odchodů (spárované sessiony),
- dobu trvání každé návštěvy,
- celkovou dobu přítomnosti za dané období.
