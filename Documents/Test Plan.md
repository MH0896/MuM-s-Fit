-------------
# MuM's Fit Master Test Plan #
-------------
**MuM's Fit**  
**Master Test Plan**

**Version 1.0**

## Revision History ##

|Date|Version|Description|Author|
|---|---|---|---|
|26/04/2017|1.0|Dokument erstellt|MuM|
|18/05/2017|1.1|Dokument mit allen vorhandenen Informationen gefüllt|MuM|


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
		1. Data and Database Integrity Testing
		2. Function Testing
		3. Business Cycle Testing
		4. User Interface Testing
		5. Performance Profiling
		6. Load Testing
		7. Stress Testing
		8. Volume Testing
		9. Security and Access Control Testing
		10. Failover and Recovery Testing
		11. Configuration Testing
		12. Installation Testing
6. Entry and Exit Criteria
	1. Test Plan
		1. Test Plan Entry Criteria
		2. Test Plan Exit Criteria
		3. Suspension and resumption criteria
	2. Test Cycles
		1. Test Cycle Entry Criteria
		2. Test Cycle Exit Criteria
		3. Test Cycle abnormal termination
7. Deliverables
	1. Test Evaluation Summaries 
	2. Reporting on Test Coverage
	3. Perceived Quality Reports
	4. Incident Logs and Change Requests
	5. Smoke Test Suite and supporting Test Scripts
	6. Additional work products
		1. Detailed Test Results
		2. Additional automated functional Test Scripts
		3. Test Guidelines
		4. Traceability Matrices
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
n/a
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
Tests geben beiden Teammitgliedern ein Feedback über ihre arbeit. Es wird sichergestellt, dass die Usecases entsprechend ihrer Festlegung implementiert sind und dass änderungen keine negativen Auswirkungen auf die App haben.
2. **Evaluation Mission**  
Hauptziel ist es, den Quellcode der Applikation und das Desig unserer App zu optimieren. Daher wird versucht, so viele Fehler als möglich zu finden und zu beheben, mögliche Engpässe auszumachen usw.
3. **Test Motivators**  
Tests reduzieren Fehler in sowohl bereits existierenden Features als auch in neuen Features. Außerdem sind Tests eine gute möglichkeit der Dokumentation.

## 3. Target Test Items ##
- Android-Applikation "MuM's Fit"

## 4. Outline of Planned Tests ##
1. **Outline of Test Inclusions**  
	- Unit-tests
	- Funktions-tests
2. **Outline of other candidates for potential inclusion**  
	- Datenbank-tests
3. **Outline of Test Exclusions**  
n/a

## 5. Test Approach ##
1. **Initial Test-Idea Catalogs and other reference sources**  
n/a
2. **Testing Techniques and Types**  
	1. Data and Database Integrity Testing
tbd
	2. Function Testing

| | |
|----|----|
|Technique Objective|Testen des Ablaufs der App, inklusive Dateneingabe und -verarbeitung|
|Technique|Es muss sichergestellt werden, dass:  
<br>- bei nutzen korrekter Daten das entsprechende Ergebnis stattfindet  
<br>- bei nutzen falscher Daten eine entsprechende Fehlermeldung erscheint|
|Oracles|Tests sind erfolgreich, wenn jede Interaktion das gewünschte Ergebnis bringt|
|Required Tools|JUnit|
|Success Criteria|Alle Tests laufen erfolgreich durch|
|Special Considerations|n/a|   
	3. Business Cycle Testing
n/a
	4. User Interface Testing  
| | |
|----|----|
|Technique Objective|Testen aller Ansichten auf korrektes Verhalten|
|Technique|Für jede Ansicht einen Test erstellen um die korrekte Darstellung und Navigation sicherzustellen|
|Oracles|Tests sind erfolgreich, wenn jede Interaktion mit der GUI das gewünschte Ergebnis bringt|
|Required Tools|Calabash|
|Success Criteria|Alle Tests laufen erfolgreich durch|
|Special Considerations|n/a|   
		5. Performance Profiling
n/a
		6. Load Testing
n/a
		7. Stress Testing
n/a
		8. Volume Testing
n/a
		9. Security and Access Control Testing
n/a
		10. Failover and Recovery Testing
n/a
		11. Configuration Testing
n/a
		12. Installation Testing
n/a

## 6. Entry and Exit Criteria ##
1. **Test Plan**
	1. Test Plan Entry Criteria
n/a
	2. Test Plan Exit Criteria
n/a
	3. Suspension and resumption criteria
n/a
2. **Test Cycles**  
	1. Test Cycle Entry Criteria
n/a
	2. Test Cycle Exit Criteria
n/a
	3. Test Cycle abnormal termination
n/a

## 7. Deliverables ##
1. **Test Evaluation Summaries**  
tbd
2. **Reporting on Test Coverage**  
	- Codacy: https://www.codacy.com/app/MH0896/MuMsFit/dashboard
3. **Perceived Quality Reports**  
	- Codacy: https://www.codacy.com/app/MH0896/MuMsFit/dashboard
4. **Incident Logs and Change Requests**  
n/a
5. **Smoke Test Suite and supporting Test Scripts**  
n/a
6. **Additional work products**  
	1. Detailed Test Results
n/a
	2. Additional automated functional Test Scripts
n/a
	3. Test Guidelines
n/a
	4. Traceability Matrices
n/a

## 8. Testing Workflow ##
Unit Tests starten automatisch. Funktionstest oder end-nutzer-tests werden manuell wenn als nötig erachtet getsartet.

## 9. Environmental Needs ##
1. **Base System Hardware**  
tbd
2. **Base Software Elements in the Test Environment**  
tbd
3. **Productivity and Support Tools**  
tbd
4. **Test Environment Configurations**  
tbd

## 10. Responsibilities, Staffing and Training Needs ##
1. **People and Roles**  
Zu finden in unserem Blog-Eintrag: <a href="https://mumsfit.wordpress.com/2016/10/13/rup-terminology/">RUP terminology</a>
2. **Staffing and Training Needs**  
n/a

## 11. Iteration Milestones ##
n/a
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