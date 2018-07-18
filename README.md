#Food Deserts in New Mexico
##Exploring Data Using the Descartes Labs Python Client Library in a JupyterLab Environment

The interesting work that Descartes Labs has done on the issue of [measuring food security from space](https://medium.com/@DescartesLabs/hacking-food-security-from-space-b06bd6243c4a) inspired me to explore a different aspect of food security: US Department of Agriculture data on food deserts. Which of New Mexico's low income food deserts contains a large number of people affected? One way to answer this question would be to look at total population of each food desert, but with census tracts of widely differing surface areas and grouped by similar population sizes, this doesn't necessarily provide a complete picture. I formulated a more specific question: "Which flagged census tract has the highest median population density?"

![Low Income and Low Food Access Census Tracts Map](https://github.com/lauraatdescartes/pythonproject/raw/master/images/food-deserts.png "Low Income and Low Food Access Census Tracts")

This repository contains the Jupyter notebook, preprocessed data, and other information I used in this project,
in order to facilitate the replication of the results for learning purposes, as well as a use case for the Descartes Labs
python client library in the developers.descarteslabs.com environment.

Data sources used for this project were:
- [United States Dept. of Agriculture Food Access Research Atlas](https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data.aspx)
- [US Census Bureau Census Tract Shapefile for New Mexico](https://www.census.gov/geo/maps-data/data/cbf/cbf_tracts.html#tr2015), from 2015 to match the latest Food Access Atlas data year (select New Mexico from dropdown)
- [Descartes Labs Population Density raster product](https://catalog.descarteslabs.com/?/product/5151d2825f5e29ff129f86d834946363ff3f7e57:CIESIN:popden:v0)
