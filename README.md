# Project Name
> Outline a brief description of your project.


## Table of Contents
* [Problem Statment ](#problem-statment)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 




## Technologies Used
Pandas Version : 1.3.4
Numpy  Version : 1.20.3
Seaborn Version : 0.11.2
Matplotlib Version : 3.4.3
StatModel Version : 0.12.2


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
F Statistics F-Statistics is used for testing the overall significance of the Model: Higher the F-Statistics, more significant the Model is.

F-statistic: 257.6 Prob (F-statistic): 1.99e-181 The F-Statistics value of 257.6 (which is greater than 1) and the p-value of '~0.0000' states that the overall model is significant

The equation of best fitted surface based on model : ( see the above coefficient table ) cnt = 0.070264 + (yr × 0.231263) - (holiday × 0.100177) − (temp ×0.539040) + (season2 × 0.080930) + (season4 × 0.297362) − (weathersit2 × 0.080930) − (weathersit3 × 0.297362) + (mnth_8 x 0.058455) + (mnth_9 x 0.123609)

Below are the coefficient of the final model
yr              0.231263
holiday         0.100177
temp            0.539040
season_2        0.095578
season_4        0.146153
weathersit_2    -0.080930
weathersit_3    -0.297362
mnth_8          0.058455
mnth_9          0.123609

The Top 3 contributors are 
        1. Temperature (0.539) (positive impact )<br>
        2. Weathersit_3( Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)  (-0.298) [ negative impact ] <br>
        3. year (0.231 ) positive impact ) <br>


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
