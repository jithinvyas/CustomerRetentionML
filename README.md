# CustomerRetentionML

## Overview
This project focuses on predicting retail customer retention potential using various Machine Learning algorithms. 
The goal is to classify customers into high, medium, or low retention potential based on historical data and customer patterns.

ML algorithms used in this project are listed below:
1. Logistic Regression
2. K Nearest Neighbor
3. Support Vector Classifier
4. Decision Tree Classifer
5. Random Forest Classifier
6. Adaboost Classifer
The best performed model has been considered to implement the model on top of the dataset. (Random Forest)
The Jupyter Notebook also consists of Data Visualizations on - Customer Patterns, transactions etc. which helps the client in taking the required actions.

## About Data
- Target attribute : RetentionPotential
- Dataset Type: Imbalanced Data (Hence accuracy is not a good metric for model evaluation)

## Install Dependencies (if any)
- Python 3.x
- Have the following packages in requirements.txt file and run this pip command in command prompt--> ## ***pip install -r requirements.txt***
-   numpy
-   pandas
-   matplotlib
-   sklearn
-   imblearn
-   xgboost  (# Optional)

- **Additional things to try** :- cross validation score, random sampling, PCA, LDA etc.. for better imporovements in the model; 

## Contributing
If you'd like to contribute, please fork the repository and create a pull request. Feel free to raise issues or suggest improvements.
