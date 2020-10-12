# Authors
Rene Villarreal\
Raul Ramon\
Xiomara Chirinos

# Fundamentals of Big Data Final Project

Our final project was built in R Studio.

There are three main folders: **Code**, **Data**, and **Documents**

**Code**: Contains the .rmd file used to create the project\
**Data**: Contains part of the dataset in CSV format, and a link to the full data set in DropBox\
**Documents**: Contains our final powerpoint presentation and our original pitch slides along with a word document with questions and answers

# Dataset

The data used for this project is from NOAA. We used data for the United States by County from 1980 to 2020. The dataset is for climate change. Contains variables like precipitation, sunshine and temperature.

# Summary

Our project contains exploratory analysis to understand what the data looks like. Below is a boxplot that shows the average temperature at different rain levels by county:

![](Images/Boxplot.JPG)

And below is the average temperature by county in a bargraph.

![](Images/Bargraph.JPG)

We also predicted some data using a loess model for rain using temperature as the independent variable:

![](Images/Scatter.JPG)

Our project also contains some time-series analysis with ARIMA models that show average temperature and forecasts:

![](Images/Arima.JPG)

# Conclusions

Our analysis concludes that:\
There is not a Linear Correlation between Rain and Temperature.\
Miami Dade and Broward are the hottest counties from the ones we tested.\
Miami Dade County is expected to become hotter by 0.30 degrees by July 2023\
Temperature and Rain have high volatility, that’s why the ARIMA models show wide error bounds.

# URL for full dataset

https://www.dropbox.com/s/7hfxwml3mnzvfck/FullData.zipx?dl=0
