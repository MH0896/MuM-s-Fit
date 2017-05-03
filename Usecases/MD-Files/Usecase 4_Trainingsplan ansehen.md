-------------
# MuM's Fit Use-Case Specification: Trainingsplan ansehen #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan ansehen**

**Version 2.1**

## Revision History ##
 
|Date|Version|Description|Author|
|----|----|----|----|
|07/12/2016|1.0|Dokument erstellt|MuM|
|07/12/2016|1.1|Screenshots, Mock-Ups und Features hinzugefügt|MuM|
|05/04/2017|2.0|Dateiformat zu .md geändert|MuM|
|25.04.2017|2.1|Function Point Calculation added|MuM|
 

## Table of Contents ##
1. Use-Case Trainingsplan ansehen
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

### 1. Use-Case Trainingsplan ansehen ###
1. **Brief Description**  
Dieser Use-Case ermöglicht es dem User, den Trainingsplan anzusehen. So kann man sich die Splits und die Übungen ansehen und bei Bedarf bearbeiten (anderer Use-Case)

	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20ansehen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20ansehen.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20ansehen.png "Basic Flow")
2. **Alternative Flows**  
n/a
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20ansehen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20ansehen.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20ansehen.png "Mock-Ups")
4. **Screenshots**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Ansehen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Ansehen.png</a>  
![Screenshots](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Ansehen.png "Screenshots")
5. **Features**  
<a href="https://github.com/MH0896/MuMsFit/blob/master/features/ViewPlan.feature">https://github.com/MH0896/MuMsFit/blob/master/features/ViewPlan.feature</a>

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein und es muss ein Trainingsplan vorhanden sein.

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **23,4**; Estimation = 5h30m   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20ansehen.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20ansehen.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20ansehen.PNG "FPs")  
 
|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|1|-|2|LOW|3|
|External Outputs|5|-|2|AVG|4|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|5|1|-|LOW|4|
|External Interface Files|0|0|-|LOW|0|
 