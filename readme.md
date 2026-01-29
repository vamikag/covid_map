# COVID-19 in the United States (2020)

This project explores how COVID-19 affected different parts of the United States in 2020 using two interactive web maps.  
The goal is to compare **case rates** (which account for population) with **total case counts** (which show absolute burden) and see how the spatial patterns differ at the county level.

## Map Overview

### Map 1: COVID-19 Case Rates
This map shows COVID-19 **case rates per 1,000 residents** for each U.S. county in 2020.  
A choropleth map is used so that counties can be compared more fairly by adjusting for population size.

- Darker colors indicate higher case rates
- Clicking a county displays the county name, state, and case rate
- The Albers projection is used for a more accurate U.S. map

### Map 2: COVID-19 Case Counts
This map shows **total COVID-19 case counts** using proportional circle symbols.

- Larger circles represent counties with more total cases
- This map highlights where the absolute burden of COVID-19 was highest
- Clicking a circle displays the county name, number of cases, and deaths
- The same Albers projection is used for consistency

##  Data Sources

- **COVID-19 cases and deaths:**  
  The New York Times COVID-19 dataset  
  https://www.nytimes.com/interactive/2021/us/covid-cases.html

- **Population data:**  
  2018 American Community Survey (ACS) 5-Year Estimates  
  https://www.census.gov/programs-surveys/acs

- **County boundaries:**  
  U.S. Census Bureau cartographic boundary files  
  https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html
