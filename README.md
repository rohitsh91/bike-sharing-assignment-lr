# bike-sharing-assignment-lr
Bike Sharing Assignment as part of Linear Regression Module in upGrad ML &amp; AL course from IIIT Bangalore

# Bike Sharing Assignment
This assignment we  have to build a multiple linear regression model for the prediction of demand for shared bikes.

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

### Business Goal:
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Technologies Used
- NumyPy, Pandas
- Matplotlib and Seaborne
- Sklearn, Statsmodels

## Conclusions
- #### Temperature:
  - Affecting the bike rental the maximum, A coefficient of (0.547216) indicates that a unit increase in temp variable increases the bike hire numbers
- #### windspeed:
  - A negative coeffcient of (-0.177210) indicating negative impact, which means with the increase in windspeed, people generally don't purchase bikes.
- #### year:
  - With increase in year [from 2018 to 2019], sales have increased, which implies positive impact, the coeff value is also: 0.236853
- #### weather:
  - a good weather with coeffient of 0.092103 implies weather affects the sale in positive manner, for good weather conditions, sales would increase

cnt = 0.038646 + yr(0.236853) + temp(0.547216) + windspeed(-0.177210) + season_summer(0.091523) + season_winter(0.119440) + mnth_sept(0.094638) + weathersit_good*(0.092103)  

##### It is recommended to give utmost importance to these variables while planning to achieve maximum bike rental booking  

## Contact
Created by [@rohitsh91] - feel free to contact me!
