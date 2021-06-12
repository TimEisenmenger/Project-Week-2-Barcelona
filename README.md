<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Air Quality Barcelona
*TimKimLau*

*Ironhack Data Analytics - May 2021*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description

In this project we, *Tim, Kim and Laura,* performed an analysis on a dataset with information about the air quality of Barcelona in November 2018. 
It is intereseting to dive into Barcelona's pollution data, being a really turistic city but not as populated as other Eruopean citites, we might if it follows the Eruopen standard of pollution.
We must consider the limitations of the analysis and interpretation of the results as we just work with data from one month of one year. 


## Questions & Hypotheses

In this projects we have consider those questions to understand how is the quality of the air in Barcelona, after looking at the data available in our initial data set.

Which is the most polluted day of the month?
Which is the most polluted day of the week?
Which is the most polluted hour of the day?
Which station is the most polluted?
Which station has the best air quality?
Are there any realationship between polutants?

Hypotheses

We had already assumptions on what we could find. We expect to find more pollution during the week an on rush hours, in more centric areas in the city. 
As well as find days/hours above the stablish recommended pollution concetration when there there is more traffic. The weather conditions can also affect the quality of the air, but we don't have data about that neither of traffic.
We expected to notice relationship between pollutants as they interact together in the air.



## Dataset

Air Quality of Barcelona in November 2018 (source:https://opendata-ajuntament.barcelona.cat/)

Measures of concentration for:
- Nitrogen Dioxide (NO2)
- Tropospheric Ozone (O3) 
- Particulate Matter (PM10)

Measured for different 8 meteorological stations: Palau Reial, Sants, Poblenou, Vall d’Hebron, L’Eixample, Gràcia, Ciutadella i Observatori Fabra. 
The records are taken every day and every hour.
Those hourly records are categorized as good or moderate depending on the degree of pollution (according to WHO and 2008/50/CE).

In this link the is information about those 8 stations, that at this moment, are already 11.
(https://ajuntament.barcelona.cat/qualitataire/es/qualitat-de-laire/com-es-lluita-contra-la-contaminacio/la-red-de-vigilancia-y-prevision-de-la)




## Database

On our data base we include three tables:

Table 1: air-quality-nov-2018.csv (raw data)
Table 2: air_quality_bcn_18_clean (cleaned data)
Table 3: station_locations.csv (subset of the original data set with information about the GPS coodinates of each of the stations)

## Workflow

The workflow of this project was very agile. 
We pick the topic of interest and brainstorm questions, making assumptions before going into the data without previous knowledge. After we created the rough organization and the steps to take in the project and documented them in Trello.
Following, the data was cleaned, re-structure and observed in detail.
We gain the first insights with the previous step and helping us to redirect our analysis approach and be more concrete with the questions that we brainstorm at the beginning. At this point, the questions were divided within the team, and we started coding to find interesting highlight without performing complex analysis or even graphs.
With the information we got from the analysis, we tried to see if our hypothesis/assumptions were supported by the data.


## Organization

For the organization of this project, we used a board on Trello.
Tim created a repository and gave Laura and Kim access as contributors. Following, we created branches of the main branch in the repository, for each team member. We all work in our own branch and finally merge them with the main to have a definitive, unique version.

To make it easy to navigate through the project here there is a small description of the folder and files  that you will find in the repository.
Main folder:your-project
			sub-folder: data (with the three tables of our database, more info on Databse Section of this Read.me)
			Four jupyter notebook files: 
			- DATA_CLEANING- Quality air in BCN nov18.ipynb (The whole process of the data cleaning and data tranformation)
			- ANALYSIS_POLLUTANTS -Quality air in BCN nov18.ipynb (Analysis to understand the values of the pollutants and their relationship)		 
			- ANALYSIS_PEAKS- Quality air in BCN nov18.ipynb (Analysis to find weekly, monthly and hourly peaks of pollution)
			- ANALYSIS_BESTSTATIONS- Quality air in BCN nov18.ipynb (Analysis to find the stations with best and worst air quality)

## Links
Links to our...

[Repository](https://github.com/TimEisenmenger/Project-Week-2-Barcelona)  
[Slides](https://docs.google.com/presentation/d/1vvP2H66x_Rild6tgr51jbMLzqhka86k5nCL3I2n5KgI/edit?usp=sharing)  
[Trello](https://trello.com/b/SlZB3v2Q/timkimlauprojects2)  
