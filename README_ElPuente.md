# Shop Daten Analyse – El Puente (2021)

Verkaufsanalyse eines Fair-Trade-Dienstleisters mit Sitz in Nordstemmen, Deutschland. Grundlage sind Verkaufsdaten aus zwei Regionen für das Jahr 2021.

## Datenbasis

| Datei | Region | Inhalt |
|---|---|---|
| `Shop_Data.xlsx` | Deutschland | 3 Produkte (P1→A, P2→B, P3→C), monatlich |
| `Shopauswertung.csv` | Europa | Produkte A, B, A+B+C, täglich |

Produkt C für Europa wurde rechnerisch ermittelt: **C = (A+B+C) − A − B**

## Wichtigste Erkenntnisse

- Europa generiert 95,1 % des Gesamtumsatzes (40,2 Mio. €) – mit konstantem Wachstum über das gesamte Jahr.
- Produkt C dominiert in beiden Regionen mit 90,9 % des Gesamtumsatzes (38,4 Mio. €).
- Produkt A ist in Europa nahezu irrelevant (0,0 %) – strategische Neubewertung empfohlen.
- Der Wochentag hat keinen messbaren Einfluss auf den Umsatz – gleichmäßige Verteilung über alle Tage.

## Projektstruktur

```
README.md
shop_data_analyse_bereinigt.ipynb   -- Analyse-Notebook (Python)
ElPuente_Analyse.pptx               -- Präsentation mit Ergebnissen
Shop_Data.xlsx                      -- Rohdaten Deutschland
Shopauswertung.csv                  -- Rohdaten Europa
```

## Voraussetzungen

Python 3.x – benötigte Bibliotheken: `pandas`, `matplotlib`, `seaborn`, `openpyxl`

```bash
pip install pandas matplotlib seaborn openpyxl
```

## Autorin

Nadiia Kotykova
