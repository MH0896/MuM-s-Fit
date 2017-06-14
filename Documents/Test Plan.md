-------------
# MuM's Fit Master Test Plan #
-------------
**MuM's Fit**  
**Master Test Plan**

**Version 1.5**

## Revision History ##

|Date|Version|Description|Author|
|---|---|---|---|
|26/04/2017|1.0|Dokument erstellt|MuM|
|18/05/2017|1.1|Dokument mit allen vorhandenen Informationen gefüllt|MuM|
|18/05/2017|1.2|Formatierungsfehler gefixt|MuM|
|31/05/2017|1.3|Weiteren Inhalt hinzugefügt|MuM|
|12/06/2017|1.4|Monkey-Stresstest hinzugefügt|MuM|
|14/06/2017|1.5|Installationstest hinzugefügt|MuM|


## Table of Contents ##
1. Introduction
	1. Purpose
	2. Scope
	3. Intended Audience
	4. Document Teminology and Acronyms
	5. References
	6. Document Structure
2. Evaluation Mission and test Motivation
	1. Background
	2. Evaluation Mission
	3. Test Motivators
3. Target test Items
4. Outline of Planned Tests
	1. Outline of Test Inclusions
	2. Outline of other candidates for potential inclusion
	3. Outline of Test Exclusions
5. Test Approach
	1. Initial Test-Idea Catalogs and other reference sources
	2. Testing Techniques and Types
		1. Function Testing
		2. User Interface Testing
		3. Stress Testing
		4. Installation Testing
6. Entry and Exit Criteria
	1. Test Plan
		1. Test Plan Entry Criteria
		2. Test Plan Exit Criteria
		3. Suspension and resumption criteria
	2. Test Cycles
7. Deliverables
	1. Test Evaluation Summaries 
	2. Reporting on Test Coverage
	3. Perceived Quality Reports
	4. Incident Logs and Change Requests
	5. Smoke Test Suite and supporting Test Scripts
	6. Additional work products
8. Testing Workflow
9. Environmental Needs
	1. Base System Hardware
	2. Base Software Elements in the Test Environment
	3. Productivity and Support Tools
	4. Test Environment Configurations
10. Responsibilities, Staffing and Training Needs
	1. People and Roles
	2. Staffing and Training Needs
11. Iteration Milestones
12. Risks, Dependencies, Assumptions and Constraints
13. Management Process and Procedures
	1. Measuring and Assessing the Extent of Testing
	2. Assessing the deliverables of this Test Plan
	3. Problem Reporting, Escalation and Issue Resolution
	4. Managing Test Cycles
	5. Traceability Strategies
	6. Approval and Signoff

## 1. Introduction ##
1. **Purpose**  
Ziel dieses Testplans ist es, alle für die Planung und Kontrolle des Tests nötigen Informationen zu bekommen und zu dokumentieren.  
Der Test Plan soll das Erreichen der folgenden Ziele sicherstellen:  
	- Die Tests sind auf Funktionalität und interface der App abgestimmt.
	- Die Applikation soll so wenig wie möglich bzw. im Idealfall gar keine Fehler mehr enthalten.  
2. **Scope**  
Dieses Dokument geht auf die folgenden typen und level von tests ein:
	- JUnit Tests
	- Funktions-Tests
3. **Intended Audience**  
Mitglieder des Projektteams und Entwickler
4. **Document Terminology and Acronyms**  
MuM = Max und Moritz  
n/a = not applicable  
tbd = to be determined
5. **References**  

|Objekt|Link|
|---|---|
|SAD|https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Architecture%20Document.md|
|SRS|https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md|
|Codacy|https://www.codacy.com/app/MH0896/MuMsFit/dashboard|
6. **Document Structure**  
n/a

## 2. Evaluation Mission and Test Motivation ##
1. **Background**  
Tests geben beiden Teammitgliedern ein Feedback über ihre Arbeit. Es wird sichergestellt, dass die Usecases entsprechend ihrer Festlegung implementiert sind und dass Änderungen keine negativen Auswirkungen auf die App haben.
2. **Evaluation Mission**  
Hauptziel ist es, den Quellcode der Applikation und das Desig unserer App zu optimieren. Daher wird versucht, so viele Fehler als möglich zu finden und zu beheben, mögliche Engpässe auszumachen, usw.
3. **Test Motivators**  
Tests reduzieren Fehler in sowohl bereits existierenden Features als auch in neuen Features. Außerdem sind Tests eine gute möglichkeit der Dokumentation.

## 3. Target Test Items ##
- Android-Applikation "MuM's Fit"

## 4. Outline of Planned Tests ##
1. **Outline of Test Inclusions**  
	- Unit-tests
	- Funktions-tests
	- Installations-tests
2. **Outline of other candidates for potential inclusion**  
	- Datenbank-tests
	- Stresstests
3. **Outline of Test Exclusions**  
	- Datenbank an sich

