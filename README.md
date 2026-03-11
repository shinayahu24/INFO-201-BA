# Crime and COVID-19 Analysis Dashboard

This project presents an interactive dashboard that explores crime patterns in Los Angeles during the COVID-19 pandemic using crime report data and public health data. The analysis focuses on how crime levels changed over time during the pandemic and whether shifts in COVID-19 cases corresponded with changes in criminal activity.

The dashboard combines data cleaning, statistical summaries, and visualizations to examine trends in daily crime reports, the most common crime types during the pandemic years, and the relationship between COVID-19 cases and crime levels.


## Dashboard

The project is implemented in R using Quarto, with visualizations built using ggplot2 and data processing performed using dplyr from the tidyverse ecosystem.

The dashboard presents several analytical views, including:

- Changes in total daily crime reports over time
- Identification of the most common crime types during the pandemic years (2020–2021)
- Examination of the relationship between COVID-19 case counts and daily crime reports
- Contextual information describing the datasets and research questions

The rendered dashboard allows viewers to explore how crime patterns shifted during the pandemic and whether public health conditions appear to influence criminal activity.


## Data Sources

This project draws on two main datasets:

- **Los Angeles Crime Data** from
  https://catalog.data.gov/dataset/crime-data-from-2020-to-present
  The data allows us to analyze trends in reported crime across Los Angeles beginning in 2020.

- **COVID-19 Case Data** from
  https://covidtracking.com/data/
  This dataset contains daily COVID-19 statistics collected from U.S. state public health departments. 

By combining these datasets, the project investigates whether changes in pandemic conditions correspond with changes in crime patterns.


## Technologies Used

- R
- Quarto
- tidyverse
- plotly
- ggplot2
