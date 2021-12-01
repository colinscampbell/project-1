**Project Title:**
COVID-19's Impact on US Travel Behavior

**Team Members:**
Colin Campbell
Prina Thaker
Etienne Dembele
Mandakini Majumdar

**Project Description:**
We will be looking at the impact of CDC reported cases, deaths, and vaccination rates on travel behavior in the US, by state. We will look at how the progress of COVID-19 impacted the type, quantity, and frequency of travel beahvior. We will also estimate whether this change in travel behavior appears to be permanent.

**Research Questions:**
- How quickly did people return to normal pre-COVID travel patterns after achieving certain vaccination thresholds?
- How much did case rates impact inbound / outbound travel volume (people visiting states vs. leaving COVID-19 hotbeds)
- TBD
- TBD


Datasets:
- CDC COVID Dataset (time series of cases, deaths, etc. by state and metro area)
- Travel Dataset TBD

1. Load data

Data Source:

· 1.United States COVID-19 Cases and Deaths by State over Time o Link : https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36

o API Endpoint : https://data.cdc.gov/resource/9mfq-cb36.json · https://data.cdc.gov/resource/9mfq-cb36.csv

2. Trips by Distance : Link: https://data.bts.gov/Research-and-Statistics/Trips-by-Distance/w96p-f2qv

API Endpoint : https://data.bts.gov/resource/w96p-f2qv.json https://data.bts.gov/resource/w96p-f2qv.csv

Description of Scope


· Merge Covid Case data frame with Travel data frame based on State and Dates (inner join)

· Plot correlation between cases and travel patterns (total travel, type of trips)

· Plot correlation between death and travel patterns (total travel, type of trips)

· Plot line trends of cases and travel patterns (total travel, type of trips) for given time series

· Plot line trends of deaths and travel patterns (total travel, type of trips) for given time series

· Provide case and travel pattern comparison between states

· Identify highest and lowest impacted states of travel impacts for Covid pandemic

· Use Google heatmap to show impacts by state using intensity numbers of impacts per million

(we can add more)

We can also enhance our scope of work with

1.State wise Vaccination data and Travel data

2.Covid data and unemployment data