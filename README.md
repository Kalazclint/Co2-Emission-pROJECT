# Co2-Emission-pROJECT
Problem Statement:
This project will address the challenge of accurately predicting CO2 emission and fuel economy in vehicles based on various features such as vehicle specifications, engine characteristics, and driving conditions. By leveraging machine learning techniques, we aim to build a robust model capable of estimating these metrics with a high degree of accuracy.

Dataset:
To accomplish this, a comprehensive dataset was collected from https://www.fueleconomy.gov/feg/ws/index.shtml#fuelType1, comprising vehicle-specific information, including engine displacement, transmission type, number of cylinders, fuel type,  and other relevant parameters.

Data Cleaning/Feature Engineering
The dataset was preprocessed to handle missing values, outliers, and categorical variables appropriately. Feature selection techniques, such as correlation analysis, was  employed to identify the most significant features affecting CO2 emission and fuel economy. 

Machine Learning Model:
The project employed supervised machine learning techniques, specifically regression algorithms, to develop the predictive model. Several machine learning algorithms were explored, including linear regression, decision trees, random forests, support vector machines, ExtreeRegressor and Artificial Neural networks. These algorithms were trained on the dataset to learn the relationships between the input features and the target variables (CO2 emission and fuel economy). Seperate machine learning models were developed each for co2 emission and fuel economy.

Model Evaluation:
The performance of the developed machine learning models were evaluated using  R-squared (R2) score.

Stratisfication
The training and test data data were stratisfied by the most important categorical variable and a seperate model was built. This is to avoid Bias in our model

Model Fine Tuning
All models were fine-tuned using Grid-search cross Validation to obtain the best Hyper parameters.
