Datasets used: https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022?select=Base.csv
https://www.kaggle.com/datasets/ammaraahmad/top-10-machine-learning-datasets?select=cell_samples.csv


Fraud Detection with ML Classification Models
This project aims to predict fraud using various machine learning models and classification techniques. It includes data preprocessing steps, feature engineering, and the implementation of multiple algorithms to compare performance.

Table of Contents
Overview
Installation
Data Preprocessing
Modeling and Classification
Results
Contributing
License
Overview
Fraud detection is a critical issue in the financial domain, and this project focuses on building predictive models to classify transactions as fraudulent or legitimate. We use a dataset that includes features such as income, payment type, housing status, and customer age. The goal is to preprocess the data, handle class imbalance, and apply classification techniques to achieve high accuracy.

Installation
To run the project, you need to install the required Python libraries. You can install them using:

bash
Copy code
Libraries used
imbalanced-learn
pandas
scikit-learn
Data Preprocessing
Categorical Variable Encoding: Columns like payment_type and housing_status are mapped to numerical values.
Example: payment_type = {'AA': 0, 'AB': 1, 'AC': 2, 'AD': 3, 'AE': 4}
Handling Missing Values: Ensure all missing data points are handled appropriately.
SMOTE: Synthetic Minority Over-sampling Technique (SMOTE) is applied to handle class imbalance in the dataset.
Modeling and Classification
The following machine learning models are implemented and compared:

Logistic Regression
Decision Trees
Random Forest
Support Vector Machine (SVM)
LSTM (Long Short-Term Memory)
Each model is evaluated based on metrics like accuracy, precision, recall, and F1-score.

Results
Performance comparisons between models are made using various metrics. The model with the highest precision and recall is chosen as the final model for fraud detection.

Contributing
Feel free to open issues or submit pull requests for improvements.

License
This project is licensed under the MIT License.
