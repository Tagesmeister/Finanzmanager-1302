# Finanz-Webseite

Gruppe: Pascal Oestrich, Stefan Jesenko

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|    17.11.2023   | 0.0.1   | Heute haben wir begonnen, zu realisieren. Inputs wurden gemacht. |
|24.11.2023|0.2.0|Heute haben wir die zwei Inputs verbessert.|
|01.12.2023| 0.5.0   |Heute haben wir die Webseite schöner gemacht und kleine Fehler behoben.|
|08.12.2023|1.0.0| Wir haben die Webseite nach all unseren Vorgaben realisiert.|

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen eine dynmaische Onepage Webseite, indem man sein Finanzbudget berechnen lassen kann.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |     Muss            |  Funktionalität    | Ich als User möchte, dass ich meine Finanzen in Schreibfelder eintragen kann, damit das Programm meine Zahlen hat, um damit zu rechnen. |
| 2  |        Muss         |  Funktionalität    |     Ich als User möchte, dass meine eingegebenen Zahlen zusammen berechnet werden, sodass mein Budget ausgegeben wird.                               |
| 3  |        Muss         |   Funktionalität   |     Ich als User möchte, dass die Webseite dynamisch ist und beim Aufrufen immer ohne Zahlen erscheint, damit ich direkt meine Zahlen eingeben kann, ohne sie zuerst zu löschen.                               |
| 4  |         Muss        |  Qualität    |     Ich als User möchte, dass die Webseite schlicht und einfach gestaltet ist, damit ich ohne Verwirrung die Webseite verwenden kann.                               |
| 5  |          Muss       |  Qualität    | Ich als User möchte, dass ich für jedes Konto ein eigenes Feld eingeben kann, damit ich alles im Überblick behalten kann.                                   |
| 6  |      Muss           |  Qualität     | Ich als User möchte, dass mein ausgerechnetes Budget in einem eigenen Feld ausgegeben wird, damit das Resultat klar angezeigt wird.                                   |
| 7  |      Muss           |  Rand     | Ich als User möchte, dass die Webseite dynamisch ist und somit mit Javascript erstellt wurde.                             |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Webseite aufgerufen / gestartet + Eingabefeld für Konto "Bank"            |    543     |      Die Zahl wird in das Feld eingetragen.             |
| 2.1  |   Webseite aufgerufen / gestartet + Alle Zahlen in die Felder eingegeben          |   "Rechnen"      |     Das berechnete Budget erscheint im Budgetfeld.              |
| 3.1  |    Webseite wird aufgerufen / gestartet        |   *nichts*     |      Die Webseite erscheint mit leeren Eingabefeldern.             |
| 4.1  | Webseite aufgerufen / gestartet         |    *nichts*     |    Die Eingabefelder erscheinen nacheinander / übereinander.            |
| 5.1  | Webseite aufgerufen / gestartet            |    *nichts*     |      Die Eingabefelder mit der Beschriftung von jedem Konto erscheinen nacheinander / übereinander.             |
| 6.1  |    Webseite wird aufgerufen / gestartet        |   Drücke den Button "Rechnen"     |      Das berechnete Budget wird in dem Budgetfeld ausgegeben.             |
| 7.1  |    *nichts*         |   *nichts*     |      *Die Webseite ist mit Javascript erstellt worden.*             |

### 1.4 Diagramme

![image](https://github.com/Tagesmeister/Finanz-Webseite/assets/110892250/0d026970-434c-450b-9237-cddaa38c4aef)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   17.11.2023    |    Pascal Oestrich & Stefan Jesenko       |  sich in Javascript einlesen            |    1           |
| 1.B  |   17.11.2023    |    Pascal Oestrich       |       Realisierung vom GUI für die Webseite       |       1.5        |
| 2.A  |   17.11.2023    |    Stefan Jesenko       |       Realisierung von den Eingabefeldern        |       1.5        |
| 2.B  |   24.11.2023    |    Pascal Oestrich       |       Realisierung vom Zusammenrechnen der Eingaben      |       1        |
| 3.A  |   24.11.2023    |    Stefan Jesenko      |       Realisierung vom dynamischen Interface       |       2        |
| 4.A  |   1.12.2023    |    Pascal Oestrich       |       Realisierung von der Feingestaltung der Webseite     |       1.5        |
| 5.A  |   1.12.2023    |    Stefan Jesenko      |       Eingabefeld designen und realisieren     |       1        |
| 6.A  |   8.12.2023    |    Pascal Oestrich & Stefan Jesenko      |       Realisierung der Budgetausgabe     |       2.5        |
| 6.A  |   17.11.2023 - 15.12.2023   |    Pascal Oestrich & Stefan Jesenko      |       Realisierung in einer Webapplikation     |       -        |

Total: 12 Arbeitspakete = 540 min

## 3 Entscheiden

Wir haben uns entschieden, das Produkt wie geplant umzusetzen. Da wir das erste Mal mit Javascript arbeiten, haben wir mehr Zeit in die Realisierung eingeplant.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |17.11.2023|Stefan&Pascal|1|1|
| 1.B  |17.11.2023|Pascal|1.5|1|
| 2.A  |17.11.2023|Stefan|1.5|2|
| 2.B  |24.11.2023|Pascal|1.5|1.5|
| 3.A  |24.11.2023|Stefan|2|1.5|
| 4.A  |01.12.2023|Pascal|1.5|2|
| 5.A  |01.12.2023|Stefan|1|1.5|
| 6.A  |08.12.2023|Pascal&Stefan|2.5|2|



## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |   15.12.2023    |     OK     |    Pascal Oestrich    |
| 2.1 |  15.12.2023      |    OK      |    Pascal Oestrich    |
| 3.1  |  15.12.2023      |   OK       |    Pascal Oestrich    |
| 4.1  |  15.12.2023      |    OK      |    Pascal Oestrich    |
| 5.1  |  15.12.2023      |   OK       |     Pascal Oestrich   |
| 6.1  |  15.12.2023      |   OK       |   Pascal Oestrich     |
| 7.1  |  15.12.2023      |     OK     |    Pascal Oestrich    |

### Fazit:
Das Programm läuft optimal, alle Tests hatten ein positives Ergebnis. Das Produkt ist fertig.

## 6  Portfolio

Pascal Oestrich: https://portfolio.bbbaden.ch/view/view.php?id=33265

Stefan Jesenko
