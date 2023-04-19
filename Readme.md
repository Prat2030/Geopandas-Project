# Project Details

The assignment contains two datasets:

1. US States Geospatial Data

2. Occurances of Fires in 2017

## Libraries used in this :
- Geopandas
- Gspatial-plot
- Pandas
- Matplotlib
- Seaborn
- Mplleaflet

## We are solving some of the questions given below


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



### Data Dictionary for important columns:

US States:

ALAND - Land Area

AWATER - Water Area

NAME - State Name

Fire Occurances:

FIRE_TYPE - Type of Fire

IG_DATE - Datetime

ACRES - Acres Burnt


### Resources:

Geopandas Documentation: [Documentation &#8212; GeoPandas 0.12.2+0.gefcb367.dirty documentation](https://geopandas.org/en/stable/docs.html)

gspatial-plot Documentation:  [Welcome to gspatial-plot’s documentation! &mdash; gspatial-plot 0.1.0a0 documentation](https://gspatial-plot.readthedocs.io/en/latest/)
