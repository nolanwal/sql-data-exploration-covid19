# COVID-19 Data Exploration with SQL

This project explores global COVID-19 data using SQL, analyzing infection rates, mortality, and vaccination progress across countries and continents.

## Dataset
- Source: [Our World in Data – COVID-19 Dataset](https://ourworldindata.org/covid-deaths)  
- Key fields: location, date, total_cases, total_deaths, population, new_vaccinations

## Skills & Tools
- SQL (T-SQL), Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, Converting Data Types
- Excel/CSV for data import

## Analyses Performed
1. Initial data review: countries, dates, cases, deaths, population  
2. Mortality analysis: death percentage per country  
3. Infection spread: percent of population infected  
4. Country-level aggregates: highest infection rate and death count  
5. Continent-level aggregates: death count by continent  
6. Global metrics: total cases, total deaths, global death percentage  
7. Vaccination analysis: rolling count of vaccinated individuals  
8. Views: `PercentPopulationVaccinated` for downstream visualization

## Key Insights
- Smaller countries had disproportionately high infection rates  
- U.S. and India recorded highest absolute cases  
- Europe and North America had the largest death totals  
- Vaccination rollout accelerated in 2021 but remained uneven globally
