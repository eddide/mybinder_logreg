# Binder Badge
https://mybinder.org/v2/gh/eddide/mybinder_logreg/23ab37941c6f7fe1791ccc451c6570af4551a87e

# Dokumentation zur Ausführung
1. Aktivieren des Links zu Binder
2. Öffnen des Python-Notebooks "Installationen"
3. In der Toolbar unter "Kernel" "Restart & Run All" aktivieren. --> Bestätigen des Pop-up Fensters mit "Restart and Run All Cells"
4. Nach der erfolgreichen Ausführung Schließen des Python-Notenooks "Installationen"
5. Öffnen des Pyhton-Notebooks "Logistic Regression"
6. In der Toolbar unter "Kernel" "Restart & Run All" aktivieren. --> Bestätigen des Pop-up Fensters mit "Restart and Run All Cells"
7. Ergebnisse mit den unten beschriebenen Ergebnissen abgleichen.

# Logistische Regression

In diesem Projekt werden wir mit Fake-Daten zu Werbung arbeiten, die aufzeigen, ob ein Nutzer auf eine Werbeanzeige auf einer Webseite einer Firma geklickt hat oder nicht. Wir werden versuchen ein Modell zu erstellen, das anhand von Nutzereigenschaften vorhersagt, ob dieser auf die Werbung klicken wird oder nicht.

Der Datensatz beinhaltet folgende Eigenschaften:

* 'Daily Time Spent on Site': Zeit auf der Webseite in Minuten
* 'Age': Alter in Jahren
* 'Area Income': Durchschnittliches Einkommen der Region des Nutzers
* 'Daily Internet Usage': Durchschnittliche Minutenzahl die der Nutzer täglich im Internet ist
* 'Ad Topic Line': Überschrift der Werbung
* 'City': Stadt des Nutzers
* 'Male': Ob der Nutzer männlich ist (1) oder nicht (0)
* 'Country': Land des Nutzers
* 'Timestamp': Zeit zu der der Nutzer auf die Werbung geklickt oder das Fenster geschlossen hat
* 'Clicked on Ad': Ob der Nutzer gelickt hat (1) oder nicht (0)

## Anwendung
### Libraries Import
zuerst werden die relevanten Libraries importiert
- pandas
- numpy
- matplotlib
- seaborn
### Daten Import und Überprüfung
dann werden die Daten importiert und überprüft
- Anzeigen der Daten
- Information der Daten
- Beschreibung der Daten
### Explorative Datenanalyse
Verwendung unterschiedlicher Visualisierungen um die Daten zu erforschen
- Histogramm
- Jointplot
- Pairplot
### Logistische Regression
Anwenden der logistischen Regression zur Vorhersage der Kategorie
- Aufsplitten in Trainings- und Testdaten
- Trainieren und Fitten des Modells auf den Datensatz
### Evaluation der Vorhersage
Evaluierung über den classification report.
Es sollten ähnliche Ergebnisse wie diese angezeigt werden:
- accuracy: 91%
- reall: 96 und 85%
- f1-score: 91 und 90 %
