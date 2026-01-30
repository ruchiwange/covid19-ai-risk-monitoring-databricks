## **About**

Community collected, cleaned and organized COVID-19 datasets about India sourced from different government websites which are freely available to all. Here we have digitized them, so it can be used by all the researchers and students.

# Infected Data 
### Column Discription

Main file in this dataset is `COVID-19_India_Data.csv ` and the detailed descriptions are below. 

    Date_reported : Date of the observation in YYYY-MM-DD
    cum_cases : Cumulative number of confirmed cases till that date
    cum_death : Cumulative number of deaths till that date
    cum_recovered : Cumulative number of recovered patients till that date
    new_recovered : Daily new recovery 
    new_cases : New confirmed cases. Calculated by:  current cum_cases - previous cum_case
    new_death : New confirmed deaths. Calculated by: current cum_death - previous cum_death
    cum_active_cases : Cumulative number of infected person till that date. Calculated by: cum_cases - cum_death - cum_recovered
   
  

# Vaccination data

## Column Discription

Main file in this dataset is `Vaccination.csv ` and the detailed descriptions are below. 

- `date`: date of the observation.
- `total_vaccinations`: total number of doses administered. For vaccines that require multiple doses, each individual dose is counted. If a person receives one dose of the vaccine, this metric goes up by 1. If they receive a second dose, it goes up by 1 again. If they receive a third/booster dose, it goes up by again.
- `people_vaccinated`: total number of people who received at least one vaccine dose. If a person receives the first dose of a 2-dose vaccine, this metric goes up by 1. If they receive the second dose, the metric stays the same.
- `people_fully_vaccinated`: total number of people who received all doses prescribed by the vaccination protocol. If a person receives the first dose of a 2-dose vaccine, this metric stays the same. If they receive the second dose, the metric goes up by 1.
- `daily_vaccinations_raw`: daily change in the total number of doses administered. It is only calculated for consecutive days. This is a raw measure provided for data checks and transparency, but we strongly recommend that any analysis on daily vaccination rates be conducted using daily_vaccinations instead.
- `daily_vaccinations`: new doses administered per day (7-day smoothed). For countries that don't report data on a daily basis, we assume that doses changed equally on a daily basis over any periods in which no data was reported. This produces a complete series of daily figures, which is then averaged over a rolling 7-day window. An example of how we perform this calculation can be found here.
- `total_vaccinations_per_hundred`: total_vaccinations per 100 people in the total population of the country.
- `people_vaccinated_per_hundred`: people_vaccinated per 100 people in the total population of the country.






# Acknowledgements

- [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19) for making the data available for educational and academic research purposes.
- World Health Organization (WHO): https://www.who.int/
- Government of India: https://www.mygov.in/covid-19,  Ministry of Health and Family Welfare: https://www.mohfw.gov.in/
- Our World in Data: https://ourworldindata.org/covid-vaccinations?country=~IND
- https://data.covid19india.org/
