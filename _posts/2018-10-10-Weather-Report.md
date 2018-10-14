---
title:  "Weather Report"
date:   2018-10-10 23:37:00
categories: text
---

![alt text](https://github.com/vittalsiddaiah/UTDataAnalyticsAssignments/blob/master/images/WeatherReportConsolidated.png?raw=true)

This is an **analysis and visualization** of ***weather*** of 550+ cities across the world. The main objective was to showcase the relationship of various factors like temperature, humidity, cloudiness and wind speed with respect to the distance from the equator. 

For this analysis, approx. 600 coordinate pairs of latitude and longitude were created randomly and then [citypy](https://pypi.org/project/citipy/) was used to generate city names for respective coordinates. After selecting unique non-repeat observations, a weather check was performed on each of the cities using a series of successive API calls from OpenWeatherMap. Then all different point of interests were plotted against latitude using [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) libraries.

In conclusion, an equatorial climate is a type of tropical climate in which there is no dry season. It is usually found at latitudes within five degrees of the equator and tropical rainforest is the natural vegetation.

