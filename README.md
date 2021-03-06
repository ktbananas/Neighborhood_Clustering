# Neighborhood_Clustering
Principal Component Analysis application to Minneapolis population demographics dataset.

May 2020
As part of a larger project to identify and communicate trends in Minneapolis crime statistics, this analysis provided context about neighborhood demographics. We wanted to understand the different characteristics of each neighborhood and identify which neighborhoods were similar based on over 40 quantitative dimensions. To reduce dimensionality we implemented a Principal Component Analysis. 

Step 1: There were some differences in the neighborhood names between the crime and demographics dataset. So the first step was to match neighborhood names.
 
Step 2: Clean up of extra columns with redundant data. 

Step 3: Apply sklearn kmeans clustering and Principal Component Analysis function. 

Step 4: Output visualization of clusters with centroids. Marked specific neighboorhoods of interest in order to compare crime data. 

Interestingly, neighbohoods having similar demographic characteristics did not also have similar number of crime incidents. Given more time, we might have considered each characteristic vs total crime incidents to see if there was a correlation, but the overall goal of the project was to tell a story about crime patterns Minneapolis. Demographics was only helpful in providing context.

Source of datasets:
https://www.mncompass.org/demographics/overview
http://opendata.minneapolismn.gov/datasets/neighborhood-crime-stats

Very helpful article I leaned on greatly for this project:
https://towardsdatascience.com/dive-into-pca-principal-component-analysis-with-python-43ded13ead21