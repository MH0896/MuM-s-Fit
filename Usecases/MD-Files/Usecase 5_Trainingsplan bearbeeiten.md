-------------
# MuM's Fit Use-Case Specification: Trainingsplan bearbeiten #
-------------
**MuM's Fit**  
**Use-Case Specification: Trainingsplan bearbeiten**

**Version 2.0**

## Revision History ##
<table>
<tr><td>Date</td><td>Version</td><td>Description</td><td>Author</td></tr>
<tr><td>10/12/2016</td><td>1.0</td><td>Dokument erstellt</td><td>MuM</td></tr>
<tr><td>12/12/2016</td><td>1.1</td><td>Screenshots, Mock-Ups und Features hinzugefügt</td><td>MuM</td></tr>
<tr><td>05/04/2017</td><td>2.0</td><td>Dateiformat zu .md geändert</td><td>MuM</td></tr>
</table>

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
n/a