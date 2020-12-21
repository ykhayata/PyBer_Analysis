# PyBer Analysis

## Purpose of Project 

I have been given the task to analyze the company's ride-share data, using python's pandas, numpy, and matplotlib libraries. The goal is to point out the major differences in data between the three city types; rural, urban, and suburban. As we analyze the data, we are going to examine the different metrics that go into each city type, and how they compare to one another.

## Results 

We are tasked with creating a data frame that measures total rides per city type, total drivers per city type, total fares per city type, average fare per ride, and finally average fare per driver. With this information we came up with a ride-sharing summarry to send to Omar.  

![Image 12-20-20 at 8 22 PM](https://user-images.githubusercontent.com/74481469/102739182-3fd6c480-4301-11eb-8577-4689b8afcbd4.jpeg)

### Overview of City Types

Drivers are represented by the size of the bubbles, as fares are displayed on the y axis, and rides are displayed on the x axis.

![Fig1](https://user-images.githubusercontent.com/74481469/102739391-e4f19d00-4301-11eb-848d-1e3afab607a7.png)

### Ride Count Data

This Box-and-Whisker plot is broken down by rides per city by city type and total rides per city type. 

![Fig2](https://user-images.githubusercontent.com/74481469/102739486-28e4a200-4302-11eb-9cdf-59ef6fd7dd9b.png)

This Pie Chart below breaks down the percent of total rides by city type.

![Fig6](https://user-images.githubusercontent.com/74481469/102739638-82e56780-4302-11eb-9736-344b42487acd.png)

### Drivers per City Type 

Drivers per city by city type and total drivers per city type:

![Fig7](https://user-images.githubusercontent.com/74481469/102739724-c344e580-4302-11eb-91c3-25b25f22a2bc.png)

### Fares per City Type

![Fig5](https://user-images.githubusercontent.com/74481469/102739797-f25b5700-4302-11eb-93df-c1462d937223.png)

![PyBer_fare_summary](https://user-images.githubusercontent.com/74481469/102739828-0acb7180-4303-11eb-932d-c4411f9849ad.png)

## Summary 

There are certainly disparities among the city types after doing an in-depth analysis and our next step in the project is to adress these issues, and hopefully guide the CEO in the right direction.

### Recommendations

1) Rural cities consist of only 5% of total rides, 7% of total fares, and 2.6% of the total drivers. But surprisingly, we see that the average fare per ride and average fare per driver is higher than any other city type at $34.62 and $55.49 respectively. I would try and incentivize more drivers to go to these rural areas to better distribute the quantity of drivers, and in return provide them with a higher income per ride, compared to urban and suburban city types. 

2) Suburban city types, like rural, make up a small percentage of rides, fares, and drivers. They make up 26.3% of rides, 30.5% of fares, and 16.5% of drivers. We can also incentive urban drivers to work in suburban cities due to consistent wagers. Based on our data summary, 490 drivers averaged an earning of $39.50, which is significantly higher than the earnings in urban cities.

3) In urban city types, the average fare per ride is significantly lower than other city types, at $24.53. But, there is a significant overflow of drivers to rides. For ever ride, there is 1.48 drivers, much more than we will ever need. We should set a limit of drivers in urban cities, and branch them out to areas where they are more needed, such as rural and suburban cities.  
