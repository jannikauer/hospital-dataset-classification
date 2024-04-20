# Predicting Patient Mortality in Hospitals
This project aims to develop classifiers to predict the likelihood of a patient expiring during their hospital stay. This project was purely done for practicing purposes and should not be used for real world usecases.

## Dataset:
The classification dataset consists of 47,181 instances of patients with data for 27 different attributes. Attributes include demographic information such as age and admit location, as well as various medical indicators. Attributes like marital status and ethnicity, which do not significantly contribute to predicting patient mortality, are subseqeuntly excluded from the analysis.

## Project Structure:
The first parts of the notebook is focused on data cleaning, transformation, and feature selection. It ensures that only relevant attributes are retained for model training, and that the data is formatted appropriately for machine learning algorithms.
After that I implemented several classification algorithms to predict patient mortality. Lastly, the models are used to classify unseen data of a kaggle challenge dataset.

## Preprocessing:
- Data Cleaning: Handling missing values, outliers, and inconsistencies.
- Feature Selection: Identifying attributes strongly correlated with patient mortality and removing irrelevant features.
- Data Transformation: Encoding categorical variables, normalizing numerical features, and preparing data for model training.

## Classification:
- Model Selection: Experimenting with multiple classification algorithms such as Random Forest, Support Vector Machines, and Gradient Boosting.
- Model Evaluation: Assessing model performance using metrics like accuracy, precision, recall, and F1-score. 
- Model Optimization: Experimenting with parameters to improve model performance and robustness. 




