# SQL projekce: Filmový klub

**Databáze:** MariaDB, databáze `filmovy_klub`  
**Tabulky:** `student`, `film`, `vstupenka`  
**Počet úloh:** 12

## Pravidla

1. Každou úlohu vyřeš jedním SQL dotazem.
2. Použij tabulky `student`, `film` a `vstupenka`.
3. Spojení tabulek zapiš jako `JOIN`. `LEFT JOIN` ani `RIGHT JOIN` nepoužívej.
4. Odevzdej SQL dotaz ke každé úloze.
5. U úloh s řazením dodrž všechna uvedená pravidla řazení.

## Úloha 1 – Výpis všech studentů

Vypiš všechny sloupce a všechny záznamy z tabulky `student`.

## Úloha 2 – Základní informace o studentech

Vypiš `jmeno`, `prijmeni`, `rocnik` a `datum_nastupu` všech studentů.

## Úloha 3 – Studenti vyšších ročníků

Vypiš všechny sloupce studentů, jejichž `rocnik` je vyšší než 3.

## Úloha 4 – Příjmení s „ová“

Vypiš `jmeno` a `prijmeni` všech studentů, jejichž příjmení obsahuje text `ová`.

## Úloha 5 – Seřazení studentů

Vypiš `id_student`, `jmeno`, `prijmeni` a `rocnik` všech studentů. Seřaď je podle `rocnik` sestupně. Při stejném ročníku je seřaď podle `id_student` vzestupně.

## Úloha 6 – Dlouhé filmy

Vypiš `nazev`, `zanr` a `delka_min` filmů, jejichž délka je vyšší než 150 minut.

## Úloha 7 – Vstupenky studentů

Vypiš `jmeno`, `prijmeni`, `id_vstupenka` a `sedadlo`. Propoj tabulky `student` a `vstupenka` pomocí `JOIN`.

## Úloha 8 – Vstupenky na filmy

Vypiš `nazev` filmu, `zaplaceno_kc` a `sedadlo`. Propoj tabulky `film` a `vstupenka` pomocí `JOIN`.

## Úloha 9 – Návštěvy komedií

Vypiš `jmeno`, `prijmeni` a `nazev` filmu u všech vstupenek na film se žánrem `komedie`. Propoj tabulky `student`, `vstupenka` a `film` pomocí `JOIN`.

## Úloha 10 – Vstupenky dražší než 200 Kč

Vypiš `jmeno`, `prijmeni`, `nazev` filmu, `id_vstupenka` a `zaplaceno_kc` u vstupenek dražších než 200. Propoj potřebné tabulky pomocí `JOIN`.

## Úloha 11 – Kompletní přehled projekce

Vypiš `jmeno`, `prijmeni`, `nazev` filmu a `datum_projekce`. Propoj všechny tři tabulky pomocí `JOIN`.

## Úloha 12 – Nejdražší vstupenky

Vypiš `jmeno`, `prijmeni`, `nazev` filmu a `zaplaceno_kc`. Propoj všechny tři tabulky pomocí `JOIN`. Seřaď výsledek podle `zaplaceno_kc` sestupně a při stejné částce podle `id_vstupenka` vzestupně.

## Odevzdání

Ke každé úloze odevzdej SQL dotaz, kterým jsi ji vyřešil/a.
