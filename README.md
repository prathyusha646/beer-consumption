# Beer consumption analysis, prediction

## Dataset used:
* The Kaggle dataset that uses Brazil user data is used
* It has one year data of beer consumption for that region

## Preprocessing:
* Cleaning null values and NaN
* Renaming columns (to English)
* Finding general statistics about consumption
* Converting the temperatures into float
* Grouping data based on month and date, add columns to dataset

## Train and Testing:
* Split: 80% of the data is used for training and 20% for testing in each month
* Correlation matrix says Max Temperature, Rainfall and Weekends are considerable features
* Linear Regression model used to train on dataset

## Testing and Visualization:
* Model accuraacy = 73%
* Different barplots and histograms describing the data are plotted