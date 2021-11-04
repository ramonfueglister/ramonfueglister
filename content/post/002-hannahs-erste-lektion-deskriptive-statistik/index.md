---
title: "003: Hannah möchte wissen ob ihre Lernenden der letzten Jahrgänge im
  Durchschnitt ähnlich alt waren (t-test)"
date: 2021-11-01T19:32:40.277Z
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
##### 1. Story

https://wiki.uib.no/jamovide/index.php/

Jamovi https://statistics.berkeley.edu/computing/r-t-tests

https://r-intro.tadaa-data.de/book/ANOVA.html

https://bjoernwalther.com/t-test-fuer-unabhaengige-stichproben-in-r-rechnen-und-interpretieren/



In vielen Fachbüchern wird empfohlen, dass bei einem Stichprobenumfang von 𝑛 ≥ 30
die Annahme der Normalverteilung für die meisten praktischen Zwecke ignoriert werden
kann (Arnold, 1990; Casella und Berger, 1990 sowie Moore und McCabe, 1993).

**2. Fragestellung**

Gibt es einen Unterschied zwischen der Motivation der Studierenden im Jahr 2020 und 2021?

**3. Hypothesen**

Generelle Hypothese: Es gibt einen Unterschied zwischen den Motivationsmittelwerten des Jahrgangs 2020 und 2021

##### 4. Statistische Hypothese:

H0 = Es gibt keinen Unterschied zwischen den Motivationsmittelwerten des Jahrgangs 2020 und 2021

H1 = Es gibt einen Unterschied zwischen den Motivationsmittelwerten des Jahrgangs 2020 und 2021

##### 4. Variablen

Y =gemessene Motivation auf einer Skala von 1-6

X = Jahrgang 2020 und Jahrgang 2021

**5. Ausgewähltes Verfahren: T-Test** 

Dert-Test für unabhängige Stichproben testet, ob die Mittelwerte zweier unabhängiger Stichproben verschieden sind oder verkürzt: "Unterscheiden sich die Mittelwerte zweier unabhängiger Stichproben?"

**4. Voraussetzungen**

\- 2 Gruppen, die unabhängig voneinander sind (z.B. 2 Jahrgänge, 2 Klassen etc.) gemessen als kategoriale Variable

\- sinnvollerweise mindestens 30 gemessene Datenpunkte (z.B. Personen) pro Gruppe

\- eine kontinuerliche Variable

statistische Voraussetzungen





**4. Bestimmung der abhängigen und unabhängigen Variable(n)**





**6. Statistische Hypothesen**



##### 7. Statistische Voraussetzungen:



3. 



Sie benötigen eine zweistufige Gruppenvariable (z. B. Behandlung / Kontrolle) und eine kontinuierliche Ergebnisvariable. Vergewissern Sie sich, dass das korrekte [Skalenniveau](https://wiki.uib.no/jamovide/index.php/Skalenniveau_festlegen "Skalenniveau festlegen") gewählt ist, so dass die Gruppenvariable mit dem Symbol für kategoriale Variablen [![Icon Nominal.jpg](https://wiki.uib.no/jamovide/images/thumb/1/1d/Icon_Nominal.jpg/30px-Icon_Nominal.jpg)](https://wiki.uib.no/jamovide/index.php/Datei:Icon_Nominal.jpg) und die kontinuierliche Variable mit dem Symbol für kontinuierlichen Variablen [![Icon Continuous.jpg](https://wiki.uib.no/jamovide/images/thumb/d/d8/Icon_Continuous.jpg/30px-Icon_Continuous.jpg)](https://wiki.uib.no/jamovide/index.php/Datei:Icon_Continuous.jpg) gekennzeichnet ist.\
Ein korrekter Datensatz sollte folgendermaßen aussehen:



Wählen Sie Analyses → T-Test -> Independent Samples T-Test.



Das Ergebnis wird in der Resultatausgabe (rechts) angezeigt.







Verschieben Sie die Ergebnisvariablen (abhängige Variablen) in "Dependent Variables" und die Gruppenvariable in "Grouping Variable".



002: Hannahs erste Lektion (Deskriptive Statistik)