# Metis Project 1: MTA Data

### Project Proposal Template

Before you start project work for a course, you **should be able to complete the following proposal template**, addressing the questions listed as completely as possible. 
However, keep in mind that throughout the design iterations of your project, many parts of it will likely change 
(i.e. increase/decrease in number of samples, types of features or algorithm used, etc), so this is just a starting point.
Also, if you are unsure in some areas, you should still submit a partial proposal to receive feedback from instructors. 

In addition to submitting this plan, you may discuss the areas below with an instructor in a **scope meeting**.

#### Question/need:
* What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

How has use of the MTA changed in the last year compared to the previous year, and how does this correlate with data pertaining to the Covid-19 pandemic?

* Who benefits from exploring this question or building this model/system?

Both NYC Health and the MTA can use this data in the event of a pandemic in the future, to see when new cases and MTA usage may change based on each other.

#### Data Description:
* What dataset(s) do you plan to use, and how will you obtain the data?

This project will use the publically available MTA Turnstile data located at http://web.mta.info/developers/turnstile.html,
and will also use public nychealth Coronavirus data found at https://github.com/nychealth/coronavirus-data/.

* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 

Data can be analyzed on a day-to-day basis, including number of new cases, new deaths, etc.

* If modeling, what will you predict as your target?

Use of the MTA will likely negatively correlate with the number of new daily cases. This relationship may be staggered by 2 weeks as increased use of the MTA likely leads to further cases.

#### Tools:
* How do you intend to meet the tools requirement of the project? 
* Are you planning in advance to need or use additional tools beyond those required?

#### MVP Goal:
* What would a [minimum viable product (MVP)](./mvp.md) look like for this project?

Sample the same week of data from both 2020 and 2019, ideally from the peak period of Covid-19 cases, to show the negative correlation between cases and MTA usage.
