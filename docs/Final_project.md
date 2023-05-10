---
layout: page
title: Final_project
permalink: /Final_project/
---

<div align="center">
  
<h1>New york vehicle crashes</h1>

<h3> A visualization story </h3>

</div>


 The aim of this visualization story is to give readers an overview of crashes in Manhatten - NYC - from 2013-2022. Furthermore, we have also created a machine learning model that tries to predict wheter or not a person has been injured or killed in a crash. The usecase for this could be to register data and then alert nearby emergency rooms with a warning when a crash occurs. 

 The data is gathered from NYC open data platform and is based on the first responders initial gathering of data. We supplied that data with weather data from the local stations for each day represented in the dataset, and with information about the road lengths on which the crashes occurs. First, a plot of the crashes over the years is shown.


|  |  |
| --- | --- |
| ![Image description](/docs/assets/final/years.png) | It is easy to see that the crashes are more or less constant over the years, with two exceptions. In 2016 the crashes dropped significantly in april, and then corona hit in march 2020, leading to much fewer crashes, which has continued in the previous two years. The next thing to look for is the distribution of reasons for crashes. |


|  |  |
| --- | --- |
|The plots shows that most of the crashes are labeled as unspecified, therefore this category will be removed to get a clearer view of the distribution of the crashes that actually has a category.  | ![Image description](/docs/assets/final/factor.png) |

The plot below shows the distribution for the top 14 factors over the years from 2013-2022. It is clear that some of the categories were removed over the years. We can see that turning improperly went down, and that all factors took a natural big drop during the covid years, with the exception of drivers disregarding traffic control, that seems to be steady throughout the years. 

![Image description](/docs/assets/final/factoryear.png) 