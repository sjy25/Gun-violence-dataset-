# Overview
The U.S. has the 32nd-highest rate of deaths from gun violence in the world: 3.96 deaths per 100,000 people in 2019. That was nearly 100 times higher than in the United Kingdom, which had 0.04 deaths per 100,000.

On a state-by-state calculation, the rates can be even higher. In the District of Columbia, the rate is 18.5 per 100,000 — the highest in the United States (https://www.npr.org/sections/goatsandsoda/2021/03/24/980838151/gun-violence-deaths-how-the-u-s-compares-to-the-rest-of-the-world)

This notebook explores and analyzes the gun violence dataset, compiled by the Gun Violence Archive (GVA), a non-profit corporation formed in 2013. The questions that guided this analysis included:

(i)What has been the trend for gun violence incidents during this period (i.e. rising or falling trend?)
(ii) In terms of casualties, how deadly have such incidents been and whats the time trend
(ii)Do more incidents take place in certain states as well as certain physical locations?

### Dataset
This dataset comprises all recorded gun violence incidents in the US between January 2013 and March 2018, inclusive.Specificially, it describes 260k gun violence incidents, with information such as the state where the incident took place and the number of injured/fatalities. 
The dataset is avaliable on Kaggle(https://www.kaggle.com/jameslko/gun-violence-data).
 

### Findings

(i) There was a significant increase in the number of incidents between 2013 and 2014. this upward trend continued through 2018

(ii) After removing outliers, the mean number of casualties for 2014-2018 were comparable.The mean for 2013 was significantly higher

(iii) High schools, apartments, parks and bars were the among the most common places for gun violence incidents during this period 

(iv)Gun violence incidents during this period were fairly evenly spread across the  different states. However, incidents with >10  casualties were concentrated in certain states such as florida, texas and califonia 

### Future directions

For this dataset

(i) deeper analysis of the participant data e.g. are females more likely than males to be victims?are males more likely to be perpetrators of violent crimes?

Beyond this dataset

(i) Number of incidents per capita. It will be interesting to compare this to gun ownership per capita since the NRA has long argued that more guns make for a safer country. 

(ii) Gun laws for each state compared with the number of gun violence incidents. This project found that more violent incidents (>10 casualties) were concentrated in certain states such as florida and texas. Do these states have more lax gun laws? 

(iii) The profile of gun violence incidents, especially those that do not result in injury or death. It will be interesting to collect more data and see what are the associated factors for whether an incident results in injury or death e.g. time (day vs night),neighbourhood (median household income, unemployment rates)

(iv) The impact of the covid-19 pandemic on the number of gun violence incidents e.g. compared with 2019, were there more incidents in 2020 during the lockdown? While more people stayed home during this period, the pandemic affected employment and mental health. 
