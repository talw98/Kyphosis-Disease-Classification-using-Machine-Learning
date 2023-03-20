# Kyphosis-Disease-Classification-using-Machine-Learning
*Predicting whether a patient has Kyphosis using Decision Trees and Random Forest Classifier.*

# Background:

Kyphosis is a spinal disorder that causes an abnormal rounding of the upper back due to excessive curvature of the spine. It is commonly observed in adolescents and can cause discomfort, pain, and difficulty in breathing. Therefore, it is crucial to diagnose this condition early on to prevent its progression and provide appropriate treatment. One approach to early diagnosis is to use machine learning techniques, specifically decision trees and random forest classifiers, to predict whether a patient has kyphosis based on given features and diagnostic measurements.

# Dataset:

The Kyphosis dataset used in this project is obtained from [Kaggle]((https://www.kaggle.com/datasets/abbasit/kyphosis-dataset) and contains information about children who had corrective spinal surgery. It includes four columns: **Age**, **Number**, **Start**, and **Kyphosis**. The Age column represents the age of the patient in months, the Number column represents the number of vertebrae involved in the surgery, the Start column represents the number of the topmost vertebra operated on, and the Kyphosis column represents a binary variable indicating the presence or absence of kyphosis after the operation.

# Data Pre-processing:

To preprocess the data, the categorical data in the Kyphosis column is converted to numerical data using the label encoder. The dataset is then split into input features (X) and output (y) using the train_test_split() method. The necessary libraries such as pandas, numpy, matplotlib, seaborn, scikit-learn, and jupyterthemes are imported to work with the dataset.

# Model Training:

The machine learning model in this project uses Decision Trees and a Random Forest classifier to predict whether a patient has kyphosis or not. The model is created by training algorithms with labeled data. The training and testing datasets are prepared using the train_test_split() method. The dataset is then fed into the model to adjust its weights until it has been fitted appropriately.

# Conclusion:

In conclusion, this project provides a comprehensive overview of the Kyphosis dataset, visualizes the data, and prepares the data for training and testing. The machine learning model based on decision trees and random forest classifiers can predict whether a patient has kyphosis or not. This approach may assist medical professionals in diagnosing kyphosis early and providing the necessary treatment.
