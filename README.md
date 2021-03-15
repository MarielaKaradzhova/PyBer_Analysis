# PyBer: A Python Based Ride Sharing App Company


![](https://github.com/MarielaKaradzhova/PyBer_Analysis/blob/main/images/PYBER.png)

*Improving Access and Affordability.*




## Purpose of Project
The purpose of this project is to explore and analyze ride-sharing data from a large dataset with the goal of improving access to ride-sharing services. Second, this project aims to determine affordability for underserviced neighbourhoods, and to provide acessible and affordable transportation where needed.

## Overview of Statistical Analysis
### Resources
Data Source: https://github.com/MarielaKaradzhova/PyBer_Analysis/tree/main/Resources

Software: Python 3.7.6, Jupyter Notebook 6.1.4
Python Tools: pandas, Matplotlib

This analysis was performed using Jupyter Notebook, an open-sourced web application that allows users to create and share documents with live code, equations, visualizations and text. The exploratory analysis of this project contains dataframes created from a much larger dataset (see the Resources folder for original data sources), which includes statistics from different cities, dates, numbers of drivers, fare costs, numbers of rides and numbers of users. The goal of this analysis was to obtain summary statistics between the type of city,  number of drivers and riders, and the percentage of total fares, drivers and riders per city type. 


Link to the full code here: https://github.com/MarielaKaradzhova/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb


## Results

### Differences in ride-sharing data among the different city types 

Displayed below is a summary analysis table showing the differences in ride-sharing data among the different city types:



![](https://github.com/MarielaKaradzhova/PyBer_Analysis/blob/main/analysis/pyber_summary_table.png)


From the "Total Rides" column, we can see that Urban cities had the highest amount of rides (1625), where Rural cities had the least amount of rides (125) and Suburban cities were somewhere in between with 625 rides.
Furthermore, Urban cities had a total of 2405 drivers, where Rural cities had 78 drivers, and Suburban cities had a total of 490 drivers. 

Next, the "Total Fares" column show that in Urban cities amounted to 39,854, Suburban cities had 19356, and in rural cities there was a total of 4328 fares. 
Total amount of fares for each city type

The "Average Fare Per Ride" column shows that the average fare per ride to be around 34.60 in Urban cities, around 30.98 in Suburban cities and around 34.60 in rural cities.

Finally, values in the the "Average Fare Per Driver" column were calculated based on the sum of all fares, divided by the total rides per each city type, respectively. The results show that the
average fare per driver in Urban cities is around 16.57, in Suburban cities it is around 39.50, and in Rural cities it is around 55.50.

These results show that there are several important differenced between city types. Specifically, there are more drivers and riders in highly populated areas such as Urban and Suburban cities, which in turn results in lower fares per ride, and lower fares per driver. Also, Rural cities have less drivers and riders, and higher fare per driver and per drive, respectively (see Fig.1). 


![](https://github.com/MarielaKaradzhova/PyBer_Analysis/blob/main/analysis/Fig1.png)

Below is a detailed line chart that shows the differences in fare per city type between January and March of 2019. The trends of each city type are stable for the most part, but we can see an increase in fares for Suburban cities in April, but overall Urban cities have the most amount of fares sold, followed by Suburban cities, and finally Rural cities have the lowest number of fares.

![](https://github.com/MarielaKaradzhova/PyBer_Analysis/blob/main/analysis/Fig2.png)


## Summary: 
Based on the results, **three business recommendations are provided below to the CEO** with the purpose of addressing any disparities among the city types.

Depending on the needs of riders, (ex. going to work, shopping, general transportation) there could be a way to improve accessibility to ride-sharing services and more available drivers in areas that are underserviced at peak times with respect to commuting to and from work. If riders need ride-sharing services for errands such as shopping/grocieries, then PyBer could look into a delivery service partnered with grocery stores/retail stores which could increase acessibility and affordability by cutting down the cost of a fare at given times of the day. However this may not be a very accessible option for people in Rural areas, therefore more research and analysis is needed to determine a practical and sustainable plan of action. Finally, PyBer could create a shuttle category of ride-sharing services dedicated to access with bigger vehicles which function similarly to public transportation on a smaller scale. This type of ride-sharing is privatized and quite popular in European countries, especially in rural areas. Shuttle services could decrease the cost of fare per person and accomodate more riders per driver in Rural areas, making ride-sharing more accessible and affordable. One downside to this idea would be finding drivers with a bigger vehicle that can accomodate more riders, that is one aspect which needs more research to determine the practicality and possibility of such service offered by PyBer.