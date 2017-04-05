-------------
# MuM's Fit Software Architecture Document #
-------------
**MuM's Fit**  
**Software Architecture Document**

**Version 2.0**

## Revision History ##
<table>
<tr><td>Date</td><td>Version</td><td>Description</td><td>Author</td></tr>
<tr><td>21/11/2016</td><td>1.0</td><td>Dokument erstellt</td><td>MuM</td></tr>
<tr><td>24/11/2016</td><td>1.1</td><td>Klassendiagramm Aktualisiert</td><td>MuM</td></tr>
<tr><td>28/11/2016</td><td>1.2</td><td>Informationen Hinzugefügt</td><td>MuM</td></tr>
<tr><td>30/11/2016</td><td>1.3</td><td>Anordnungsfehler ausgebessert</td><td>MuM</td></tr>
<tr><td>12/12/2016</td><td>1.4</td><td>Inhalte Aktualisiert</td><td>MuM</td></tr>
<tr><td>14/12/2016</td><td>1.5</td><td>Deployment View Hinzugefügt</td><td>MuM</td></tr>
<tr><td>05/04/2017</td><td>2.0</td><td>Dateiformat zu .md geändert</td><td>MuM</td></tr>
</table>

## Table of Contents ##
1. Introduction
	1. Purpose
	2. Definitions, Acronyms and Abbreviations
	3. References
2. Architectural Represenation
3. Architectural Goals and Constraints
4. Use-Case View
5. Logical View
	1. Architecturally Significant Design Packages
6. Process View
7. Deployment View
8. Implementation View
9. Data View
10. Size and Performance
11. Quality

### 1. Introduction ###
1. **Purpose**
<br>Dieses Dokument soll eine Übersicht über die Smartphone-App “MuM’s Fit” aus diversen architektonischen Sichtweisen geben.
2. **Definitions, Acronyms, and Abbreviations**
<br>MuM = Max und Moritz
<br> n/a = not applicable
<br>tbd = to be determined
3. **References**
<table>
<tr><td>SRS</td><td><a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Software%20Requirements%20Specification.md">https://github.com/MH0896/MuM-s-Fit/blob/master/Software%20Requirements%20Specification.md</a></td></tr>
<tr><td>Grafik MVP</td><td><a href="http://www.techyourchance.com/mvp-mvc-android-1/">http://www.techyourchance.com/mvp-mvc-android-1/</a></td></tr>
</table>

### 2. Architectural Representation ###
<a href="http://www.techyourchance.com/mvp-mvc-android-1/">http://www.techyourchance.com/mvp-mvc-android-1/</a><br>
![MVP Architecture](https://github.com/MH0896/MuM-s-Fit/blob/master/MVP_WebGrafik.png "MVP Architecture")

### 3. Achitectural Goals and Constraints ###
Wir wenden die klassischen MVC (bzw. MVP) Prinzipien an. Wir benutzen kein spezielles Tool dafür, da wir mit Android Studio arbeiten und das dort schon vorhanden ist.  
Wie in der Grafik in Punkt 2 zu sehen ist wird unsere View vom Model isoliert und weiß sozusagen nichts. Jegliche Änderungen werden über den Presenter vorgenommen und an die View weitergeleitet.

### 4. Use-Case View ###
Overall-Use-Case-Diagram:<br>
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/UCDs/Overall_UCD.png">https://github.com/MH0896/MuM-s-Fit/blob/master/UCDs/Overall_UCD.png</a>

### 5. Logical View ###
1. **Architecturally Significant Design Packages**
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/MVP-Architecture.png">https://github.com/MH0896/MuM-s-Fit/blob/master/MVP-Architecture.png</a><br>
![MVP Architecture](https://github.com/MH0896/MuM-s-Fit/blob/master/MVP-Architecture.png "MVP Architecture")

### 6. Process View ###
tbd

### 7. Deployment View ###
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/DeploymentView.png">https://github.com/MH0896/MuM-s-Fit/blob/master/DeploymentView.png</a><br>
![Deployment View](https://github.com/MH0896/MuM-s-Fit/blob/master/DeploymentView.png "Deployment View")

### 8. Implementation View ###
tbd

### 9. Data View ###
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/db-schema.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/db-schema.PNG</a><br>
![Data View](https://github.com/MH0896/MuM-s-Fit/blob/master/db-schema.PNG "Data View")

### 10. Size and Performance ###
tbd

### 11. Quality ###
tbd