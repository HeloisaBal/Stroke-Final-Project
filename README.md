# Stroke-Final-Project
### Purpose
This project is a descriptive analysis of data from the U.S Healthcare in 2022. It contains machine learning models for predicting the chances of getting a stroke with 99% accuracy scores.

### Source data
https://www.cdc.gov/brfss/annual_data/annual_2020.html
https://www.opendata.nhs.scot/dataset/scottish-stroke-statistics

### Documentation
Final Project - Stroke.ipynb draws insights from the data and testes the models.

Stroke - Presentation Results.pdf contains data visuals summarising the insights.

### Summary
Performed data cleaning and wrangling, going from 326 columns to 29 columns.
Oversampled the data in order to train the models.

I used MinMaxScaler, ordinal encoding and OneHotEncoder to build a different models to predict stroke in patients.
Decision Trees and Random Forests were the models returning the highest accuracy.

### Conclusions drawn
- Smoking and high BMI are highly related to having a stroke.
- Alcohol and lack of sleep are not correlated to having a stroke in the dataset patients.
- Patients above the age of 55 are more prone to having a stroke.
