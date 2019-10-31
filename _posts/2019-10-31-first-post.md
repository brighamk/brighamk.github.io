---
layout: post
title: "Summer Practicum Project: United States Mortality Trends"
date: 2019-10-31
---

The goal of this project was conduct a regional and time trend analysis of the most common causes of death in the United States. I collaborated with two other classmates to first collect county level data of fifteen different death rates from the Center for Disease Control (CDC), shown in the picture below. 

![Image](https://github.com/brighamk/brighamk.github.io/blob/master/images/Picture2.png?raw=true)

We collected the age adjusted death rates in 5 year intervals. We collected the death rates in 5 year intervals is because if there were less than 20 deaths for a selected time period, the CDC reports the death rate as "Unreliable". Increasing the time period from one year to five year intervals resulted in less "Unreliable" data. We collected the death rates for 2009-2013, 2011-2015, and 2013-2017. 






We cleaned and merged this data with county level demographic information from the U.S. Census Bureau and County Health Rankings. Next, we conducted principal component analysis in Python to reduce the original fifteen death rate features to seven principal components that retained 80% of the variation. 
