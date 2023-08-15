# Bike Rental Case Study
> This case study involves understand the factors on which the demand for these shared bikes depends.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
<b>What is the background of your project?</b>

- A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

<b> What is the business problem that your project is trying to solve? </b>


- Understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.

- Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
  Which variables are significant in predicting the demand for shared bikes.
  How well those variables describe the bike demands

<b> What is the dataset that is being used? </b>

- [BikeSharing DataSet](day.csv)
- [Data Dictionary - Data attribute definition](Readme.txt)


## Conclusions
- "temp", "season_winter", "mnth_sept", "weekday_sat" have all positive coefficients which indicates increase in thier values will lead to increase in value of cnt.</b>
- "weekday_sun", "mnth_jul", "season_spring", "weathersit_moderate", "windspeed", "weathersit_bad" all have negetive coefficients which indicates decrease in their values will lead to decrease in value of cnt.
- Increase of temp, will result in more bike renting.
- More bikes are rented in the month of September.
- Bad weather will have a negative impact on bike rentals.
- More wind speed will have a negative impact on bike rentals.
- Spring season will have the least bike rentals.
- Winter season will have more bike rentals.


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn 
- statsmodels


## Contact
Created by [@arijeetsaha](https://github.com/arijeetsaha) - feel free to contact me!