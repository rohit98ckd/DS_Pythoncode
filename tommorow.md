# Assignment

The assignment contains two datasets:

1. US States Geospatial Data

2. Occurances of Fires in 2017

A boiletplate code has been given to you in a file called Analysis.ipynb. You can make use of it or do analysis on your own.

Tasks:

1. Do a spatial join on two datasets such that each fire occurance has state information (Look for sjoin in geopandas documentation)

2. Which state had the most number of fires?

3. Which state had the least number of fires?

4. Is there any relationship between number of fires vs total water area (AWATER)?

5. Plot a heatmap of fires (You can use gspatial-plot or geopandas or any other library)

6. Plot a density map of fire occurances (You can use gspatial-plot or seaborn or any other library)

7. Which state had the highest number of Wildfires? (FIRE_TYPE column)

8. Which state had the highest number of  acres burned? (ACRES)

9. Which Month had highest number of fires?

10. Which State had highest number of fires for the month in question 9?

Data Dictionary for important columns:

US States:

ALAND - Land Area

AWATER - Water Area

NAME - State Name

Fire Occurances:

FIRE_TYPE - Type of Fire

IG_DATE - Datetime

ACRES - Acres Burnt

Libraries:

It is advised to create a ***new virtual environment with python 3.10***.

You'll be primarily using two libraries

1. geopandas : Pandas for geospatial data.

2. gspatial-plot : A Seaborn like plotting interface for geopandas

You can also use any other library of your choice.

Note: Installing gspatial-plot will also install geopandas. gspatial-plot is in beta, if you are having any problems with it, you can report it to us, you can do all the analysis using geopandas only but gspatial-plot will simplify the process.

`pip install gspatial-plot`

Resources:

Geopandas Documentation: [Documentation &#8212; GeoPandas 0.12.2+0.gefcb367.dirty documentation](https://geopandas.org/en/stable/docs.html)

gspatial-plot Documentation:  [Welcome to gspatial-plot’s documentation! &mdash; gspatial-plot 0.1.0a0 documentation](https://gspatial-plot.readthedocs.io/en/latest/)
