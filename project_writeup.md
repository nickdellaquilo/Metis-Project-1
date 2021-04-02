# MTA Usage and Covid-19 Case Rate
Nicholas Dell'Aquilo

## Abstract
The goal of this project was to perform an exploratary data analysis (EDA) on the usage of the MTA in New York City. I worked with data provided by the MTA, as well as data provided by NYC Health, using data pertaining to new daily cases and cumulative MTA turnstile entries. I cleaned and converted the MTA data into a format representing new daily entries across the entire city, and used it to create a comparative visualization of MTA usage and Covid-19 cases over the same period of time.

## Design
The project uses the MTA's [turnstile data](http://web.mta.info/developers/turnstile.html), and New York City's Health Department's [Coronavirus data](https://github.com/nychealth/coronavirus-data/). 

## Data
The MTA turnstile data contains cumulative entries and exits from each turnstile at a station, updated every 4 hours. The Covid-19 data contains daily numbers for new cases, hospitilizations, and deaths, as well as 7-day averages for each of these categories. An individual sample of analysis in this project might compare how a high number of cases over 7 days, for example, reduces MTA usage.

## Tools
* Python for data ingestion
* Pandas for data manipulation
* Matplotlib for data plotting

## Communication
I have provided a [slidehow](https://github.com/nickdellaquilo/Metis-Project-1/blob/main/mta_slides.pdf) to present my findings.
![image](https://user-images.githubusercontent.com/22899761/113425044-2c76d300-939f-11eb-815f-a1d208f41e26.png)
