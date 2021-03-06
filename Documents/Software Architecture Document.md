-------------
# MuM's Fit Software Architecture Document #
-------------
**MuM's Fit**  
**Software Architecture Document**

**Version 2.2**

## Revision History ##
| Date       | Version | Description                   | Author |
|------------|---------|-------------------------------|--------|
| 21/11/2016 | 1.0     | Dokument erstellt             | MuM    |
| 24/11/2016 | 1.1     | Klassendiagramm Aktualisiert  | MuM    |
| 28/11/2016 | 1.2     | Informationen Hinzugefügt     | MuM    |
| 30/11/2016 | 1.3     | Anordnungsfehler ausgebessert | MuM    |
| 12/12/2016 | 1.4     | Inhalte Aktualisiert          | MuM    |
| 14/12/2016 | 1.5     | Deployment View Hinzugefügt   | MuM    |
| 05/04/2017 | 2.0     | Dateiformat zu .md geändert   | MuM    |
| 14/06/2017 | 2.1     | Letzte Informationen hinzugefügt | MuM    |
| 22/06/2017 | 2.2     | Update für final | MuM    |

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
	1. Content
	2. Pattern
	3. Metrics

### 1. Introduction ###
1. **Purpose**  
Dieses Dokument soll eine Übersicht über die Smartphone-App “MuM’s Fit” aus diversen architektonischen Sichtweisen geben.
2. **Definitions, Acronyms, and Abbreviations**  
MuM = Max und Moritz  
n/a = not applicable  
tbd = to be determined
3. **References**  

| File       | Link                                                                                                 |
|------------|------------|
| SRS        | https://github.com/MH0896/MuM-s-Fit/blob/master/Documents/Software%20Requirements%20Specification.md |
| Grafik MVP | http://www.techyourchance.com/mvp-mvc-android-1/ |

### 2. Architectural Representation ###
http://www.techyourchance.com/mvp-mvc-android-1/
![MVP Architecture](https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/MVP_WebGrafik.png "MVP Architecture")

### 3. Achitectural Goals and Constraints ###
Wir wenden die klassischen MVC (bzw. MVP) Prinzipien an. Wir benutzen kein spezielles Tool dafür, da wir mit Android Studio arbeiten und das dort schon vorhanden ist.  
Wie in der Grafik in Punkt 2 zu sehen ist wird unsere View vom Model isoliert und weiß sozusagen nichts. Jegliche Änderungen werden über den Presenter vorgenommen und an die View weitergeleitet.

### 4. Use-Case View ###
Overall-Use-Case-Diagram:  
https://github.com/MH0896/MuM-s-Fit/blob/master/Usecases/UCDs/Overall_UCD.png

### 5. Logical View ###
1. **Architecturally Significant Design Packages**  
https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/MVP-Architecture.png
![MVP Architecture](https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/MVP-Architecture.png "MVP Architecture")

### 6. Process View ###
n/a

### 7. Deployment View ###
https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/DeploymentView.png
![Deployment View](https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/DeploymentView.png "Deployment View")

### 8. Implementation View ###
n/a

### 9. Data View ###
https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/db-schema.PNG
![Data View](https://github.com/MH0896/MuM-s-Fit/blob/master/Architecture/db-schema.PNG "Data View")

### 10. Size and Performance ###
Die Applikation wird so klein wie möglich gehalten. Die Datenbank liegt auf dem Gerät, was die Performance verbessert. Je mehr Informationen gespeichert werden, desto größer wird der von der Applikation benötiger Speicher.

### 11. Quality ###
1. **Content**  
Für den Inhalt, beispielsweise die Sinnhaftigkeit der Trainingspläne, ist der Endnutzer verantwortlich. Die Funktionsfähigkeit der Applikation wurde durch regelmäßige Tests und Anpassungen sichergestellt.

2. **Pattern**  
Wir haben das "Adapter"-pattern angewendet. Dieses pattern bildet eine Schnittstelle und ermögicht es dadurch eigentlich inkompatiblen Klassen miteinander zu kommunizieren. Weiteres ist in unserem Blogeintrag zu finden: https://mumsfit.wordpress.com/2017/05/16/02-hw6-patterns/

3. **Metrics**  
Die Metrics haben wir mit hilfe von Codacy berechnet. Hier findet man unser codacy dashboard: https://www.codacy.com/app/MH0896/MuMsFit/dashboard  
Außerdem ist hier der zugehörige Blogeintrag zu finden: https://mumsfit.wordpress.com/2017/05/17/02-hw7-metrics/
