---
layout: page
title: Assignment 2
permalink: /A2/
---

# Introduction and motivations

According to the "Top 10 Countries with the Highest Number of Foreign-Born Residents (Immigrants) - United Nations 2020", the United States has by far the world's largest number of immigrants with over 50 million. This is nearly 4 times more than Germany which has the second-highest number of immigrants at 15 million.  

This article aims at helping San Francisco newcomers. We are employees of an immigration consulting company, mainly serving US immigration consulting. Our company has many groups, and we are the West Coast group, which mainly analyzes data from San Francisco. According to our survey, many clients have concerns about whether to immigrate to the United States because of the gun abuse and drug abuse reported in the news in recent years. Many clients have emphasized that the consideration of safety factors will be the primary factor when they choose which country to immigrate to. So it is very important for us to give our customers a rough understanding of the real data, rather than hearsay. It also serves as a significant reference when they decide whether to immigrate and which city to choose to settle in. The forms of crime that everyone cares about are different. Therefore customized services to tailor the distribution of crime forms in San Francisco for customers with special needs might be needed. This article gives a quick overview of the capabilities of data visualization. 

We will be working with a dataset obtained through "dataSF.org" called "Police Department Incident Reports Historical 2003 to May 2018" as a starting point. The dataset contains all 37 kinds of crime in San Francisco between 2003-2017, for example, 'Weapon laws', 'Prostitution', 'Driving under the influence', 'Robbery', 'Assault', 'Larceny/Theft' etc. covering 10 police districts.  


# Crime data visualization

First of all, we would like to first analyze the trend of the overall crime rate in the 14 years from 2003 to 2017, whether it shows an increasing trend or vice versa.

![Book logo](/docs/assets/timeseries.png)

From the plot above, we can have an overall understanding of the crime rate in San Francisco from 2003 to 2017. We can see it fluctuates during the period, the lowest amount was 9500 crimes in 2011, and the highest amount reached 13500 in 2015. But we could see a tendency from 2014 to 2017, it was slightly going down. So as a professional immigrant consulting team, we stay positive to pick San Francisco as a potential safe region.


Second, we want to see which neighborhoods have the lowest crime rates for different kinds of crime. We have looked at the top 10 crimes. If there is a neighborhood where many types of crime rates are the lowest, for example, the neighborhood ranked lowest crime rate for 5 times (5 out of 10 type crimes), then we consider this neighborhood to be the safest neighborhood. Furthermore, for this neighborhood, we also want to look at the distribution of other crimes. See if the crimes of the other kinds are all below average or vice versa.

{% include mapplot.html %}

From the map above, we can easily find out the neighborhood called 'Richmond' has the lowest total crime count of 98.399. The second lowest area is Park with 101.978. The third place is the neighborhood 'Taraval' with 131.197. From the data observed, we can easily tell the north-east side of San Francisco has a lower crime rate, which also means it's much safer compared to the rest neighborhood for the immigrant to choose their future residence. It provides a fundamental and instructional suggestion for immigrants. The map has also been filled with the locations of each police station within each district, that is the black dots. When hoovering the dots, the telephone number and addresses of the police stations are available. (Data was obtained at "dataSF.org")


{% include sf_crime_scatter_regression_final.html %}


This visualization aims to inform immigrants about the crime patterns in San Francisco. The scatter plot shows the total number of crimes recorded throughout the years from 2003-2017, while the linear regression line illustrates the trend of crime rates over time.

The plot displays the 10 most common crime categories in San Francisco, such as Larceny/Theft and Vehicle-Theft incidents, which are color-coded for easy identification. By hovering over the points on the plot, immigrants can see the specific number of crimes recorded for a particular year and the crime category.

 The slope of each regression line represents the change in the total number of crimes per year for that category. This information can help immigrants make informed decisions about when to visit or live in San Francisco. Ie. they can see that Vehicle-Theft has gone down over the years, but regular theft has gone up, so it might be safer to have a car now than 15 years ago, but theft (presumably of smaller items) is on the rise.

Overall, this visualization provides immigrants with valuable insights into the crime patterns in San Francisco, allowing them to make informed decisions to ensure their safety while living or traveling in the city.

Furthermore, the plot also shows that Larceny/Theft is by far the most reported crime, thus new citizens should be aware and be on the lookout for pickpockets. 



# Conclusion

In general, through the above three visualizations, we have a preliminary understanding of the crime rate in the San Francisco area. As professional immigration consultants, we provide our clients with useful information and can answer their queries. Through our professional opinions, we provided key help when they made decisions in the later stage. San Francisco has always been a very popular immigrant location and especially after the tech boom. The climate is pleasant, the city is highly developed, and people live very comfortably there. It is the core city of the Bay Area, as well as a cultural, commercial, and financial center. Through our analysis, we found that San Francisco in the Northwest region had lower overall crime rates. It is also safer compared to other neighbors. Among them, especially in the Richmond neighborhood, up to five forms of crime are ranked the lowest crime rate. Therefore, we suggest that our customers give priority to the Northeast region, especially Richmond when choosing their future residence.
