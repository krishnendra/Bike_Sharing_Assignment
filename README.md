# Bike Case Study

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- As mentioned above in the description
- Its a Linera Regression Model Assignment 
- Understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- day.csv is used as the dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model works with 13 features and 1 target variable 
- OLS Regression Results                            

| Variable         | value            | Variable           | Value     |
|------------------|------------------|--------------------|-----------|
| Dep. Variable:   | cnt              | R-squared          | 0.781     |
| Model            | OLS              | Adjusted R Squared | 0.775     |
| Method           | least Squares    | F Statistic        | 136.0     |
| Date             | Mon, 12 Dec 2022 | Prob (F statistic) | 4.04e-154 |
| Time             | 16:31:58         | Log-Likelihood:    | 425.72    |
| No. Observations | 510              | AIC                | -823.4    |
| Df Residuals     | 496              | BIC                | -764.2    |
| Df Model         | 13               |                    |           |
| Covariance Type  | non burst        |                    |           |


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python
    - numpy
    - pandas
    - sklearn
    - statsmodel   

 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Upgrad


## Contact
Created by [@krishnendra] - feel free to contact me!
