# Data-Analysis-CVD
Analysis of fake Covid19-Data from Germany in the Format (date, location)

# What do I get out?
The Possibility to visualize a Dataset over matplotlib or folium.
The Possibilities are: 
  - a simple plot to show the outlines of an area with a given day visualizing every active case within an infective period (matplotlib)
  - a Choropleth over an interactive map, visualizing every active case on a given day with every active case within an infective period (Folium)
  - a Choropleth with a time slider over an interactive map, visualizing every active case within a time period and an infective period (Folium)
  - a Heatmap over an interactive map, visualizing every active case on a given day with every active case within an infective period(Folium)
  - a Heatmap with a time slider over an interactive map, visualizing every active case within a time period and an infective period (Folium)


# Code

- Datasets 
  + Geodata of the zip areas in Germany (shp-file)
  + fictive patient-tuple in the Format of (date, location) (csv-file)
  + Data containing all zip codes of Germany tied to city, states and county (csv-file)

- Code-Structure (everything is one section in the notebook)
  + import of the relevant packages
  + functions to read the data-sets
  + functions to process the datasets for the different applications (everything in a seperate section)
  + functions to visualize the data
  + concluding tests and visualization


# Entstehung

Ich arbeite seit Winter 2020 im Gesundheitsamt Da-Di und lerne seit Frühling 2021 ein bisschen über das Feld Data Science und die Programmiersprache Python. Gemeinsam mit einer Freundin haben wir zusammen einen Machine Learning Kurs für Python absolviert und da ich das ganze mal praktisch anwenden wollte habe ich dieses Jupyter Notebook geschrieben in der Hoffnung die Daten unseres Gesundheitsamtes in der aktuellen Pandemie einmal zu analysieren. Das ganze ist eher als Einstieg gedacht und das kennenlernen von Daten-Analysen, am Ende war das Schwierigste die Daten Beschaffung, fiktive Bereinigung und Umwandlung. Das eigentliche ploten war am Ende "eher" einfach.

Ich interessiere mich schon länger für verschiedene Digitale Themen und habe auch am Anfang meiner 20er mal ein Mathematik und Informatik Studium nicht beendet. Daher hatte ich etwas Vorkenntnisse und theoretisches Verständnis. Es ist aber am Ende auch mein erstes praktisches Code-Projekt, daher sind mit Sicherheit einige Performance Verbesserungen noch rauszuholen.

Mein Testdatensatz besteht aus ca. 40.000 fiktiven Patiententupeln und sind nur aus dem Bereich Darmstadt, d.h. Stadtkreis Darmstadt und Landkreis Darmstadt-Dieburg. Der Datensatz ist ca. 3 mal so groß wie der reale Datensatz gewesen wäre. Leider fand hier im Gesundheitsamt keine Verwendung für den Code statt.


# Quellen und Danksagungen

Vielen Dank an Ralph Frankenbach für das Feedback und den Austausch über meinen Code

- erste Inspiration und etwas Code
https://juanitorduz.github.io/germany_plots/

- Datensätze: Geodaten+PLZ-Daten
https://www.suche-postleitzahl.org/downloads

- Verständnis des Plug-Ins TimeSliderChoropleth
https://nbviewer.jupyter.org/github/python-visualization/folium/blob/master/examples/TimeSliderChoropleth.ipynb

- Verständnis des Plug-Ins HeatMapWithTime
https://nbviewer.jupyter.org/github/python-visualization/folium/blob/master/examples/HeatMapWithTime.ipynb

- Stackoverflow......of course
https://stackoverflow.com/


# Dokumentation der Software und Pakete

- Python *usedVersion3.8*
https://www.python.org/doc/

- Pandas *usedVersion1.2.5*
https://pandas.pydata.org/pandas-docs/stable/

- Folium *usedVersion0.0.0*
https://python-visualization.github.io/folium/

- Geopandas *usedVersion0.9.0*
https://geopandas.org/

- Numpy: *usedVersion1.21.0*
https://numpy.org/doc/

- Matplotlib: *usedVersion3.4.2*
https://matplotlib.org/

- Geopy: *usedVersion2.1.0*
https://geopy.readthedocs.io/en/stable/

- Branca: *usedVersion0.4.2*
https://python-visualization.github.io/branca/colormap.html
