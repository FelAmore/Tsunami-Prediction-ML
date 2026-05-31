# Tsunami Prediction ML
To build an ideal tsunami prediction system, suitable datasets and machine learning algorithms are crucial to produce accurate predictions. For this testing, the machine learning techniques used are of supervised type, SVM, Random Forest Classifier, Decistion Tree, Classifier, XGB Classifier, Gradient Boosting Classifier, and Logistic Regression. However, given the supervised machine learning techniques available, some testings are required to figure out the best and least favorable machine learning to implement for the dataset. As a result, the purpose of this project is to determine the most and least suitable supervised machine-learning technique for our scraped dataset. This dataset was obtained from the Kaggle website, which allows users to search for datasets to use for educational purposes, collaboration with other data scientists and machine learning experts, and even competition purposes. The original dataset contains 20 columns in which after cleaning (dropped, renamed, and encoded) is left with 15 columns, namely, Year, Month, Day, Validity, Cause, Eq Magnitude, Country, Location, Latitude, Longitude, Max Water Height (m), Tsm Magnitude (Iida), Tsunami, ECountry, ELocation.

## Group Members
+ Felise Amore Pandiora 
+ Hilkia Kennan Latjandu 
+ Vania Agnes Djunaedy 

## Datasets Resources : 
+ https://www.kaggle.com/datasets/raulchavez89/tsunami?select=Tsunami.csv

## Directory
1. CSV folder : Contains the original dataset and the cleaned dataset
2. Machine Learning Results : Contains all testing results for each machine learning
3. Code.ipynb : Contains all the code
   - Datasets Info
   - EDA
   - Classification Report
   - Best Hyperparameter
   - Results of Using Best Parameters (Classification Report)
   - Confusion Matrix
   - Heatmap
   - ROC AUC
   - ROC AUC Graph
   - SHAP Values
   - Feature Importance
4. Correlation Heatmap.jpeg : the pearson correlation heatmap for our dataset
5. Tsunami.csv : Contains the datasets for our testings
