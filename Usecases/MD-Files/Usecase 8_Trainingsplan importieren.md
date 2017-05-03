-------------
# MuM's Fit Use-Case Specification: Trainingsplan importieren #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan importieren**

**Version 1.2**

## Revision History ##
 
|Date|Version|Description|Author|
|----|----|----|----|
|14/04/2017|1.0|Dokument erstellt|MuM|
|18/04/2017|1.1|Mock-ups und UCD hinzugefügt|MuM|
|25.04.2017|1.2|Function Point Calculation added|MuM|
 

## Table of Contents ##
1. Use-Case Trainingsplan importieren
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

### 1. Use-Case Trainingsplan importieren ###
1. **Brief Description**  
Dieser Usecase ermöglicht es dem Benutzer, einen anderen Trainingsplan, den z.B. sein Trainer erstellt haben könnte, zu importieren.
	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20importieren.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20importieren.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Trainingsplan%20importieren.png "Basic Flow")
2. **Alternative Flows**  
n/a
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20Importieren.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20Importieren.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Trainingsplan%20Importieren.png "Mock-Ups")
4. **Screenshots**  
<a href="TODO">TODO</a>  
![Screenshots](TODO "Screenshots")

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein.

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **31,2**; Estimation = 7h35m   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20importieren.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20importieren.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/TP%20importieren.PNG "FPs")  
 
|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|3|-|2|LOW|3|
|External Outputs|1|-|1|LOW|1|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|8|2|-|LOW|5|
|External Interface Files|0|0|-|LOW|0|
 