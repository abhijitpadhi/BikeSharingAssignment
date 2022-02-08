# Bike Sharing Project
> Anaysing the dips in the revenues due to the ongoing Corona pandemic of a bike sharing provider.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona 
pandemic.The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up 
with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and 
the economy restores to a healthy state.
- Bunilding a linear regression model.
- The company has gathered a large dataset on daily bike demands across the American market based on some factors. 
It wants to understand the factors on which the demand for these shared bikes depends.
Essentially, it wants to know:
    1) Which variables are significant in predicting the demand for shared bikes.
    2) How well those variables describe the bike demands.
    3) To identify the variables affecting bike count, e.g season, yr,month,holiday etc.
    4) To create a linear model that quantitatively relates bike counts(total rental bikes) 
    5) To know the accuracy of the model, i.e. how well these variables can predict bike counts.
- The data set with name "day.csv" is used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The linear regression model is significant due following points,
    1) Error terms are normally distributed.
    2) Probability distribution of the error has constant variance.
    3) Error values are statistically independent.
- The R-squared value for the train and test dataset is not more than 5%, therefore we can say that this is a good model.
- The Adj R-squared value for the train and test dataset is not more than 5%, therefore we can say that this is a good model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- numpy version	    : 1.20.3
- pandas version	: 1.3.4
- seaborn version	: 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by linear regression model
- This project was based on [Bike Sharing Demand]().


## Contact
Created by [@abhijitpadhi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
