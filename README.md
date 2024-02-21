# COVID-19 Data Exploration

## Introduction
This repository contains SQL queries aimed at exploring COVID-19 data. The queries cover various aspects such as total cases, deaths, population statistics, vaccination rates, and more. Skills utilized include joins, common table expressions (CTEs), temporary tables, window functions, aggregate functions, and creating views.

## Data Source
The data used in these queries is sourced from the PortfolioProject database, specifically from tables named `CovidDeaths` and `CovidVaccinations`. These tables contain information on COVID-19 cases, deaths, vaccinations, populations, and other relevant data points.

## Queries
Below is a brief overview of the SQL queries included in this project:

- Query 1: Selects COVID-19 deaths data by continent.
- Query 2: Selects initial COVID-19 data including total cases, deaths, and population by location and date.
- Query 3: Calculates the death percentage based on total cases for locations containing the word "states".
- Query 4: Calculates the percentage of population infected with COVID-19 for each location and date.
- Query 5: Identifies countries with the highest infection rates compared to their populations.
- Query 6: Identifies countries with the highest death counts per population.
- Query 7: Shows continents with the highest death counts per population.
- Query 8: Provides global COVID-19 statistics including total cases, deaths, and death percentage.
- Query 9: Calculates the percentage of population that has received at least one COVID-19 vaccine dose.
- Query 10: Utilizes a common table expression (CTE) to calculate the percentage of population vaccinated.
- Query 11: Utilizes a temporary table to calculate the percentage of population vaccinated.
- Query 12: Creates a view to store data for later visualizations.

## Usage
You can run these SQL queries against your SQL database containing COVID-19 data to gain insights into various aspects of the pandemic. Feel free to modify the queries as needed for your analysis requirements.

## Acknowledgements
The data used in these queries is sourced from the PortfolioProject database. Special thanks to the creators and maintainers of the dataset for providing valuable insights into the COVID-19 pandemic.

