-------------
# MuM's Fit Software Requirements Specification #
-------------
**MuM's Fit**  
**Software Requirements Specification**

**Version 2.3**

## Revision History ##
| Date       | Version | Description                                      | Author |
|------------|---------|--------------------------------------------------|--------|
| 20/10/2016 | 1.0     | Dokument erstellt                                | MuM    |
| 25/10/2016 | 1.1     | Formelle Änderung des Inhalts                    | MuM    |
| 28/10/2016 | 1.2     | UCD Details hinzugefügt                          | MuM    |
| 28/10/2016 | 1.3     | UCD löschen hinzugefügt                          | MuM    |
| 14/11/2016 | 1.4     | Links aktualisiert und UCD erstellen hinzugefügt | MuM    |
| 21/11/2016 | 1.5     | Link SAD Hinzugefügt                             | MuM    |
| 07/12/2016 | 1.6     | UCD Plan ansehen Hinzugefügt                     | MuM    |
| 10/12/2016 | 1.7     | UCD Plan bearbeiten Hinzugefügt                  | MuM    |
| 12/12/2016 | 1.8     | Fehlende Punkte ausgefüllt                       | MuM    |
| 05/04/2017 | 2.0     | Dateiformat zu .md geändert                      | MuM    |
| 20/04/2017 | 2.1     | neue Usecases hinzugefügt                        | MuM    |
| 25/04/2017 | 2.2     | Links hinzugefügt                                | MuM    |
| 22/06/2017 | 2.3     | update für final                                | MuM    |

## Table of Contents ##
1. Introduction
	1. Purpose
	2. Scope
	3. Definitions, Acronyms and Abbreviations
	4. Document - References
2. Overall Description
	1. Product Perspective
	2. Product Functions
	3. User Characteristics
	4. Constraints
	5. Assumptions and Dependencies
3. Specific Requirements
	1. Funcionality
		1. Overall Use-Case-Diagram
		2. Startseiten-Optionen
		3. Bearbeitung-Optionen
		4. Beenden
	2. Usability
		1. Training Time
		2. Hardware Requirements
		3. Software Requirements
	3. Reliability
		1. Availability
		2. Mean Time Between Failures (MTBF)
		3. Mean Time To Repair (MTTR)
		4. Accuracy
		5. (Maximum) Bugs or Defect rate
	4. Performance
		1. Response Time
		2. Throughput
		3. Capacity
		4. Degradation modes
		5. Resource utilizations
	5. Supportability
	6. Design Constraints
	7. On-Line User Documentation and Help System Reqiurements
	8. Purchased Components
	9. Interfaces
		1. User Interfaces
		2. Hardware Interfaces
		3. Software Interfaces
		4. Communication Interfaces
	10. Licensing Reqiurements
	11. Legal, Copyright, and Other Notices
	12. Applicable Standards
4. Supporting Information

### 1. Introduction ###
Unser Ziel ist es, eine Smartphone-App zu entwickeln, welche einem die Dokumentation des persönlichen Trainings erleichtert.  
Unsere Vision: <a href="https://mumsfit.wordpress.com/2016/10/10/vision/">https://mumsfit.wordpress.com/2016/10/10/vision/</a>

1. **Purpose**  
Das SRS soll einen Überblick über die Anforderungen und Dokumente unseres Projektes bieten.
2. **Scope**  
Dieses Dokument dient zur internen Nutzung und soll als Richtlinie für die Entwicklung der Application gelten.
3. **Definitions, Acronyms, and Abbreviations**  
MuM = Max und Moritz  
n/a = not applicable  
tbd = to be determined 
4. **References**

