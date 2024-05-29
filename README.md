# Boom Bikes Linear Regression Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Background
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

### Problem Statement
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

### Business Goal
- You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Data
- The data set is a csv file with the bike rentals data for the Boom Bikes.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The major steps included in the python notebook are data understanding, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set.
- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library.
- The R-squared value of the train set is 84.0% whereas the test set has a value of 80.8%. The adjusted R-squared value of train set is 83.6% whereas the test set has 78.7%. The difference in R^2 between train and test is 3.1% and the difference in adjusted R^2 between Train and test is 4.8% which is less than 5%. Hence, this suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

### Business Goals:
- A US bike-sharing provider BoomBikes can focus more on Temperature.
- We can see demand for bikes was more in 2019 than 2018, so just focus as there is increase in 2019 and might be facing dips in their revenues due to the ongoing Corona pandemic and by the time it reduces the things will be better.
- Can focus more on Summer & Winter season, August, September month, Weekends, Working days as they have good influence on bike rentals.
- We can see spring season has negative coefficients and negatively correlated to bike rentals. So we can give some offers there to increase the demand.
- Now seeing to weathersit variable, we have got negative coefficients for Mist +cloudy and Lightsnow weather. So, we can give some offers during this season.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.7.3
- seaborn - version 0.11.0
- statsmodels - version 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact
Created by [@lattalavijaysekhar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
