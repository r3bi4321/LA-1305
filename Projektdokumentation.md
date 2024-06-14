# Projekt-Dokumentation



| Datum | Version | Zusammenfassung                                          |
| ----- | ------- | -------------------------------------------------------- |
|03.05.2024|0.0.1| User Stories und Testfälle geschrieben                    |
|17.05.2024|0.0.2| Arbeitspakete erstellt, mit Realisieren begonnen.         |
|24.05.2024|0.0.3| Arbeitspaket 1 und  2                                     |
|31.05.2024|0.0.4| Arbeitspaket 5 und  6                                     |
|07.06.2024|0.0.5| Arbeitspaket 7 und  8                                     | 
|14.06.2024|0.0.6| Kontrolliert und Portfolio geschrieben                    |

## 1 Informieren

### 1.1 Ihr Projekt

Mein Projekt ist ein Vokabeltrainer. 

Ich möchte einen Vokabelrtainer erstellen. Die Vokabeln sollen in einer NOSQL Datenbank abgespeichert werden, welche mit dem Programm verbunden ist. 

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss  | Funktionalität | Als User möchte ich die Vokabeln erfassen können. |
| 2    | Muss  | Funktionalität | Als User möchte ich, die Übersetzung zu jedem Wort eingeben können.|
| 3    | Muss  | Funktionalität | Als User möchte ich die eingegebenen Vokabeln speichern können.|
| 4    | Muss  | Funktionalität | Als Programmierer möchte ich, dass die Vokabeln in einer MongoDB gespeichert werden.| 
| 5    | Muss  | Funktionalität | Als User möchte ich auch ältere Sets üben können.|
| 6    | Muss  | Funktionalität | Als User möchte ich, dass die Antworten überprüft werden.|
| 7    | Muss  | Funktionalität | Als User möchte ich, dass Wörter welche falsch beantwortet wurden, wiederholt werden.| 
| 8    | Muss  | Funktionalität | Als User möchte ich, dass ich jedes Wort 2 mal richtig schrieben muss, damit es als gelernt gilt.| 



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Vokabeln erfassen ausgewählt,  | Vokabel eingeben| Vokabel aufgelistet|
| 2.1  | Vokabeln erfassen ausgewählt, Vokabel eingeben| Geben sie die deutsche Übersetzung ein| Eingabe Übersetzung |
| 3.1  | Vokabel eingegeben| "Vokabel speichern"| Vokabel wird in DB gespeichert|
| 4.1  | MongoDB erstellen| Vokabeln eingeben und speichern| Vokabeln werden gespeichert| 
| 5.1  | Applikation läuft| Set auswählen| Vokabeln werden aufgerufen|
| 6.1  | Vokabelset gestartet, Vokabel eingegeben| "enter"| Vokabel ist korrekt|
| 6.2  | Vokabelset gestartet, Vokabel eingegeben| "enter"| Vokabel ist inkorrekt|
| 7.1  | Vokabel falsch eingegeben| Wiederholen sie die Vokabel| Vokabel eingeben| 
| 8.1  | Vokabel richtig geschrieben, späterer Versuch| Vokabel nochmals richtig eingeben| Vokabel korrekt, wird nicht mehr gebracht| 




## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 14.06.2024  | Rebecca Willi          |  Vokabel erfassen            |     90min          |
| 2.A  | 14.06.2024  | Rebecca Willi          |    Übersetzung erfassen          |     60min          |
| 3.A  | 14.06.2024  | Rebecca Willi          |      Eingaben speichern        |       90min        |
| 4.A  | 14.06.2024  | Rebecca Willi          |    Eingaben in DB speichern          |    150min           |
| 5.A  | 14.06.2024  | Rebecca Willi          |    Ältere sets öffnen können       | 30min| 
| 6.A  | 14.06.2024  | Rebecca Willi          |  Antworten überprüfen | 60min|
| 7.A  | 14.06.2024  | Rebecca Willi          | Antworten wiederholen | 45min | 
| 8.A  | 14.06.2024  | Rebecca Willi          | Abfrage Wiederholen | 60 min| 


## 3 Entscheiden



## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| 2.A  |       |           |               |                   |
| 3.A  | 


## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.