| File                               | Link                                                                                                           |
|------------------------------------|----------------------------------------------------------------------------------------------------------------|
| Blog                               | https://mumsfit.wordpress.com/                                                                                 |
| GitHub                             | https://github.com/MH0896/MuM-s-Fit                                                                            |
| Use-Case Details ansehen           | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%201_Details%20ansehen.md             |
| Use-Case Trainingsplan löschen     | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%202Trainingsplan%20l%C3%B6schen.md   |
| Use-Case Trainingsplan erstellen   | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%203Trainingsplan%20erstellen.md      |
| Use-Case Trainingsplan ansehen     | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%204Trainingsplan%20ansehen.md        |
| Use-Case Trainingsplan bearbeiten  | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%205Trainingsplan%20bearbeeiten.md    |
| Use-Case Einstellungen ändern      | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%206Einstellungen%20%C3%A4ndern.md    |
| Use-Case Trainingsplan exportieren | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%207Trainingsplan%20exportieren.md    |
| Use-Case Trainingsplan importieren | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%208Trainingsplan%20importieren.md    |
| Use-Case Analyse ansehen           | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%209Analyse%20ansehen.md              |
| Use-Case Training durchführen      | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%2010Training%20durchf%C3%BChren.md   |
| Software Architecture Document     | https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Architecture%20Document.md                |
| Function Points                    | https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Complexity%20Adjustment%20Table.PNG |
| Risikomanagement                   | https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Riskiomanagement.md                                  |

### 2. Overall Description ###
Es handelt sich um eine Smartphone App, mit welcher ein Trainingsplan erstellt werden kann und das Training dokumentiert werden kann.
Dazu wird ein neuer Plan erstellt, über die Aufteilung des Trainings entschieden (beispielsweise ein sogenannter “2er-Split Plan” für z.B. Oberkörper und Unterkörper) und dann werden in jeden Plan die vorgesehenen Übungen eingetragen. Während des Trainings trägt man dann z.B. das erreichte Gewicht oder die gelaufene Distanz o.ä. ein, sodass am Ende anhand eines Diagramms der Fortschritt angezeigt werden kann.

1. **Product Perspective**  
Die App soll dem Benutzer die Organisation seines Trainings vereinfachen. Gleichzeitig kann man für andere Personen einen Plan erstellen und ihn diesen Schicken, beispielweise wenn man als erfahrener Sportler Neulingen den Einstieg erleichtern will.
2. **Product Functions**
	- Trainingsplan erstellen
	- Plan aufteilen ("Split")
	- Übungen hinzufügen
	- Fortschritt Dokumentieren
	- Fortschritt analysieren (Diagram)
	- Plan mit anderen Teilen (Im- und Export)
3. **User Characteristics**  
Der Nutzer sollte regelmäßig seinem Sport nachgehen, andernfalls macht eine Fortschrittsanalyse keinen Sinn. Weiterhin sollte der Nutzer in der Lage sein einen Trainingsplan selber zu erstellen, außer er nutzt die App weil er einen Plan von jemand anderen zugeschickt bekommen hat.
4. **Constraints**  
Sofern kein Plan zugeschickt oder Empfangen werden muss wird nichts weiter außer der App an sich benötigt. Die Speicherung der Daten erfolgt lokal auf dem eigenen Handy durch eine embedded Datenbank.  
Für das Senden bzw. Empfangen eines Plans werden eine Internetverbindung und ein E-Mail-Account benötigt.
5. **Assumptions and Dependencies**
	- IDE: Android Studio
	- Versionskontrolle: GitHub
	- Scrum: Jira
	- Programmiersprache: Java
	- Datenbank: SQLite
	- Tests: Cucumber (über Android Calabash), .feature-file Test  

### 3. Specific Requirements ###
1. **Funcionality**
	1. Overall Use-Case-Diagram  
GitHub: <a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Overall_UCD.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Overall_UCD.png</a>  
![Overall UCD](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Overall_UCD.png "Overall UCD")
	2. Startseiten Optionen  
Der User kann von dem Hauptbildschirm aus diese Aktionen ausführen:  

        Usecase Details ansehen:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%201_Details%20ansehen.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%201_Details%20ansehen.md</a>  

		Usecase Trainingsplan löschen:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%202_Trainingsplan%20l%C3%B6schen.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%202_Trainingsplan%20l%C3%B6schen.md</a>  

		Usecase Trainingsplan erstellen:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%203_Trainingsplan%20erstellen.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%203_Trainingsplan%20erstellen.md</a>

		Usecase Einstellungen ändern:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%206_Einstellungen%20%C3%A4ndern.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%206_Einstellungen%20%C3%A4ndern.md</a>

		Usecase Trainingsplan importieren:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%208_Trainingsplan%20importieren.md">hhttps://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%208_Trainingsplan%20importieren.md</a>
	3. Bearbeitungs-Optionen  
