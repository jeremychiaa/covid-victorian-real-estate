# covid-victorian-real-estate
## The impacts of Covid-19 cases upon real estate sales in Victoria
### The big question
- Have the numbers of Covid 19 cases in the most popular Local Government Area changed their popularity for homeowners?
- Hypothesis: High Covid 19 cases in the most popular Local Government Area will reduce their popularity

### The working questions
1. What are the three most popular Local Government Areas in Victoria before March 2020?

2. What are the factors that contribute to this popularity?

3. How has the popularity of the top 3 LGAs in Victoria changed after March 2020?

4. Does the number of Covid 19 cases from March to June 2020 in each LGA contribute to its popularity?

### Data Collection
Real Estate data
Kaggle
- https://www.kaggle.com/htagholdings/aus real estate sales march 2019 to april2020

Covid 19 Data
DHHS Website
- https://www.dhhs.vic.gov.au/victorian-coronavirus-covid-19-data

School data & Hospital data
Victorian Government Data Directory
- https://discover.data.vic.gov.au/dataset/school-locations-time-series
- https://discover.data.vic.gov.au/dataset/hospital-locations-spatial

### Findings & Conclusion & Implications
#### Before Covid (September 2018 - January 2020)
- The top 3 LGAs are: Stonnington (1), Bayside (2), Monash (3)
- Hospitals : 8% of the house price can be explained by the number of hospitals
- Schools : The more schools there are, the higher the total number of sales is in a Local Government area.

#### After Covid (February - July 2020)
- Stonnington : 23% (Most Covid cases in April, second most in May until mid June)
- Bayside : + 3.6% (Next to Stonnington, with an average number of Covid cases)
- Monash : 9.9% (Top 5 Covid cases in early April, top 15 Covid cases until mid June)

### Notebooks
- property_pre_covid_analysis.ipynb: analysis of change in house price per LGA before Feb 2020
- property_during_covid_analysis.ipynb: analysis of number of properties sold per LGA after Feb to July 2020
- hospitals_analysis.ipynb: analysis of house price vs hospital count per LGA
- schools_analysis.ipynb: analysis of house price vs schools count per LGA