# Major Findings in the EDA for Historical Air Quality: Project 1, Group 6

* We looked into Historical Air quality data in New Jersey over the last few decades.

### Github Participants:
* @jefferyb92 - Jeffrey Burgos
* @mariavpatino - Victoria Patiño 
* @jjjjjeb - Jamie Bruno
* @angievizca - Angelica Vizcaino
* ----------


## Project Proposal:

Our project is to compare air quality in New Jersey over the years. We will examine the relationships between Toxic Air Pollutants, where they have been found and trends in reported values ​​throughout the year and over the years that have been measured.

## Finding Data:
Process: Kaggle → Historical Air Quality → By US Environmental Protection Agency

## Overall Questions: 

1. What are some dangerous Toxic Air Pollutants to human's health? 
2. Can they befound in New Jersey?
3. Are the levels found in New Jersey dangerous?

## Data Source

* We used the Ambient Monitoring Archive of Hazardous Air Pollutants found at [EPA Toxics Data Archive](https://www3.epa.gov/ttn/amtic/toxdat.html#data)
* This had data on the following Hazardous Air Pollutants and  specific data on New Jersey
1. Benzene
2. Cadmium
3. Chromium
4. Toluene

### Risks of hazardous exposure to these pollutants results in the following effects as dependent on level of exposure:
1. Cancer, including lung, kidney, bone, stomach
2. Harm to the nervous system and brain
3. Birth defects
4. Irritation to the eyes, nose and throat
5. Coughing and wheezing
6. Impaired lung function
7. Harm to the cardiovascular system
8. Reduced fertility

# ANALYSIS OF ALL DATA SETS: BENZENE, TOLUENE, CHROMIUM, CADMIUM

* The benzene and toluene data sample results show the most similarities with high values before 1995 and high averages across all the years in Harrison and North Plainfield.  Because Toluene is used to produce Benzene and because both are used in the production of paint, perhaps there were a higher number of paint-producing factories in these locations. 
* 
* 
* 

# Toxic Pollutant Highlights

## Benzene

### How has the air quality changed overall over the course of the past 30 years?

The air quality in terms of Benzene specifically, was on the decline over the last 30 years for the most part. However, in the years 2015 and 2016, the amount of Benzene appeared to be on the rise in the areas that were observed, with the addition of Bayonne and Newark being observed in those years and not the years prior.


### What were the mean values for the air quality in specific cities?

In terms of specific cities, most were below 1 microgram per cubic meter, with the exceptions of Camden, Darby, Elizabeth, North Plainfield, and Harrison. North Plainfield and Harrison had the highest recorded mean values, having around 4 micrograms per cubic meters, and 3 micrograms per cubic meter respectively. Although the had the highest mean values, they had less than ten years of observational data, each having about 7 years, whereas others had more than 10 and some with more than 20 years of observational data.

### How had the air quality changed in cities with more than 10 years of observational data?

Of the cities that had more than 10 years of observational data, they pretty much all had a decline in how much Benzene was in the air over the years, albeit a year here or there that had a small spike. One of the cities that had the most significant improvements in terms of air quality was Camden, that had mean values of over 4 micrograms per cubic meters in 1990, to under 1 microgram per cubic meter in 2016. Elizabeth on the other hand, while improving in air quality over time, actually had an increase in Benzene in 2016, growing to about 1.5 micrograms per cubic meter, as opposed to being under 1 microgram per cubic meter the year prior.

### How do the cities compare over time?

In conclusion, over time pretty much all the cities have made efforts to reduce the amount of Benzene in the air, whether it be due tighter regulations from the government, or from less people smoking cigarettes and the like, with small exception of course. If things continue to go down this route, I’m sure most if not all the cities will be under 1 microgram per cubic meter, which while I can’t say with certainty is considered “safe” levels, is certainly much safer than the levels that were shown in the previous years.


## Cadmium:

EPA calculated an inhalation unit risk estimate of 1.8 × 10 -3 (µg/m 3 ) -1 . (0.0018 µg/m 3) (per day) [Ref](https://www.epa.gov/sites/production/files/2016-09/documents/cadmium-compounds.pdf
https://cfpub.epa.gov/ncea/iris/iris_documents/documents/subst/0141_summary.pdf#nameddest=cancerinhal)


### How has the average air quality in terms of toxins changed in the last 20 to 30 years overall in New Jersey?

According to the graph: “Chromium (microg/c3) by Year in NJ”, the air quality in terms of the presence of chromium toxin has been constant since 1991 mostly throughout the State of New Jersey (in cities where it has been measured). However, in 2007 and 2008, the levels of this toxin reached levels of concern for health in the cities of Little Ferry and especially Secaucus (based on the Air Quality Index (AQI) - Particulate matter).


### How had the air quality changed in cities with more than 10 years of observational data?

Over the years, all cities have shown a constant amount of chromium in the air (within healthy levels for the human being). This may be due to stricter government regulations to companies that have combustion and metal industry processes since these are the main sources that release this chemical element to the environment


### How do the cities compare over time?


In terms of specific cities, most were below 1 microgram per cubic meter, with the exception of Little Ferry and Secaucus. These cities showed the highest average values ​​reported, with levels above 35.5 during the years of 2007 and 2008, which according to the AQI - Particulate matter, are levels that would affect the population with serious health effects.


## Additional Observations for Cadmium

### What Years have more Risk of getting cancer?

Out of the 18 years studied in the data(from 2002 to 2016) by getting the mean values of each year for the state of New Jersey, the only years that were not at risk of getting cancer by inhaling more than 0.0018 µg/m 3 for 24 hours were 2006 to 2008 and 2013 to 2014 . We can see that the mean values fluctuate over the 18 years, and are not consistent and not steady. Which may represent a risk or uncertainty in the upcoming years.

### What Cities in NJ have the highest risk of getting cancer? have higher concentration of Risk Estimate by EPA 0.0018 µg/m 3) (per day)

By grouping the data by year and city, we can calculate the mean values, and extract the years and cities with mean values in µg/m 3 higher than EPA at Risk estimate of 0.0018 µg/m 3 (per day). We can see that the year of 2016 has the highest risk with the cities of Newark, Hopatcong, and Highland Park. Been Highland Park the City with the highest mean value and at higher risk with a mean value of 0.004366 µg/m 3 for 24 hours. Which represents a higher probability for this population of getting cancer by inhaling Cadmium with this values over the lifetime. 

### How has the air quality improved in areas that have had observations of 10 years or more?

For the Cadmium data the average air quality is not steady and fluctuates, but the last 3 years evaluated (204 to 2016) shows an increase of this toxins for the Cities of Camden, Highland Park, Elizabeth and Hopatcong, and and increase of last year evaluated (2016) for Newark and New Brunswick.


## Chromium 

### How has the air quality changed overall over the course of the past 30 years?


### What were the mean values for the air quality in specific cities?

Air quality with levels of health concern

Air Quality for Sensitive Groups

Unhealthy Air Quality

Very unhealthy Air Quality

Hazardous Air Quality



### How do the cities compare over time?


## Toluene

Toluene is added to gasoline, used to produce benzene, and used as a solvent.  Exposure to toluene may occur from breathing ambient or indoor air affected by such sources.  The central nervous system (CNS) is the primary target organ for toluene toxicity in both humans. CNS dysfunction and narcosis have been frequently observed in humans exposed to elevated airborne levels of toluene; symptoms include fatigue, sleepiness, headaches, and nausea with serious exposure causing swollen liver, congestion & hemorrhage of the lungs, and tubular kidney necrosis. Toluene has not been proven to be carcinogenic. (Source: epa.gov)

### Harmful Exposure Breakpoints in mg/m3:
* (National Institute of Occupational Safety & Health, Occupational Safety and Health Administration)
* Causing Death in 50% of Tested Subjects: 33,176 mg/m3 (rats) / 20,056 mg/m3 (mice)
* Immediately Dangerous to Life : 18,885 mg/m 
* Short Term Exposure Limit (15 Minute): 560 mg/m3
* Long Term Exposure Limit (8-10 Hours):  NIOSH: 375 mg/m3 / OSHA: 754 mg/m3 (?)


### How has the air quality changed overall over the course of the past 30 years

According to the Data Set, NJ’s Toluene air sampling values are trending downward and have overall reduced.

Fig 1: Toluene: The Yearly Average of all Testing Sites Combined






### Which cities suffered more from high levels of this pollutant overall?
* Harrison and North Plainfield have the highest mean across all the years. (Fig 2)
* When looking at the values please keep in mind: There were 18 Testing Sites for Toluene Sampling.  After CityPy these 18 sites were reduced to 13 sites: Data was combined from two sites in Elizabeth and three sites in Paterson. (Fig 3)  None of these averages reached hazardous levels.

Figure 2: Toluene Average Values over all timesets per city


Figure 3: Toluene Average Values over all timesets per Latitude



### A closer look:  Showing City Averages...
* There is a lack of data per city before 1995. Overall datasets per city are incomplete. The highest averages are registered before 1995.  Most pre-1995 testing sites ending tests completely. 
* Camden registered the highest average in 1991, with a downward trend until 2008. After a few years of no data 2013 sampling jumps with higher averages still up 2016.

Figure 4: Tracking Toluene Samples per City over the years


Figure 5: Toluene Sampling Averages for Cities with over 10 Years of Data

### … & Max Values over time: A look into the max values illustrates another story. 
* Here we see values over hazardous levels in Camden, Ewing, Harrison, Highland Park, New Brunswick, and Paterson. 
* * Where are solvent and paint industries located in NJ?
* * Did Rutgers facilities decide to paint their buildings in 2005 without notifying the Air Sampling Administrators (therefore skewing their entire data set) or was there some kind of chemical spill?

Figure 6: Max Value per Year over Time


Figure 7: Toluene Max Values, City Highlights



