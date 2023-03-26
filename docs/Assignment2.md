---
layout: page
title: Assignment 2
permalink: /A2/
---

# Introduction and motivations

According to the "Top 10 Countries with the Highest Number of Foreign-Born Residents (Immigrants) - United Nations 2020", the United States has by far the world's largest number of immigrants with over 50 million. This is nearly 4 times more than Germany which has the second highest number of immigrants at 15 million. 

That's why we can survive in this tough market. We are employees of an immigration consulting company, mainly serving US immigration consulting. Our company has many groups, and we are the West Coast group, which mainly analyzes data from San Francisco. According to our survey, many clients have concerns about whether to immigrate to the United States because of the gun abuse and drug abuse reported in the news in recent years.Many clients have emphasized that the consideration of safety factors will be the primary factor when they choose which country to immigrate to. So it is very important for us to give our customers a rough understanding of the real data, rather than hearsay. It also serves as a significant reference when they decide whether to immigrate or which city to choose to settle in San Francisco.And the forms of crime that everyone cares about are different. We can also provide customized services to tailor the distribution of crime forms in San Francisco for customers with special needs.

We will be working with dataset obtained through "dataSF.org" called "Police Department Incident Reports Historical 2003 to May 2018" as a starting point. The dataset contains all 37 kinds of crime in San Francisco between 2003-2017, for example 'Weapon laws', 'Prostitution', 'Driving under the influence', 'Robbery', 'Assault', 'Larceny/Theft' etc. covering in 10 areas. 


# Crime data visualization

First of all, we would like to first analyze the trend of the overall crime rate in the 14 years from 2003 to 2017, whether it shows an increasing trend or vice versa, and which kind of crime has the highest crime rate.

#![Book logo](/docs/assets/timeseries.png)

From the plot above, we can have a overall understanding of the crime rate of San Francisco from 2003 to 2017. We can see it fluctuate during the period, the lowest amount reached to 9500 crimes in 2011, the highest amount reached 13500 in 2015. But we could see a tendency from 2014 to 2017, it was slightly going down. So as a professional immigrant consualtanting team, we stay positive to pick San Francisco as a potential immigrant region.


Second, we want to see which neighborhood have the lowest crime rates for different kinds of crime. We have taken a look for the top 10 crimes. If there is a neighborhood where many types of crime rates are the lowest, for example, the neighborhood ranked lowest crime rate for 5 times (5 out of 10 type crimes), then we consider this neighborhood to be the safest neighborhood. Furthermore, for this neighborhood, we also want to look at the distribution of other crimes. See if the crimes of the other kinds are all below average or vice versa.

![Book logo](/docs/assets/mapplot.png)

From the map above, we can easily find out the neighborhood called 'Richmond' has the lowest total crime count is 98,399,000. The second lowest area is neighborhood 'Park'with 101,978,000. The second place is neighborhood 'Taraval' with 131,197,000. From the data observed, we can easily tell the north-east side of San Francisco has lower crime rate, it also means it's much safer compared to the rest neighborhood for the immigrant to choose their future residence. It's provide a fundamental and instructional suggestion for the immigrants.


After taking a look at the overall crime rate of San Francisco, we want to further have a check the particular crime amount that happens in these safe neighborhoods that we mentioned above (Richmond, Par, Taraval), especially Richmond. We would investigate for the reason why the overall criminal act is low. For these ten different crime type, how frequency of Richmond ranked the lowest crime rate.

From the top 10 crimes categories above, it is obviou to conclude that Richmond has the lowest crime rate for 'OTHER OFFENSES',  'NON-CRIMINAL', 'ASSAULT','DRUG/NARCOTIC' and 'WARRANTS', which is 5 out of 10. Regarding the rest of 5 which Richmond is not ranked the lowest crimes, Richmond's ranking is also remain competitive. It ranked around 2rd or 3th place among these 10 neighborhoods. So after access the crime particularly, Richmond is the most safe neighborhood by investigation. We believe that the type of crime that everyone, or every new immigrant pays attention to is not the same. For example, if this person does not buy a car, he or she will not care about the low-risk neighborhood of vehicle theft rate. Or if some immigrants are non-white, they will pay more attention to which neighborhood is less prone to crimes related to racial discrimination, and they will be more likely to choose housing in these neighborhood.



{% include map.html %}