## 5. Test Approach ##
1. **Initial Test-Idea Catalogs and other reference sources**  
n/a
2. **Testing Techniques and Types**  
	1. Function Testing

	| | |
	|----|----|
	|Technique Objective|Testen des Ablaufs der App, inklusive Dateneingabe und -verarbeitung|
	|Technique|Es muss sichergestellt werden, dass bei nutzen korrekter Daten das entsprechende Ergebnis stattfindet und bei nutzen falscher Daten eine entsprechende Fehlermeldung erscheint|
	|Oracles|Tests sind erfolgreich, wenn jede Interaktion das gewünschte Ergebnis bringt|
	|Required Tools|JUnit|
	|Success Criteria|Alle Tests laufen erfolgreich durch|
	|Special Considerations|n/a|  

	2. User Interface Testing  

	| | |
	|----|----|
	|Technique Objective|Testen aller Ansichten auf korrektes Verhalten|
	|Technique|Für jede Ansicht einen Test erstellen um die korrekte Darstellung und Navigation sicherzustellen|
	|Oracles|Tests sind erfolgreich, wenn jede Interaktion mit der GUI das gewünschte Ergebnis bringt|
	|Required Tools|Calabash|
	|Success Criteria|Alle Tests laufen erfolgreich durch|
	|Special Considerations|n/a|  

	3. Stress Testing  
	
	| | |
	|----|----|
	|Technique Objective|Stresstest der Applikation|
	|Technique|Stresstest|
	|Oracles|n/a|
	|Required Tools|Monkey, Android Device or Emulator|
	|Success Criteria|Die Applikation stürzt nicht ab und friert nicht ein|
	|Special Considerations|n/a|  

	4. Installation Testing  
	
	| | |
	|----|----|
	|Technique Objective|Testen, ob die App korrekt installiert werden kann|
	|Technique|Es wird die Apk zur verfügung gestellt mitsamt einer Anleitung zur Installation. Anschießend muss ein Dokument ausgefüllt werden|
	|Oracles|Tests sind erfolgreich, wenn die Installation nicht fehlschlägt und die App keine Fehler aufweist|
	|Required Tools|Android Smartphone|
	|Success Criteria|Die App wird erfolgreich installiert und es wird eine Datenbank angelegt (man kann Trainingspläne erstellen, bearbeiten, ...)|
	|Special Considerations|n/a|  

	Installationstest-Dokument: https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Installationstest%20Dokumentation.pdf

	Installationstest ausgefüllt von "SmartEvent": https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Installationstest%20Dokumentation_SmartEvent-Fabian.pdf

## 6. Entry and Exit Criteria ##
1. **Test Plan**
	1. Test Plan Entry Criteria  
Bei jedem Deploy werden FUnktionstests automatisch ausgeführt. Stresstests oder Installations-tests werden manuell durchgeführt.
	2. Test Plan Exit Criteria  
Der Testplan ist beendet, sobald alle Tests erfolgreich durchgeführt wurden. Ausgenommen davon sind ggf. die manuellen Tests, je nach Umfang. 
	3. Suspension and resumption criteria  
Der Testplan kann nicht abgebrochen werden!  
2. **Test Cycles**  
n/a  

## 7. Deliverables ##
1. **Test Evaluation Summaries**  
Eine Zusammenfassung unserer Tests ist immer aktuell in Travis:  
https://travis-ci.org/MH0896/MuMsFit/  
Diese wird automatisch mit jedem Push auf den Master-branch erstellt.
2. **Reporting on Test Coverage**  
Unsere Testcoverage ist in unserem Git-Hub badge zu sehen, oder in folgendem Dokument: https://github.com/MH0896/MuMsFit/blob/master/Test-Coverage/index.html
3. **Perceived Quality Reports**  
	- Codacy: https://www.codacy.com/app/MH0896/MuMsFit/dashboard
4. **Incident Logs and Change Requests**  
n/a
5. **Smoke Test Suite and supporting Test Scripts**  
n/a
6. **Additional work products**  
n/a  

## 8. Testing Workflow ##
Unit Tests starten automatisch. Funktionstest oder end-nutzer-tests werden manuell, wenn als nötig erachtet, gestartet, ebenso wie Stresstests.

## 9. Environmental Needs ##
1. **Base System Hardware**  
Android Smartphone mit minimum-SKD: 21. Das entspricht Android Version 5.0.  
2. **Base Software Elements in the Test Environment**  

|Software Element|Version|Typ / andere Notizen|
|----|----|----|
|Windows|10|Entwicklungsumgebung und Programmausführung|
|Google Chrome|58.X.X|Einsicht der Testergebnisse|
|JDK|8 Update 111|Programmiersprache|

3. **Productivity and Support Tools**  

|Kategorie|Name|Version|
|----|----|----|
|Metrics|Codacy|n/a|
|Test|JUnit|4.12|
|IDE|Android Studio|2.3.2|
|Projektmanagement|JIRA|7.0.0|

4. **Test Environment Configurations**  
n/a

## 10. Responsibilities, Staffing and Training Needs ##
1. **People and Roles**  
Zu finden in unserem Blog-Eintrag: <a href="https://mumsfit.wordpress.com/2016/10/13/rup-terminology/">RUP terminology</a>
2. **Staffing and Training Needs**  
n/a

## 11. Iteration Milestones ##

|Geplanter Meilenstein|Startdatum|Enddatum|
|----|----|----|
|~30% Codecoverage|Projectstart|31.05.2017|
|50%+ Codecoverage|01.06.2017|21.06.2017|
## 12. Risks, Dependencies, Assumptions and Constraints ##
Eine Übersicht über unser gesamtes Risikomanagement findet sich <a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Riskiomanagement.md">dieser Datei</a>


## 13. Management Process and Procedures ##
1. **Measuring and Assessing the Extent of Testing**  
n/a
2. **Assessing the deliverables of this Test Plan**  
n/a
3. **Problem Reporting, Escalation and Issue Resolution**  
n/a
4. **Managing Test Cycles**  
n/a
5. **Traceability Strategies**  
n/a
6. **Approval and Signoff**  
n/a

## 14. Metrics ##
Wir verwenden Codacy.  
Das Dashboard mit allen Informationen über unseren Quellcode und aktuell bestehende Fehler findet sich hier: <a href="https://www.codacy.com/app/MH0896/MuMsFit/dashboard">Codacy Dashboard</a>  
Dies ist immer unser aktuellster Commit, d.h. jegliche Fehler die dort angezeigt werden sind entweder nach wie vor vorhanden oder aktuell in Bearbeitung. 