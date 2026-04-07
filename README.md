# pokemondb-de

Eine bereinigte und strukturierte Datenbank aller Pokémon mit deutschen Namen, Typen und Basiswerten (Stats).

## Features
- **Deutsche Lokalisation:** Alle Namen und Typen sind auf Deutsch.
- **Tab-getrenntes Layout (TSV):** Perfekt für den Import in Excel, Google Sheets oder zur Weiterverarbeitung in Skripten.

## Datenformat
Die Liste ist in folgenden Spalten aufgebaut:

1. **Nr**: Die offizielle Pokédex-Nummer.
2. **Name**: Der deutsche Name des Pokémon.
3. **Typ 1**: Primärer Typ.
4. **Typ 2**: Sekundärer Typ (oder `-` falls nicht vorhanden).
5. **KP**: Kraftpunkte (Hit Points).
6. **Ang**: Angriff (Attack).
7. **Ver**: Verteidigung (Defense).
8. **SpA**: Spezial-Angriff (Special Attack).
9. **SpV**: Spezial-Verteidigung (Special Defense).
10. **Init**: Initiative (Speed).

## Beispiel
| Nr | Name | Typ 1 | Typ 2 | KP | Ang | Ver | SpA | SpV | Init |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 001 | Bisasam | Pflanze | Gift | 45 | 49 | 49 | 65 | 65 | 45 |
| 004 | Glumanda | Feuer | - | 39 | 52 | 43 | 60 | 50 | 65 |
| 1005 | Donnersichel | Drache | Unlicht | 105 | 139 | 71 | 55 | 101 | 119 |

## Credits
Ein herzliches Dankeschön geht an [pokemondb.net](https://pokemondb.net/). 

Die englischen Originaldaten und Basiswerte (Base Stats), auf denen dieses Projekt basiert, stammen von ihrer umfangreichen Datenbank. Ohne ihre Vorarbeit wäre diese strukturierte deutsche Fassung nicht möglich gewesen.
