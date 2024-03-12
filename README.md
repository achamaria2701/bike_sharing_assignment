# Bike Sharing
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
> The dataset contains total demand of bike for more than 700 days with 11 categorical and numerical features.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
- This is a problem solving excercise using multiple linear regression technique.
- The company wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands
- This analysis is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
- From the final model following categorical variable are relevant in predicting demand:
    - Positively correlated categorical variables are:
          - yr (Coeff: + 0.2515)      ## Year in which demand is being predicted
          - winter (Coeff: + 0.1359)    ## Season is summer or not
          - Sept (Coeff: + 0.0403)     ## Month is September or not
    - Negatively correlated categorical variables are:
          - holiday (Coeff: - 0.0810) ## weather day is a holiday or not
          - July (Coeff: - 0.0928)  ## Month is July or not
          - Cloudy (Coeff: - 0.0458) ## weathersit is 'Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist' or not
          - LRain (Coeff: - 0.2586)  ## weathersit is 'Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds' or not
- Adjusted R2-Score for the test dataset comes out to be 79.3%



## Contact
Created by [@achamaria2701] - feel free to contact me!
