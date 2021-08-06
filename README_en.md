# Data-Analysis-CVD
Analysis of fake Covid19-Data from Germany in the Format (date, location)

# What do I get out?
The Possibility to visualize a Dataset over matplotlib or folium.
The Possibilities are: 
  - a simple plot to show the outlines of an area with a given day visualizing every active case within an infective period (matplotlib)
  - a Choropleth over an interactive map, visualizing every active case on a given day with every active case within an infective period (Folium)
  - a Choropleth with a time slider over an interactive map, visualizing every active case within a time period and an infective period (Folium)
  *still to come* "- a Heatmap over an interactive map, visualizing every active case on a given day with every active case within an infective period(Folium)
  - a Heatmap with a time slider over an interactive map, visualizing every active case within a time period and an infective period (Folium)"


# Code

- Datasets 
  + Geodata of the zip areas in Germany (shp-file)
  + fictive patient-tuple in the Format of (date, location) (csv-file: !!german csv-file, it's seperatet by a ";" instead of ","!!)
  + Data containing all zip codes of Germany tied to city, states and county (csv-file)

- Code-Structure (everything is one section in the notebook)
  + import of the relevant packages
  + functions to read the data-sets
  + functions to process the datasets for the different applications (everything in a seperate section)
  + functions to visualize the data
  + concluding tests and visualization

# Sources and Thankyou

Many thank to Ralph Frankenbach for the feedback and the exchange about my code (see his website for an javascript implication of this code)

- first inspiration and some code
https://juanitorduz.github.io/germany_plots/

- Data: Geodaten+ZIP-Data
https://www.suche-postleitzahl.org/downloads

- Understanding of the Plug-In TimeSliderChoropleth
https://nbviewer.jupyter.org/github/python-visualization/folium/blob/master/examples/TimeSliderChoropleth.ipynb

- Understanding of the Plug-In HeatMapWithTime
https://nbviewer.jupyter.org/github/python-visualization/folium/blob/master/examples/HeatMapWithTime.ipynb

- Stackoverflow......of course
https://stackoverflow.com/


# Documentation of the Software and Packages

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
