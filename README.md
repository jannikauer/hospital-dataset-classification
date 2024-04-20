# Predicting Patient Mortality in Hospitals
This project aims to develop classifiers to predict whether or not a patient is likely to expire during their hospital stay based on information that is typically collected in hospitals. This project was purely done for practicing purposes and should not be used for real world usecases.

## Dataset
The classification dataset consists of 47,181 instances of patients with data for 27 different attributes. Attributes include demographic information such as age and admit location, as well as various medical indicators. Attributes like marital status and ethnicity, which do not significantly contribute to predicting patient mortality, are subseqeuntly excluded from the analysis.

## Project Structure
The first parts of the notebook is focused on data cleaning, transformation, and feature selection. It ensures that only relevant attributes are retained for model training, and that the data is formatted appropriately for the machine learning algorithms.
After that I implemented several classification algorithms that are able to classify a patient as either likely to "expired" or "not expire" during their hospital stay based on information collected during the hospital stay. Lastly, the models are used to classify unseen data of a kaggle challenge dataset.






