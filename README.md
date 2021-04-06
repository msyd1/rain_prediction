# Rain Prediction Project 
### Project Description
This project is made for the purpose of  predicting whether it will rain next day or not.


### Installations
Main file is a Jupyter notebook;

To clone this repository:
```
$ git clone https://github.com/msyd1/rain_prediction.git
```
Or install requred libraries:

- pandas
- numpy
- seaborn
- sklearn
- plotly


### Overview

**Data Analysis**

Exploring the data we are working with for the project on predicting the probability of rain in Australia.
Based on the information available from the dataset, we will address following questions:
1. What is the month when there is the most rainfall in Australia? 
2. Which city or place  is the most and least rainy one?
3. How well can we predict rain the next day?


**Data Preprocessing**

Cleaning and transforming the dataset.
Includes:
- dealing with missing values by replacing them with the most common class and with median values:
- dealing with ouliers;
- creating dummy variables for machine learning models.

**Training Models**

Implementing machine learning models to make a prediction. 
Three models are implemented: logistic regression, decision tree and random forest. 

The blog post that describes the results of the analysis can be found [here](https://marynas.medium.com/in-search-for-a-heavy-rain-using-machine-learning-for-a-weather-prediction-8c4eda5ad051).

### Project Structure
```
- weather.csv               # data to process
- rain_prediction.ipynb     # Jupiter file

- README.md
```

### References

Young, J. (n.d.). Rain in Australia. *Kaggle*. Retrieved from https://www.kaggle.com/jsphyg/weather-dataset-rattle-package