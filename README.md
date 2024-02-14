# Project Name

Bike Sharing Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## General Information
BoomBikes, a US bike-sharing provider, aims to boost its revenue post-pandemic. To achieve this, they want to understand the factors influencing the demand for shared bikes in the American market. Specifically, they seek answers to the following questions:

* Which variables significantly predict bike demand?
* How well do these variables describe the demand for shared bikes?

This analysis will help BoomBikes tailor their services effectively and stand out in the market.


## Conclusions
Following logical conclusion can be derived from above equation if all external and internal variables are stable:

1. Temperature Impact:
    * The most critical factor influencing demand is temperature. With a coefficient of 0.600201, for every 1-degree change in temperature, demand increases by a factor of 0.600201 (temperature × 0.600201). Impact is mostly during hotter months (especially in June, July, and August)
2. Weather Conditions:
    * The second most important factor is Light Rain or Light Snow, with a coefficient of -0.289400. On days with light rain, demand is expected to decrease by 28.9%.
3. Annual Growth:
    * The third significant factor is the year, with a coefficient value of 0.238668.
4. Winter Demand:
    * The fourth most important factor is Winter, with a coefficient of 0.146575. This implies that demand is expected to increase by a factor of 0.146575 during the winter months (specifically September, October, November, and December).
5. Windspeed Impact:
    * The fifth most important variable is windspeed, with a coefficient of -0.099198. For every change in windspeed, demand is predicted to decrease by approximately 10%.


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- SKLearn
- Statsmodels


## Acknowledgements
- This project was inspired by live session of upGrad on EDA.
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform


## Contact
Created by [@samik0701]
