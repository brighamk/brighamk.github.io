---
layout: post
title: "Summer Practicum Project: United States Mortality Trends"
date: 2019-10-31
---

  The goal of this project was to conduct a regional and time trend analysis of the most common causes of death in the United States. I collaborated with two other classmates to first collect and clean county level data of fifteen different death rates from the Center for Disease Control (CDC), shown in the picture below. 

![Image](https://github.com/brighamk/brighamk.github.io/blob/master/images/Picture2.png?raw=true)

  We collected the age adjusted death rates in 5 year intervals because if there were less than 20 deaths for a selected time period, the CDC reports the death rate as "Unreliable". Increasing the time period from one year to five year intervals resulted in less "Unreliable" data. We collected the death rates for 2009-2013, 2011-2015, and 2013-2017. When analyzing which death rates had the biggest change from 2009-2013 to 2013-2017, we found that the opioid death rates had the most significant increase in many counties in the east. 

![Image](https://github.com/brighamk/brighamk.github.io/blob/master/images/Picture4.png?raw=true)

  Next, we conducted principal component analysis in Python to reduce the original fifteen death rate features to seven principal components that retained 80% of the variation. Also in Python, K-Means cluster analysis was performed on the components to create six clusters of counties with similar death rates. To describe the clusters, we collected county level
demographic information from the U.S. Census Bureau and County Health Rankings and merged the data with the principal components. An analysis of the clusters was performed by computing the average of the death rates and demographic variables by cluster. We pulled out the variables that significantly differed from the other clusters in the graphic below and also used the averages of the death rates and demographics to give each cluster a title. 

![Image](https://github.com/brighamk/brighamk.github.io/blob/master/images/Picture5.png?raw=true)

The alluvial diagram below shows the movement of counties between clusters over the three time periods. 

![Image](https://github.com/brighamk/brighamk.github.io/blob/master/images/Picture6.png?raw=true)
