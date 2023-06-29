# Credit Card Fraud Detection
source: www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Steps of Content
* Exploratory Data Analysis
* Skewed columns
* Train Test Split
* Scaled data sets
* Base models 
* Random oversampling
* Tomek links
* Edited Nearest Neighbours
* Neighbourhood Cleaning Rule
* Neas Miss
* Under sampling mothod comparison
* Feature Importance
* Modeling with less number of features

# Algorithms that used in modeling stages
- Logistic Regression
- KNN Classifier
- Random Forest Classifier
- XGBoost Classifier
- LightGBM Classifier
- Decision Tree Classifier
- Cat Boost Classifier
- Gradient Boosting Classifier

# Application Process
Firstly, base models were tried with the specified algorithms. 
Than, undersampling methods were tried with models that have high recall, precision, f1 scores. 
Threshold values were adjusted for more balanced recall, precision, f1 score results
The undersampling methods that applied were compared
The skewed features data was used with Random Forest Classifier algorithm and most important features identified
Finally, a new random forest model was tried with the identified features that used with random undersampling method.
