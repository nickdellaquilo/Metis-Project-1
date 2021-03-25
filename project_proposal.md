# Metis Project 1: MTA Data

## Project Proposal

#### Question/need:
> What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

How has use of the MTA changed in the last year compared to the previous year, and how does this correlate with data pertaining to the Covid-19 pandemic?

> Who benefits from exploring this question or building this model/system?

Both the New York City Department of Health and the MTA can use this data in the event of a pandemic in the future, to see when new cases and MTA usage may change based on each other. 

#### Data Description:
> What dataset(s) do you plan to use, and how will you obtain the data?

This project will use the publically available MTA Turnstile data located at http://web.mta.info/developers/turnstile.html,
and public nychealth Covid-19 data found at https://github.com/nychealth/coronavirus-data/.

> What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 

The MTA turnstile data contains cumulative entries and exits from each turnstile at a station, updated every 4 hours. The Covid-19 data contains daily numbers for new cases, hospitilizations, and deaths, as well as 7-day averages for each of these categories. An individual sample of analysis in this project might compare how a high number of cases over 7 days, for example, reduces MTA usage.

#### Tools:
> How do you intend to meet the tools requirement of the project? 

I have already used SQLAlchemy and pandas to begin downloading and analyszing the data in the Jupyter notebook in this repository. I will later use the Python visualization libraries that we learn to create some data visualizations to show my findings.

> Are you planning in advance to need or use additional tools beyond those required?

I don't believe I will need any other tools than those required to complete the project. However, if I have the time to, I would like to try to use the Bokeh and/or Plotly Python libraries if they can add to the project.

#### MVP Goal:
> What would a [minimum viable product (MVP)](./mvp.md) look like for this project?

Sample the same week of data from both 2020 and 2019, ideally from the peak period of Covid-19 cases, to show the negative correlation between cases and MTA usage.
