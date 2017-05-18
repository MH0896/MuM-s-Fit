-------------
# MuM's Fit Use-Case Specification: Training durchführen #
-------------
**MuM's Fit**  
**Use-Case Specification: Training durchführen**

**Version 1.0**

## Revision History ##
 
|Date|Version|Description|Author|
|----|----|----|----|
|14/04/2017|1.0|Dokument erstellt|MuM|
|18/05/2017|1.1|Mock-ups und UCD hinzugefügt|MuM|
 

## Table of Contents ##
1. Use-Case Training durchführen
	1. Brief Description
2. Overall Description
	1. Basic Flow
	2. Alternative Flows
	4. Mock-Ups
	5. Screenshots
3. Special Requirements
	1. Funcionality on Android
4. Preconditions
5. Postconditions
6. Extension Points
	1. Function Points

### 1. Use-Case Training durchführen ###
1. **Brief Description**  
Dieser Usecase ermöglicht es dem Benutzer, das Training durchzuführen. Dabei wird die benötigte Zeit gemessen und der Nutzer kann eintragen, wie viel Gewicht er in den jeweiligen Übungen verwendet hat.
	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case:%20Training%20durchf%C3%BChren.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case:%20Training%20durchf%C3%BChren.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case:%20Training%20durchf%C3%BChren.png "Basic Flow")
2. **Alternative Flows**  
n/a
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup:%20Trainingsplan%20durchf%C3%BChren.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup:%20Trainingsplan%20durchf%C3%BChren.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup:%20Trainingsplan%20durchf%C3%BChren.png "Mock-Ups")
4. **Screenshots**  
<a href="TODO">TODO</a>  
![Screenshots](TODO "Screenshots")

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein und es muss ein Trainingsplan vorhanden sein.

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **54,29**; Estimation = 13h   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20durchf%C3%BChren.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20durchf%C3%BChren.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20durchf%C3%BChren.PNG "FPs")  
 
|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|6|-|2|AVG|4|
|External Outputs|3|-|1|LOW|2|
|External Inqueries|3|-|2|LOW|3|
|Internal Logical Files|5|3|-|LOW|4|
|External Interface Files|0|0|-|LOW|0|