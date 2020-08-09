# Hourly Weather Data Analysis and Prediction                                                                                                                              2019
## Technology Used: Python, SQLITE3
##     Analyzed hourly weather data to know the discrepancy in attributes & predicted weather of a location for parameters. Plotted different time series graphs for daily, monthly, quarterly and yearly data & determined the position of tornadoes.


### Introduction: 
We will be attempting to find the correlation between the weather conditions of different cities at different times and its cause on the occurrence of tornadoes and other weather events. Our main objective is to try to analyze, how the occurrence of a tornado depends on different weather conditions such as change in temperature or pressure or wind direction or speed.

### Dataset Description:
1.	Dataset 1 - Historical Hourly Weather Data (USA). The above dataset contains around 5 years of hourly measurements data of various weather attributes, such as temperature, humidity, air pressure, etc. for the various cities in USA. 
2.	Dataset 2 - USA Historical Tornado. This dataset contains the details of tornadoes from 1950 to 2015. This contains features like the number of tornadoes, the latitudes and longitudes of the origin among others. 
3.	Dataset 3 - Longitudes and Latitudes of Cities in USA. This dataset contains the longitudes and latitudes of different American cities. 

### Analysis:
•	Analyze hourly weather data to know the discrepancy of attributes like temperature, wind speed, pressure etc., in different cities at different times.<br />
•	Predict the weather of a location for given parameters. <br />
•	Depending on the weather conditions, we can make assumptions on occurrences of drastic changes in the current weather conditions. <br />
•	If we know the weather condition, we can predict the chances of tornado occurrence and their location. 

### Analysis method:
1.	Using Python Libraries like NumPy and Python Data Analysis Library for Loading the datasets from CSV to SQLite, Subsetting the data and Cleansing the data.
2.	Using SQlite3 for performing joins on the datasets.
3.	Using the Matplotlib library to plot graphs from the analyzed data.
4.	Using the concept of Time Series for forecasting the weather data.

### Milestones:
1.	Loading data from csv and subsetting the dataset.
2.	Cleaning the data by replacing null values with the mean.
3.	Plotting different time series graphs for weekly, monthly and yearly data.
4.	Plotting comparison Graphs with different variables like humidity, wind speed, pressure and its effect on weather.
5.	Determine the position of tornadoes using the USA historical tornadoes data.
6.	Using Cities and USA historical tornado data determine the city, which were hit by tornadoes.
7.	Using the data collected above to know the effect of weather on formation of tornadoes.

### References:
•	https://www.kaggle.com/selfishgene/historical-hourly-weather-data<br />
•	https://www.ncdc.noaa.gov/climate-information/extreme-events/us-tornado-climatology<br />
•	https://numpy.org/  <br />
•	https://pandas.pydata.org/  <br />
•	https://matplotlib.org/  <br />
•	https://www.sqlite.org/ 
