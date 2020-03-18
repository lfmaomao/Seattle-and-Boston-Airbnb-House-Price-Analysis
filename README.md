# Seattle and Boston Airbnb Price Analysis

## Motivation

Airbnb is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences. Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way.


### Some of the business questions to be solved in this notebook:

#### Question 1: What factors affect the price of AirBnB rental?

#### Question 2: Is there any difference of the rental price between Seattle and Boston?

#### Question 3: Can we predict the Airbnb rental price using property information?

## Dataset
The dataset used in the project describes the listings in Seattle and Boston. The dataset can be found here: [1） Seattle Data](https://www.kaggle.com/airbnb/seattle) [2）Boston Data](https://www.kaggle.com/airbnb/boston)

## Installation

The build-in libraries from Anaconda needed to run this project include:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn


## Results

The main results from this project include:

Location does affect the rental price of Airbnb. Other factor that affect the rental price is the number of bedrooms, property type, and the square feet of the house. 

The median rental price is higher in Boston than Seattle. House and Apartment are the most popular propery types in Seattle while Apartment is the most popular propery type in Boston. 

I chose Seattle data to build a linear regression model and random forest regressor to predict the rental price. The R2 of linear regression model and random forest model is only 0.55, which is not good. We need more feature engineering in future works.


