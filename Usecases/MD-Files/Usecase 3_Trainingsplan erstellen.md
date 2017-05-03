-------------
# MuM's Fit Use-Case Specification: Trainingsplan erstellen #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan erstellen**

**Version 2.1**

## Revision History ##
 
|Date|Version|Description|Author|
|----|----|----|----|
|14/11/2016|1.0|Dokument erstellt|MuM|
|14/11/2016|1.1|Alternative flow „Doppelte Namensgebung“ hinzugefügt|MuM|
|15/11/2016|1.3|Features hinzugefügt|MuM|
|21/11/2016|1.4|Screenshots hinzugefügt|MuM|
|23/11/2016|1.5|UCD korrigiert / erweitert|MuM|
|05/04/2017|2.0|Dateiformat zu .md geändert|MuM|
|25.04.2017|2.1|Function Point Calculation added|MuM|
 

## Table of Contents ##
1. Use-Case Trainingsplan erstellen
	1. Brief Description
2. Overall Description
	1. Basic Flow
	2. Alternative Flows
		1. Doppelte Namensgebung
	3. Mock-Ups
	4. Screenshots
	5. Features
3. Special Requirements
	1. Funcionality on Android
4. Preconditions
5. Postconditions
6. Extension Points
	1. Function Points

### 1. Use-Case Trainingsplan erstellen ###
1. **Brief Description**  
Dieser Usecase ermöglicht es dem Benutzer, einen neuen Plan anzulegen, zu benennen und abzuspeichern. Diesem Plan können danach nach Belieben sogenannte „splits“ (z.B. Aufteilung in Ober- und Unterkörper) und Übungen hinzugefügt werden. 

	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20erstellen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20erstellen.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20erstellen.png "Basic Flow")
2. **Alternative Flows**
	1. Doppelte Namensgebung  
Wen ein neuer Plan genau so benannt wird wie ein bereits bestehender Plan, schließt sich das Fenster mit der Meldung, bitte einen anderen Namen auszuwählen.
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20Erstellen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20Erstellen.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20Erstellen.png "Mock-Ups")
4. **Screenshots**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_1-3.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_1-3.png</a>  
![Screenshots 1-3](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_1-3.png "Screenshots 1-3")

	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_4-6.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_4-6.png</a>  
	![Screenshots 4-6](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_4-6.png "Screenshots 4-6")

	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_7-9.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_7-9.png</a>  
	![Screenshots 7-9](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Create%20Plan_7-9.png "Screenshots 7-9")
5. **Features**  
<a href="https://github.com/MH0896/MuMsFit/blob/master/features/CreateTrainingPlan.feature">https://github.com/MH0896/MuMsFit/blob/master/features/CreateTrainingPlan.feature</a>

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein.

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **48,75**; Estimation = 12h   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20anlegen.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20anlegen.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20anlegen.PNG "FPs")  
 
|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|11|-|2|AVG|7|
|External Outputs|4|-|1|LOW|3|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|8|2|-|LOW|5|
|External Interface Files|0|0|-|LOW|0|
 