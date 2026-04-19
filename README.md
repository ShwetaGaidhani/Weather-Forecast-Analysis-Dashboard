# Weather Forecast Analysis Dashboard

An interactive and real-time weather analytics dashboard built using Microsoft Power BI. This project integrates live weather API data and transforms it into meaningful, user-friendly visual insights.

## Overview

The Weather Forecast Analysis Dashboard is designed to present real-time meteorological data in a clear and interactive format. It enables users to monitor weather conditions, analyze trends, and make informed decisions using dynamic visualizations.

The dashboard connects to a live Weather API, processes JSON data using Power Query, and utilizes DAX for advanced calculations and KPIs.


## Objectives

- Integrate real-time weather data using a live API  
- Visualize key parameters such as temperature, humidity, wind speed, and AQI  
- Provide hourly and daily forecast insights  
- Enable location-based filtering  
- Automate data refresh for up-to-date information  


## Features

- Real-time Weather API integration  
- Interactive dashboard visualizations  
- Location-based filtering  
- Automated data refresh  
- Hourly and daily forecast analysis  
- KPI cards for key metrics  


## Tech Stack

- Microsoft Power BI Desktop  
- Power Query (M Language)  
- DAX (Data Analysis Expressions)  
- Weather API (OpenWeatherMap / WeatherAPI)  

## Dashboard Components

- KPI Cards: Temperature, Humidity, Wind Speed, AQI  
- Line Charts: Hourly and daily forecast trends  
- Bar Charts: Wind speed and rainfall analysis  
- Gauge Chart: Air Quality Index (AQI)  
- Slicers: Location-based filtering  


## How to Use

1. Open the `.pbix` file in Microsoft Power BI Desktop  
2. Ensure an active internet connection  
3. Click "Refresh" to load the latest data  
4. Use slicers to select location  
5. Analyze the dashboard visuals  


## Data Flow

Weather API → Power Query → Data Model → DAX Measures → Dashboard Visuals  


## Use Case

This dashboard helps users monitor real-time weather conditions, analyze trends, compare multiple locations, and support planning and decision-making.


## Future Enhancements

- Machine learning-based weather prediction  
- Historical trend analysis  
- Multi-location comparison  
- Mobile-optimized dashboard  


## References

- https://openweathermap.org/api  
- https://www.weatherapi.com/docs/  
- https://docs.microsoft.com/en-us/power-bi/  
- https://dax.guide/  


## Appendices

- API Response Sample (JSON format)  
- Power Query M Code  
- DAX Measures Documentation  
- Dashboard Screenshots  

## Conclusion

This project demonstrates how real-time API data can be transformed into meaningful insights using Microsoft Power BI. It highlights the effectiveness of modern data visualization tools in building interactive and scalable analytical solutions.
