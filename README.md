# Hyperparameter tuning for XGBoost in SageMaker
Jupyter Notebook that uses the 'used car prices' dataset to train a SageMaker XGBoost model capable of predicting the MSRP (Manufacturer's Suggested Retail Price). Deploys an unoptimised model and collects Key Performance Indicators (KPIs). Utilises SageMaker Hyperparameter Tuning Jobs to perform hyperparameter optimisation. Deploys the optimised model and collects Key Performance Indicators (KPIs).

- Steps:
    - Load the dataset
    - Perform Exploratory Data Analaysis (EDA)
    - Perform Data Visualisation
    - Split the data into training, validation and testing datasets
    - Prepare the data for SageMaker
    - Train an XG-Boost model using SageMaker
    - Deploy the unoptimised model and obtain KPI's
    - Perform Hyperparameter Tuning
    - Deploy the optimised model and obtain KPI's