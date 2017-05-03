-------------
# MuM's Fit Use-Case Specification: Trainingsplan bearbeiten #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan bearbeiten**

**Version 2.1**

## Revision History ##
 
|Date|Version|Description|Author|
|----|----|----|----|
|10/12/2016|1.0|Dokument erstellt|MuM|
|12/12/2016|1.1|Screenshots, Mock-Ups und Features hinzugefügt|MuM|
|05/04/2017|2.0|Dateiformat zu .md geändert|MuM|
|25.04.2017|2.1|Function Point Calculation added|MuM|
 

## Table of Contents ##
1. Use-Case Trainingsplan bearbeiten
	1. Brief Description
2. Overall Description
	1. Basic Flow
	2. Alternative Flows
		1. Änderung des Namens des Plans
	3. Mock-Ups
	4. Screenshots
	5. Features
3. Special Requirements
	1. Funcionality on Android
4. Preconditions
5. Postconditions
6. Extension Points
	1. Function Points

### 1. Use-Case Trainingsplan bearbeiten ###
1. **Brief Description**  
Dieser Use-Case ermöglicht es dem User, Änderungen an dem Pan vorzunehmen, wenn er sich bei der Erstellung zum Beispiel vertippt hat oder im Zuge des Trainings Änderungen vornehmen will.

	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20bearbeiten.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20bearbeiten.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20bearbeiten.png "Basic Flow")
2. **Alternative Flows**
	1. Änderung des Namens des Plans  
Soll der Name des Trainingsplans geändert werden und nicht die Inhalte (Übungen etc.), dann geht das nur über die Startseite indem man den Plan gedrückt hält und dann auf „Bearbeiten“ klickt
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20bearbeiten.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20bearbeiten.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20bearbeiten.png "Mock-Ups")
4. **Screenshots**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Bearbeiten_1-2.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Bearbeiten_1-2.png</a>  
![Screenshots 1-2](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Bearbeiten_1-2.png "Screenshots 1-2")

	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Bearbeiten_3-4.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Bearbeiten_3-4.png</a>  
	![Screenshots 3-4](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Bearbeiten_3-4.png "Screenshots 3-4")
5. **Features**  
<a href="https://github.com/MH0896/MuMsFit/blob/master/features/EditPlan.feature">https://github.com/MH0896/MuMsFit/blob/master/features/EditPlan.feature</a>

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein und es muss ein Trainingsplan vorhanden sein.

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **33,8**; Estimation = 9h   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20bearbeiten.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20bearbeiten.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20bearbeiten.PNG "FPs")  
 
|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|8|-|1|LOW|5|
|External Outputs|7|-|1|LOW|4|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|5|1|-|LOW|3|
|External Interface Files|0|0|-|LOW|0|
 