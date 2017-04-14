-------------
# MuM's Fit Use-Case Specification: Trainingsplan löschen #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan löschen**

**Version 2.0**

## Revision History ##
<table>
<tr><td>Date</td><td>Version</td><td>Description</td><td>Author</td></tr>
<tr><td>31/10/2016</td><td>1.0</td><td>Dokument erstellt</td><td>MuM</td></tr>
<tr><td>01/11/2016</td><td>1.1</td><td>Mockup hinzugefügt</td><td>MuM</td></tr>
<tr><td>10/11/2016</td><td>1.2</td><td>UCD korrigiert (korrektes UML format)</td><td>MuM</td></tr>
<tr><td>15/11/2016</td><td>1.3</td><td>Features hinzugefügt</td><td>MuM</td></tr>
<tr><td>23/11/2016</td><td>1.4</td><td>Screenshots hinzugefügt</td><td>MuM</td></tr>
<tr><td>23/11/2016</td><td>1.5</td><td>UCD korrigiert / erweitert</td><td>MuM</td></tr>
<tr><td>05/04/2017</td><td>2.0</td><td>Dateiformat zu .md geändert</td><td>MuM</td></tr>
</table>

## Table of Contents ##
1. Use-Case Details ansehen
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
n/a