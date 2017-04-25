-------------
# MuM's Fit Use-Case Specification: Analyse ansehen #
-------------
**MuM's Fit**  
**Use-Case Specification: Analyse ansehen**

**Version 1.2**

## Revision History ##
<table>
<tr><td>Date</td><td>Version</td><td>Description</td><td>Author</td></tr>
<tr><td>14/04/2017</td><td>1.0</td><td>Dokument erstellt</td><td>MuM</td></tr>
<tr><td>18/04/2017</td><td>1.1</td><td>Mock-ups und UCD hinzugefügt</td><td>MuM</td></tr>
<tr><td>25.04.2017</td><td>1.2</td><td>Function Point Calculation added</td><td>MuM</td></tr>
</table>

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
<a href="TODO">TODO</a>  
![Screenshots](TODO "Screenshots")

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
<table>
<tr><td>Transaction Data / Functionality</td><td>DET</td><td>RET</td><td>FTR</td><td>Complexity</td><td>Count</td></tr>
<tr><td>External Inputs</td><td>4</td><td>-</td><td>2</td><td>LOW</td><td>3</td></tr>
<tr><td>External Outputs</td><td>6</td><td>-</td><td>2</td><td>AVG</td><td>4</td></tr>
<tr><td>External Inqueries</td><td>0</td><td>-</td><td>0</td><td>LOW</td><td>0</td></tr>
<tr><td>Internal Logical Files</td><td>6</td><td>2</td><td>-</td><td>LOW</td><td>4</td></tr>
<tr><td>External Interface Files</td><td>0</td><td>0</td><td>-</td><td>LOW</td><td>0</td></tr>
</table>