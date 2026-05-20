# KK1 – Analys av Penguins

Detta projekt är en explorativ dataanalys av Penguins datasetet genomförd i Python med pandas, numpy, matplotlib och seaborn.

Syftet är att undersöka skillnader mellan pingvinarter genom datatvätt, analys och visualisering.

## Dataset

Datasetet innehåller mätningar av pingviner. 
Varje rad representerar en individuell pingvin.

Variabler inkluderar bland annat:
- kroppsmassa
- flipperlängd
- näbblängd
- näbbdjup
- art
- ö

Datasetet hämtades ursprungligen via seaborn och sparades därefter lokalt som CSV för reproducerbar analys.

## Projektstruktur

.
├── notebook.ipynb
├── README.md
└── data
    ├── raw
    │   └── penguins_raw.csv
    └── processed
        └── penguins_clean.csv



## Körning

Installera beroenden med uv:
uv sync



Starta sedan notebooken:
uv run jupyter notebook



## Fokus i analysen

Notebooken fokuserar på:

datatvätt och hantering av saknade värden
gruppjämförelser med pandas
visualisering med matplotlib/seaborn
val av diagramtyp utifrån analytisk fråga
reflektion kring datans begränsningar