---
layout: page
title: Final_project
permalink: /Final_project/
---

<div align="center">
  
<h1 style="font-size: 66px; font-weight: bold;">New york vehicle crashes</h1>

<h3 style="font-size: 48px; font-weight: bold;">A visualization story</h3>
</div>


 <font size="5"> The aim of this visualization story is to give readers an overview of crashes in Manhatten - NYC - from 2013-2022. Furthermore, we have also created a machine learning model that tries to predict wheter or not a person has been injured or killed in a crash. The usecase for this could be to register data and then alert nearby emergency rooms with a warning when a crash occurs. 

 The data is gathered from NYC open data platform and is based on the first responders initial gathering of data. We supplied that data with weather data from the local stations for each day represented in the dataset, and with information about the road lengths on which the crashes occurs. First, a plot of the crashes over the years is shown.</font> 


|  |  |
| --- | --- |
| ![Image description](/docs/assets/final/years.png) | <font size="5">It is easy to see that the crashes are more or less constant over the years, with two exceptions. In 2016 the crashes dropped significantly in April, and then COVID-19 hit in March 2020, leading to many fewer crashes, which has continued in the previous two years. The next thing to look for is the distribution of reasons for crashes.</font> |





|  |  |
| --- | --- |
|<font size ="5" >The plots shows that most of the crashes are labeled as unspecified, therefore this category will be removed to get a clearer view of the distribution of the crashes that actually has a category. </font> | ![Image description](/docs/assets/final/factor.png) |

<font size ="5" >The plot below shows the distribution for the top 14 factors over the years from 2013-2022. It is clear that some of the categories were removed over the years. We can see that turning improperly went down, and that all factors took a natural big drop during the covid years, with the exception of drivers disregarding traffic control, that seems to be steady throughout the years.  </font> 

<p align="center">
  <img src="/docs/assets/final/factoryear.png" alt="Image description" />
</p>

<font size ="5" >
The next plot shows the distribution for each of the focus factors throughout the 168 hours of the week. The most interessting takeaway from the plots are that the traffic control disregarded seems to be high on all hours of the week, meaning it is more comon for that to occur during the night than most of the other categories. We can also see that passing too closely goes down in the weekend, which might be because people are not as much in a hurry as they are on weekdays. Almost all of the categories peak on friday afternoon, probably because people want to go home. 
</font> 

<p align="center">
  <img src="/docs/assets/final/168hours.png" alt="Image description" />
</p>

<font size ="5" >
Next we want to explore the distribution of crashes troughout the different areas of manhatten for each factor. The plot shows that particularily the neighbourhood West Village, alot of the categories peak. This might be due to to the fact that the other areas sets the factor as unspecified, or simply that the area needs to apply changes for it to be more safe. In general there are less counts of crashes for almost all categories in the north of Manhatten. 
</font> 

<p align="center">
  <img src="/docs/assets/final/maps.png" alt="Image description" />
</p>


<font size="5">We wanted to look how rain affects the number of casualties. So this plot shows the crashes with casualties when it rains as the purple heatmap, and the red dots as the crashes with casualties when it does not rain

</font> 

{% include rainmap.html %} 


<font size="5">
A machine learning model was created, hoping that we could try to predict wheter or not a person was injured or killed in a crash. Application for this could be a warning system for the nearest emergency room, as they would be better prepared when an accident happens in their area. The first step was to examine the correlation between the variables in the dataset, and the result can be seen in the correlation matrix below. The variable does not correlate much, so the hopes for the model wasn't much. We decided to go with a randomforrestclassifier, and a variable indicating if a person was either injured or killed in the crash was added. The resulting model had an accuracy of 86%, and the confusion matrix shows the results that we had on the test set, which was 30% of the data. Not an impressive model result, but it was able to classify some of the crashes that had injuries or fatalities the right way.
</font> 


![Image description](/docs/assets/final/correlation.png)  

![Image description](/docs/assets/final/confusion.png) 

<font size="5"> 
Lastly we also wanted to include how the Alchohol involvement factor looked over the years, surprisingly there are not many records in the dataset where alcohol was the leading factor. The animation below shows the location of the vehicle crashes over the years on Manhatten. There doesn't seem to be a specific place where the alchohol incidents occur, but then again there are over 2000 bars in manhatten, so that would also be surprising. </font> 

{% include vehicle_crashes_map.html %} 