Weiterhin kann der User bei ausgewähltem (geöffneten) Trainingsplan folgende Aktionen ausführen:
 
		Usecase Trainingsplan ansehen:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%204_Trainingsplan%20ansehen.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%204_Trainingsplan%20ansehen.md</a>

		Usecase Trainunsplan bearbeiten:
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%205_Trainingsplan%20bearbeeiten.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%205_Trainingsplan%20bearbeeiten.md</a>

		Usecase Trainingsplan exportieren:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%207_Trainingsplan%20exportieren.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%207_Trainingsplan%20exportieren.md</a>

		Usecase Analyse ansehen:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%209_Analyse%20ansehen.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%209_Analyse%20ansehen.md</a>

		Usecase Training durchführen:  
		<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%2010_Training%20durchf%C3%BChren.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/MD-Files/Usecase%2010_Training%20durchf%C3%BChren.md</a>
	4. Beenden  
Diese Funktion ist ähnlich wie bei den meisten auf dem Markt verfügbaren Apps implementiert. Drückt man den „zurück-button“ auf seinem Handy, erscheint ein sog. „Toast“ (eine Art Pop-Up) mit der Info, dass man diese Taste erneut drücken soll um die App zu schließen. Dafür hat man 2 Sekunden Zeit. So wird ein versehentliches schließen der App verhindert.
2. **Usability**
	1. Training Time  
5 Minuten, um alle Funktionen einmal durchzuklicken und auszuprobieren. Die Funktionen sind selbsterklärend und bedürfen keiner weiteren Einweisung.
	2. Hardware Requirements  
Es wird nichts außer einem funktionierenden Smartphone benötigt.
	3. Software Requirements  
Auf dem Smartphone sollte eine möglichst aktuelle Version von Android installiert sein, das Minimum ist hierbei Android 5.0.
3. **Reliability**
	1. Availability  
Die App arbeitet mit einer embedded Datenbank und benötigt daher keine Internetverbindung o.ä. Dadurch muss die App rund um die Uhr verfügbar sein, solange das verwendete Gerät (in den meisten Fällen ein normales Smartphone) funktionsfähig ist.
	2. Mean Time Between Failures (MTBF)
n/a
	3. Mean Time To Repair (MTTR)  
n/a
	4. Accuracy  
n/a
	5. (Maximum) Bugs or Defect Rate  
n/a
4. **Performance**
	1. Response Time  
Start der Applikation: 2 Sekunden  
Reaktion auf Interaktionen: Im Normalfall sofort
	2. Throughput  
n/a
	3. Capacity
Die App ist für die Benutzung durch einen einzigen Nutzer ausgelegt
	4. Degrading modes  
n/a
	5. Resource utilization  
Momentan hat die App eine Größe von ~10 MB (auf den Testgeräten), wovon ca. 9MB für die App an sich benötigt werden. Die Gesamtgröße hängt logischerweise von der Menge von Trainingsplänen ab.
5. **Supportability**  
n/a
6. **Design Constraints**  
Es handelt sich um eine Android-Applikation  
Architektur, Klassendiagramm und Datenbankmodell können aus unserem „Software Architecture Document“ entnommen werden.
7. **On-Line User Documentation and Help System Requirements**  
Da die App und deren Funktionen selbsterklärend sind, wird auch keine Anleitung zur Verfügung stehen.
8. **Purchased Components**  
n/a
9. **Interfaces**
	1. User Interfaces  
		Screenshots:  
		<a href="https://github.com/MH0896/MuM-s-Fit/tree/master/Usecases/Screenshots">https://github.com/MH0896/MuM-s-Fit/tree/master/Usecases/Screenshots</a>

		Mock-Ups:  
		<a href="https://github.com/MH0896/MuM-s-Fit/tree/master/Usecases/Mock-ups">https://github.com/MH0896/MuM-s-Fit/tree/master/Usecases/Mock-ups</a>
	2. Hardware Interfaces  
n/a
	3. Software Interfaces  
n/a
	4. Communication Interfaces  
n/a
10. **Licensing Requirements**  
n/a
11. **Legal, Copyright and Other Notices**  
n/a
12. **Applicable Standarts**  
Code Conventions by Oracle

### 4. Supporting Information ###
n/a