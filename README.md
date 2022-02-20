# Bikesharing
Module 14: NY Citibike with Tableau

## Overview
To create a set of reports, dashboard and a *Tableau* story to convince investors that a bike-sharing program in Des Moines is a solid business proposal, also to create a bike trip analysis so we can solidify the proposal.


![Logo](/Images/Citi_Bike_logo.svg)



## Tableau Public Site
You can find the final __*Tableau Story*__ by [clicking here](https://public.tableau.com/app/profile/david.g.gonzalez/viz/NYCCitibikeChallenge_16453766948090/Module14ChallengeTableau?publish=yes)


## Resources
* Data Source: We used an August 2019 csv file downloaded from citi bike public data repository.

* Language:
  - Python

* Development tools: 
  - Visual Code 1.62.3
  - Jupyter Notebook
  - Tableau Public


## Process
* Transform tripdutration field from int64 to Date/Time
* Create several Tableau worksheets
* Create a story
* Write analysis



![Data Transformation](/Images/dataframe_to_csv.png)


![Final Tableau Story](/Images/Story.png)



## Analysis
* There were __2,344,244__ rides during the month of August 2019
* The highest number of rides were performed by subscribers with __1,900,359__ rides.
* There were more Male than Female riders with __1,530,272__.
* An age distribution table showed that the highes number of rides was done by subscribers with an *age* between *20 and 30* years old.
* The highest lenght in minute for a ride was around __5 minutes__ for *males* and __6 minutes__ for *females*. 
* We found pick hours between __8__ and __9 am__, then between __5__ and __7 pm__, __Thursdays__ are the *busiest* weekdays.
