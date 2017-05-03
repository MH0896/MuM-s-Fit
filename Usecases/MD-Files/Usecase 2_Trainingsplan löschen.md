-------------
# MuM's Fit Use-Case Specification: Trainingsplan löschen #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan löschen**

**Version 2.1**

## Revision History ##
|Date|Version|Description|Author|
|31/10/2016|1.0|Dokument erstellt|MuM|
|01/11/2016|1.1|Mockup hinzugefügt|MuM|
|10/11/2016|1.2|UCD korrigiert (korrektes UML format)|MuM|
|15/11/2016|1.3|Features hinzugefügt|MuM|
|23/11/2016|1.4|Screenshots hinzugefügt|MuM|
|23/11/2016|1.5|UCD korrigiert / erweitert|MuM|
|05/04/2017|2.0|Dateiformat zu .md geändert|MuM|
|25.04.2017|2.1|Function Point Calculation added|MuM|

## Table of Contents ##
1. Use-Case Trainingsplan löschen
	1. Brief Description
2. Overall Description
	1. Basic Flow
	2. Alternative Flows
	3. Mock-Ups
	4. Screenshots
	5. Features
3. Special Requirements
	1. Funcionality on Android
4. Preconditions
5. Postconditions
6. Extension Points
	1. Function Points

### 1. Use-Case Trainingsplan löschen ###
1. **Brief Description**  
Dieser Use-Case ermöglicht es dem Benutzer einen oder mehrere ausgewählte Trainingspläne dauerhaft zu löschen. Das Löschen kann nicht rückgängig gemacht werden. 

	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20l%C3%B6schen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20l%C3%B6schen.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20l%C3%B6schen.png "Basic Flow")
2. **Alternative Flows**  
n/a
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20L%C3%B6schen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20L%C3%B6schen.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20L%C3%B6schen.png "Mock-Ups")
4. **Screenshots**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_L%C3%B6schen_1-2.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_L%C3%B6schen_1-2.png</a>  
![Screenshots 1-2](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_L%C3%B6schen_1-2.png "Screenshots 1-2")

	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_L%C3%B6schen_3-4.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_L%C3%B6schen_3-4.png</a>  
	![Screenshots 3-4](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_L%C3%B6schen_3-4.png "Screenshots 3-4")
5. **Features**  
<a href="https://github.com/MH0896/MuMsFit/blob/master/features/DeletePlan.feature">https://github.com/MH0896/MuMsFit/blob/master/features/DeletePlan.feature</a>

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein und es muss ein Trainingsplan vorhanden sein

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **28,6**; Estimation = 6h20m  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20l%C3%B6schen.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20l%C3%B6schen.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20l%C3%B6schen.PNG "FPs")  

|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|External Inputs|3|-|2|LOW|3|
|External Outputs|0|-|0|LOW|0|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|8|2|-|LOW|5|
|External Interface Files|0|0|-|LOW|0|
  