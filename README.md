# PandasGroup_JC_DS_AH_JKT_09_BSD_04_FinalProject
**BIKE-SHARING RENTAL**

![image](https://user-images.githubusercontent.com/71365164/126863487-26d9ad4d-1c1b-4c5d-b2fa-7b03d857c93b.png)


INTRODUCTION

Bike-sharing systems are a new generation of traditional bike rentals where the whole process from membership, rental and return back has become automatic. Through these systems, the user is able to easily rent a bike from a particular position and return back to another position. Today, there exists great interest in these systems due to their important role in traffic, environmental, and health issues.

Apart from interesting real-world applications of bike-sharing systems, the characteristics of data being generated by these systems make them attractive for the research. Having features such as duration of travel, departure, and arrival position, total bike number rented turns the bike-sharing system into a virtual sensor network that can be used for sensing mobility in the city. Hence, it is expected that the most important events in the city could be detected via monitoring these data.

Capital Bikeshare has more than 4300 bikes available at 500 stations across seven jurisdictions. With that number, Capital Bikeshare provides residents and visitors with a convenient, fun, and affordable transportation option for getting from point A to point B. People use Capital Bikeshare to commute to work or school, run errands, get to appointments or social engagements, and more.

OBJECTIVES

In this final project, we would gladly use this dataset from Capital Bikeshare to analyze and provide enhancement to their business. The bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions, precipitation, day of the week, season, an hour of the day, etc. can affect the rental behaviors. The core data set is related to the two-year historical log corresponding to the years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data.

We aggregated the data on an hourly basis, then extracted and added the corresponding weather and seasonal information. Weather information is extracted from http://www.freemeteo.com. We set our limitation on only one station Capital Bikeshare systems and focusing only on the number of bikes rented.

OUTPUT

We will create a model to predict the usage of the bike-share, in order for Capital Bikeshare to increase the efficiency of available bikes in Washington DC station. So they would not oversupply or undersupply the number of available bikes based on environmental and seasonal setting (for example during commute hours, holidays, or any weather condition)

MACHINE LEARNING TASK

This project will use supervised machine learning. Using regression to predict the total number of bike-share from the dataset.

PERFORMANCE MEASURE

In order to measure the performance of the regression model, we use the following metrics: R2 Score and Root Mean Squared Error (RMSE).

RISK

Our model has a chance to predict the wrong output for the bike-share unit supplied. As a result, there will be insufficient available bike-share units for customers at the station. Or, there will be a large number of unused bikes at the station, causing an increase in operational costs.

ACKNOWLEDGMENT

Hadi Fanaee-T Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto INESC Porto, Campus da FEUP Rua Dr. Roberto Frias, 378 4200 - 465 Porto, Portugal

Original Source: http://capitalbikeshare.com/system-data

Weather Information: http://www.freemeteo.com

Holiday Schedule: http://dchr.dc.gov/page/holiday-schedule
