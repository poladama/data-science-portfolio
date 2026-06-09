# Philadelphia Car-Related Property Crime Analysis (2018–2025)

## Project Overview

This project analyzes car-related property crime in Philadelphia between 2018 and 2025 using incident-level crime data from the Philadelphia Police Department. The analysis focuses on two offenses:

* Motor Vehicle Theft
* Theft from Vehicle

The goal is to identify how these crimes have changed over time, where they are concentrated geographically, and whether meaningful day-of-week patterns exist.

## Research Questions

1. How have car-related property crime trends changed between 2018 and 2025?
2. Which Philadelphia police districts experience the highest levels of car-related property crime?
3. Do car-related property crimes occur more frequently on certain days of the week?

## Data Sources

Philadelphia Police Department crime incident data obtained through OpenDataPhilly:
<https://opendataphilly.org/datasets/crime-incidents/>

The original annual datasets (2018–2025) are not included in this repository due to file size constraints.

A GeoJSON file containing Philadelphia Police District boundaries was used for the geographic analysis and mapping component of the project: 
<https://opendataphilly.org/datasets/police-districts/>

## Methods

The analysis was conducted in Python using:

* Pandas for data cleaning and aggregation
* Seaborn and Matplotlib for visualization
* GeoPandas for geographic analysis and mapping

## Key analytical steps included:

* Combining annual crime datasets (2018–2025)
* Filtering incidents to motor vehicle theft and theft from vehicle
* Creating monthly and day-of-week variables
* Aggregating incidents by police district
* Mapping crime concentrations using district boundary data

## Key Findings

* Car-related property crime increased substantially after 2021.
* The increase was driven primarily by motor vehicle theft.
* Crime levels varied considerably across police districts, with the highest concentrations occurring in Northeast Philadelphia.
* Car-related property crime occurred at similar levels across all days of the week, with no meaningful day-of-week pattern.


## Files

* **philadelphia_car_crime_analysis.ipynb** – Jupyter Notebook with data preparation, analysis, and visualization code
* **philadelphia_car_crime_analysis.html** - HTML version of the Jupyter Notebook with data preparation, analysis, and visualization code
* **philadelphia_car_crime_report.pdf** – written report summarizing methods, findings, and conclusions
* **requirements.txt** – Python package dependencies

