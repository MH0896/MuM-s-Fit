-------------
# MuM's Fit Use-Case Specification: Trainingsplan ansehen #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan ansehen**

**Version 2.1**

## Revision History ##
<table>
<tr><td>Date</td><td>Version</td><td>Description</td><td>Author</td></tr>
<tr><td>07/12/2016</td><td>1.0</td><td>Dokument erstellt</td><td>MuM</td></tr>
<tr><td>07/12/2016</td><td>1.1</td><td>Screenshots, Mock-Ups und Features hinzugefügt</td><td>MuM</td></tr>
<tr><td>05/04/2017</td><td>2.0</td><td>Dateiformat zu .md geändert</td><td>MuM</td></tr>
<tr><td>25.04.2017</td><td>2.1</td><td>Function Point Calculation added</td><td>MuM</td></tr>
</table>

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
<table>
<tr><td>Transaction Data / Functionality</td><td>DET</td><td>RET</td><td>FTR</td><td>Complexity</td><td>Count</td></tr>
<tr><td>External Inputs</td><td>1</td><td>-</td><td>2</td><td>LOW</td><td>3</td></tr>
<tr><td>External Outputs</td><td>5</td><td>-</td><td>2</td><td>AVG</td><td>4</td></tr>
<tr><td>External Inqueries</td><td>0</td><td>-</td><td>0</td><td>LOW</td><td>0</td></tr>
<tr><td>Internal Logical Files</td><td>5</td><td>1</td><td>-</td><td>LOW</td><td>4</td></tr>
<tr><td>External Interface Files</td><td>0</td><td>0</td><td>-</td><td>LOW</td><td>0</td></tr>
</table>