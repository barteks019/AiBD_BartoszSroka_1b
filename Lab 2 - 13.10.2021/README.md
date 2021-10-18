# Opracowanie danych pogodowych

## Opis folderów:
- AnalysisData - katalog zawiera wynikowe opracowanie danych wejściowych
- OriginalData - nieprzetworzone dane wejściowe
- Documents - pliki opisujące
- CommandFiles - zawiera intrukcję, która przetwarza dane do danych wyjściowych

## Problem:
Przetworzenie i uporządkowanie danych z (Global Historical Climatology Network) w 5 miesiącach 2010 roku, dla stacji pogodowej w Meksyku.
### link do dokumentacji:
https://www.ncei.noaa.gov/data/global-historical-climatology-network-daily/doc/GHCND_documentation.pdf?fbclid=IwAR3EzG4swUSEs8WKx_yAtdZtdjNoOujeQz_Fkb16d199aifnlIL9FOZX-Cg

## Opracowanie danych:
Większość z otrzymanych danych zawiera wartości -9999 w przypadku takich wartości nie jesteśmy w stanie ich w jakikolwiek sposób ich uśrednić dlatego podmieniamy je wartością Nan.
