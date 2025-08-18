---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# STOP SP-PAC
[Najnowsze loty](./2025/2025-08/)

### Loty SP-PAC w Bednarach (EPPB)
Kliknij w miesiąc poniżej aby przejść do danych.

* Rok 2025
  * [Sierpień](./2025/2025-08/)
  * [Lipiec](./2025/2025-07/)
  * [Czerwiec](./2025/2025-06/)
  * [Maj](./2025/2025-05/)
  * [Kwiecień](./2025/2025-04/)
* Rok 2024
  * [Październik](./2024/2024-10/)
  * [Sierpień](./2024/2024-08/)
  * [Lipiec](./2024/2024-07/)
  * [Czerwiec](./2024/2024-06/)
  * [Maj](./2024/2024-05/)
<br>
<br>

*Uwagi:*
* *brak danych dla dni (kiedy samolot latał):*
  * *2024-07-20 (brak możliwości pobrania plików z FR24)*
  * *2024-08-30 (brak możliwości pobrania plików z FR24)*
* brak lotów we wrześniu 2024 - impreza AgroShow na lotnisku

### Cel
Strona dokumentuje przeloty samolotu SP–PAC należącego do SkyCamp, który od ponad dwóch lat generuje nadmierny hałas, zakłócając w ten sposób spokój mieszkańców. Gromadzimy tutaj dokumentację tych działań, korzystając z ogólnie dostępnych źródeł.

### Jak zbieramy dane
* Dane z przelotów samolotu SP-PAC są na bieżąco pobierane z serwisu [FligthRadar24 SP-PAC](https://www.flightradar24.com/data/aircraft/sp-pac) (dane dostępne za 3 ostatnie miesiące bez opłat) w postaci plików CSV zawierających odczyty z transpondera samolotu - w każdym wierszu znajduje się odczyt: data, koordynaty geograficzne, numer rejestracyjny, wysokość, prędkość i kierunek lotu
* Na podstawie zebranych danych generowany jest obraz z przelotami danego dnia, które prezentowane są na mapie.
* Na zebranych plikach pogrupowanych według dat przeprowadzamy analizę, zliczając przeloty i czasu brutto i netto samolotu w powietrzu.
* Z tych informacji automatycznie generowane są podstrony dla poszczególnych dni i miesięcy.


Przykładowe dane:
```
Timestamp,UTC,Callsign,Position,Altitude,Speed,Direction
1717917213,2024-06-09T07:13:33Z,SPPAC,"52.533733,17.22876",600,98,108
1717917223,2024-06-09T07:13:43Z,SPPAC,"52.532059,17.237078",700,108,107
1717917229,2024-06-09T07:13:49Z,SPPAC,"52.531174,17.24205",750,113,106
1717917235,2024-06-09T07:13:55Z,SPPAC,"52.530338,17.24728",825,118,103
1717917238,2024-06-09T07:13:58Z,SPPAC,"52.529938,17.250061",850,120,102
1717917241,2024-06-09T07:14:01Z,SPPAC,"52.529636,17.252066",900,120,102
1717917243,2024-06-09T07:14:03Z,SPPAC,"52.529343,17.254486",950,119,100
1717917247,2024-06-09T07:14:07Z,SPPAC,"52.529125,17.257639",1000,119,96
1717917250,2024-06-09T07:14:10Z,SPPAC,"52.528976,17.260437",1050,118,94
1717917252,2024-06-09T07:14:12Z,SPPAC,"52.528976,17.262878",1100,117,89
1717917255,2024-06-09T07:14:15Z,SPPAC,"52.529068,17.265167",1150,116,87
1717917259,2024-06-09T07:14:19Z,SPPAC,"52.529297,17.268295",1225,115,81
...
```
