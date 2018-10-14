---
title:  "Weather Report"
date:   2018-10-10 23:39:00
categories: text
---

<img src="{{site.baseurl}}/assets/WeatherReports/WeatherReportConsolidated.png"> 

This is an **analysis and visualization** of ***weather*** of 550+ cities across the world. The main objective was to showcase the relationship of various factors like temperature, humidity, cloudiness and wind speed with respect to the distance from the equator. 

For this analysis, approx. 600 coordinate pairs of latitude and longitude were created randomly and then [citypy](https://pypi.org/project/citipy/) was used to generate city names for respective coordinates. After selecting unique non-repeat observations, a weather check was performed on each of the cities using a series of successive API calls from OpenWeatherMap. Then all different point of interests were plotted against latitude using [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) libraries.

In conclusion, an equatorial climate is a type of tropical climate in which there is no dry season. It is usually found at latitudes within five degrees of the equator and tropical rainforest is the natural vegetation.

<img src="{{site.baseurl}}/assets/WeatherReports/LatitudeVsTemperture.png">

Temperature raises at the equator. Most of the places near equator have a tropical climate.



<img src="{{site.baseurl}}/assets/WeatherReports/LatitudeVsHumidity.png"> 

Humidity seems to be uniformly distributed across the latitude and seems to be dense and higher.


<img src="{{site.baseurl}}/assets/WeatherReports/LatitudeVsCloudiness.png"> 

Cloudiness is been uniformly distributed


<img src="{{site.baseurl}}/assets/WeatherReports/LatitudeVsWindSpeed.png"> 

The wind speed is not much affected by the distance from the equator, it’s almost moderate throughout the globe.
