-------------
# MuM's Fit Use-Case Specification: Details ansehen #
-------------
**MuM's Fit**  
**Use-Case Specification: Details ansehen**

**Version 2.1**

## Revision History ##
|Date|Version|Description|Author|
|----|----|----|----|
|20/10/2016|1.0|Dokument erstellt|MuM
|01/11/2016|1.1|Mockup hinzugefügt|MuM|
|10/11/2016|1.2|UCD korrigiert (korrektes UML format)|MuM|
|23/11/2016|1.4|Screenshots und features hinzugefügt|MuM|
|23/11/2016|1.5|UCD korrigiert / erweitert|MuM|
|05/04/2017|2.0|Dateiformat zu .md geändert|MuM|
|25.04.2017|2.1|Function Point Calculation added|MuM|

## Table of Contents ##
1. Use-Case Details ansehen
	1. Brief Description
2. Overall Description
	1. Basic Flow
	2. Alternative Flows
		1. Schließen des Detailfensters
	4. Mock-Ups
	5. Screenshots
	6. Features
3. Special Requirements
	1. Funcionality on Android
4. Preconditions
5. Postconditions
6. Extension Points
	1. Function Points

### 1. Use-Case Details ansehen ###
1. **Brief Description**  
Dieser Usecase ermöglicht es dem Benutzer auf genauere Informationen eines bestimmten Trainingsplans zuzugreifen. Diese Informationen sind: Name des Plans, letztes durchgeführtes Training, Erstelldatum und die Anzahl der Ausführungen.

	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Details%20ansehen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Details%20ansehen.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Details%20ansehen.png "Basic Flow")
2. **Alternative Flows**
	1. Schließen des Detailfensters  
Der Benutzer kann das Detailfenster auch schließen, in dem er nicht auf den zurück-Button drückt, sondern neben das Detailfenster drückt.
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Details%20anzeigen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Details%20anzeigen.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Details%20anzeigen.png "Mock-Ups")
4. **Screenshots**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Ansehen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Ansehen.png</a>  
![Screenshots](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Ansehen.png "Screenshots")
5. **Features**  
<a href="https://github.com/MH0896/MuMsFit/blob/master/features/ViewDetails.feature">https://github.com/MH0896/MuMsFit/blob/master/features/ViewDetails.feature</a>

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein und es muss ein Trainingsplan vorhanden sein

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **25,35**; Estimation = 6h30m   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Details%20ansehen.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Details%20ansehen.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Details%20ansehen.PNG "FPs")  

|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|2|-|1|LOW|2|
|External Outputs|4|-|1|LOW|3|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|4|1|-|LOW|>3|
|External Interface Files|0|0|-|LOW|0|