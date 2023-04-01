Credit Card Fraud Detection
This repository contains a Jupyter Notebook that implements a machine learning model for detecting fraudulent credit card transactions. The dataset used in this project contains transactions made by European cardholders in September 2013.

The dataset is highly unbalanced, with only 0.172% of all transactions being fraudulent. To address this issue, we have used a combination of oversampling using SMOTE (Synthetic Minority Over-sampling Technique) and a weighted loss function to train our model. We have also used XGBoost, a popular gradient boosting algorithm, to build the model.

The notebook contains detailed explanations and code for performing data preprocessing, feature engineering, and model training. We have evaluated the performance of our model using various metrics like precision, recall, and F1 score.

In addition, we have also included visualizations to help understand the patterns in the data and the performance of our model.

We hope that this project can serve as a useful resource for anyone interested in building fraud detection models, and contribute towards preventing fraudulent credit card transactions.