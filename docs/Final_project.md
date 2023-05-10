---
layout: page
title: Final_project
permalink: /Final_project/
---

<div align="center">
  
<h1 style="font-size: 66px; font-weight: bold;">New york vehicle crashes</h1>

<h3 style="font-size: 48px; font-weight: bold;">A visualization story</h3>
</div>


 <font size="8"> The aim of this visualization story is to give readers an overview of crashes in Manhatten - NYC - from 2013-2022. Furthermore, we have also created a machine learning model that tries to predict wheter or not a person has been injured or killed in a crash. The usecase for this could be to register data and then alert nearby emergency rooms with a warning when a crash occurs. 

 The data is gathered from NYC open data platform and is based on the first responders initial gathering of data. We supplied that data with weather data from the local stations for each day represented in the dataset, and with information about the road lengths on which the crashes occurs. First, a plot of the crashes over the years is shown.</font> 


|  |  |
| --- | --- |
| ![Image description](/docs/assets/final/years.png) | <font size="8">It is easy to see that the crashes are more or less constant over the years, with two exceptions. In 2016 the crashes dropped significantly in April, and then COVID-19 hit in March 2020, leading to many fewer crashes, which has continued in the previous two years. The next thing to look for is the distribution of reasons for crashes.</font> |





|  |  |
| --- | --- |
|<font size ="8" >The plots shows that most of the crashes are labeled as unspecified, therefore this category will be removed to get a clearer view of the distribution of the crashes that actually has a category. </font> | ![Image description](/docs/assets/final/factor.png) |

<font size ="8" >The plot below shows the distribution for the top 14 factors over the years from 2013-2022. It is clear that some of the categories were removed over the years. We can see that turning improperly went down, and that all factors took a natural big drop during the covid years, with the exception of drivers disregarding traffic control, that seems to be steady throughout the years.  </font> 

![Image description](/docs/assets/final/factoryear.png) 
<font size ="8" >
The next plot shows the distribution for each of the focus factors throughout the 168 hours of the week. The most interessting takeaway from the plots are that the traffic control disregarded seems to be high on all hours of the week, meaning it is more comon for that to occur during the night than most of the other categories. We can also see that passing too closely goes down in the weekend, which might be because people are not as much in a hurry as they are on weekdays. Almost all of the categories peak on friday afternoon, probably because people want to go home. 
</font> 


![Image description](/docs/assets/final/168hours.png) 