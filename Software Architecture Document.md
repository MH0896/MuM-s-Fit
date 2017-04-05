----------
#MuM's Fit #
----------
<br><br>
**MuM's Fit**  
**Software Architecture Document**  
<br>
**Version 1.5**
<br><br><br>
##Revision History##
<table>
	<tr>
		<td>Date</td><td>Version</td><td>Description</td><td>Author</td>
	</tr>
<tr>
		<td>21/11/2016</td><td>1.0</td><td>Dokument erstellt</td><td>MuM</td>
	</tr>
<tr>
		<td>24/11/2016</td><td>1.1</td><td>Dokument erstellt</td><td>MuM</td>
	</tr>
<tr>
		<td>28/11/2016</td><td>1.2</td><td>Dokument erstellt</td><td>MuM</td>
	</tr>
<tr>
		<td>30/11/2016</td><td>1.3</td><td>Dokument erstellt</td><td>MuM</td>
	</tr>
<tr>
		<td>12/12/2016</td><td>1.4</td><td>Dokument erstellt</td><td>MuM</td>
	</tr>
<tr>
		<td>14/12/2016</td><td>1.5</td><td>Dokument erstellt</td><td>MuM</td>
	</tr>
</table>
</center>
<br>

## Table of Contents##
1. Introduction
	1. Purpose
	2. Definitions, Acronyms and Abbreviations
	3. References
4. Architectural Represenation
5. Architectural Goals and Constraints
6. Use-Case View
7. Logical View
	1. Architecturally Significant Design Packages
2. Process View
3. Deployment View
4. Implementation View
5. Data View
6. Size and Performance
7. Quality
<br>

##Software Architecture Document##
###1. Introduction###
1. **Purpose**
	<br> Dieses Dokument soll eine Übersicht über die Smartphone-App “MuM’s Fit” aus diversen architektonischen Sichtweisen geben.
2. **Definitions, Acronyms, and Abbreviations**
	<br>MuM = Max und Moritz <br> n/a = not applicable<br>tbd = to be determined
3. **References**
<table>
	<tr>
	<td>SRS</td><td><a href="https://github.com/MH0896/MuM-s-Fit/blob/master/Software%20Requirements%20Specification.pdf">https://github.com/MH0896/MuM-s-Fit/blob/master/Software%20Requirements%20Specification.pdf</a></td>
	</tr>
	<tr>
	<td>Grafik MVP</td><td><a href="http://www.techyourchance.com/mvp-mvc-android-1/">http://www.techyourchance.com/mvp-mvc-android-1/</a></td>
	</tr>
</table>
<br>

###2. Architectural Representation###
<a href="http://www.techyourchance.com/mvp-mvc-android-1/">http://www.techyourchance.com/mvp-mvc-android-1/</a><br>
![MVP Architecture](https://github.com/MH0896/MuM-s-Fit/blob/master/MVP_WebGrafik.png "MVP Architecture")
<br>
###3. Achitectural Goals and Constraints###
Wir wenden die klassischen MVC (bzw. MVP) Prinzipien an. Wir benutzen kein spezielles Tool dafür, da wir mit Android Studio arbeiten und das dort schon vorhanden ist.  
Wie in der Grafik in Punkt 2 zu sehen ist wird unsere View vom Model isoliert und weiß sozusagen nichts. Jegliche Änderungen werden über den Presenter vorgenommen und an die View weitergeleitet.
<br>

###4. Use-Case View###
Overall-Use-Case-Diagram:<br>
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/UCDs/Overall_UCD.png">https://github.com/MH0896/MuM-s-Fit/blob/master/UCDs/Overall_UCD.png</a>
<br>

###5. Logical View###
1. **Architecturally Significant Design Packages**
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/MVP-Architecture.png">https://github.com/MH0896/MuM-s-Fit/blob/master/MVP-Architecture.png</a><br>
![MVP Architecture](https://github.com/MH0896/MuM-s-Fit/blob/master/MVP-Architecture.png "MVP Architecture")
<br>
###6. Process View###
tbd <br>

###7. Deployment View###
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/DeploymentView.png">https://github.com/MH0896/MuM-s-Fit/blob/master/DeploymentView.png</a><br>
![Deployment View](https://github.com/MH0896/MuM-s-Fit/blob/master/DeploymentView.png "Deployment View")
<br>
###8. Implementation View###
tbd
<br>

###9. Data View###
<a href="https://github.com/MH0896/MuM-s-Fit/blob/master/db-schema.PNG">https://github.com/MH0896/MuM-s-Fit/blob/master/db-schema.PNG</a><br>
![Data View](https://github.com/MH0896/MuM-s-Fit/blob/master/db-schema.PNG "Data View")<br>

###10. Size and Performance###
tbd<br>

###11. Quality###
tbd<br>