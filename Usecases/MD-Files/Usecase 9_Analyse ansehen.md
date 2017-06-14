-------------
# MuM's Fit Use-Case Specification: Analyse ansehen #
-------------
**MuM's Fit**  
**Use-Case Specification: Analyse ansehen**

**Version 1.2**

## Revision History ##
 
|Date|Version|Description|Author|
|----|----|----|----|
|14/04/2017|1.0|Dokument erstellt|MuM|
|18/04/2017|1.1|Mock-ups und UCD hinzugefügt|MuM|
|25.04.2017|1.2|Function Point Calculation added|MuM|
|14.06.2017|1.3|Screenshots hinzugefügt|MuM|
 

## Table of Contents ##
1. Use-Case Analyse ansehen
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

### 1. Use-Case Analyse ansehen ###
1. **Brief Description**  
Dieser Usecase ermöglicht es dem Benutzer, die Analyse seines Trainings anzusehen, in welche beispielsweise die Kraftsetigerung oder Ähnliches angezeigt wird.
	Link zum SRS:   
	<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md</a>

### 2. Flow of Events ###
1. **Basic Flow**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Analyse%20ansehen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Analyse%20ansehen.png</a>  
![Basic Flow](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Use%20Case-%20Analyse%20ansehen.png "Basic Flow")
2. **Alternative Flows**  
n/a
3. **Mock-Ups**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Analyse%20anzeigen.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Analyse%20anzeigen.png</a>  
![Mock-Ups](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Mock-ups/Mockup-%20Analyse%20anzeigen.png "Mock-Ups")
4. **Screenshots**  
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Analysieren.png">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Analysieren.png</a>  
![Screenshots](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Screenshots/UC_Analysieren.png "Screenshots")

### 3. Special Requirements ###
1. **Functionality on Android**  
Die App wird vorerst nur für Android programmiert und muss daher für die gängigen Bildschirmgrößen optimiert sein. Es wird davon ausgegangen, dass die wenigsten mit einem großen Tablet zum Training gehen, daher liegt der Fokus auf kleineren Bildschirmen.

### 4. Preconditions ###
Die App muss gestartet sein, es muss ein Trainingsplan vorhanden sein und dieser muss mindestens ein mal durchgeführt worden sein, um erste Informationen zur Verfügung zu haben. Für Punkte wie Kraftzuwachs o.ä. muss ein Trainingsplan mehrmals durchlaufen sein.

### 5. Postconditions ###
n/a

### 6. Extension Points ###
1. Function points = **37,05**; Estimation = 9h20m   
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Analyse%20ansehen.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Analyse%20ansehen.PNG</a>  
![FPs](https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/Function%20Points/Analyse%20ansehen.PNG "FPs")  
 
|Transaction Data / Functionality|DET|RET|FTR|Complexity|Count|
|----|----|----|----|----|----|
|External Inputs|4|-|2|LOW|3|
|External Outputs|6|-|2|AVG|4|
|External Inqueries|0|-|0|LOW|0|
|Internal Logical Files|6|2|-|LOW|4|
|External Interface Files|0|0|-|LOW|0|
 