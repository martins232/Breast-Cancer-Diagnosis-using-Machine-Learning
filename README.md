# Breast-Cancer-Diagnosis-using-Machine-Learning
# Introduction
Breast cancer is one of the most common types of cancer in women, and early detection is crucial for improving survival rates. In this project, The aim is to develop a machine learning model that can classify breast masses as benign (non-cancerous) or malignant (cancerous) based on features extracted from digital images.

# Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset, which is available on Kaggle (https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). The dataset consists of 569 samples and 30 features, and the target variable is a binary classification of the diagnosis (M = malignant, B = benign). The features in the dataset include measurements of the size and shape of the mass, as well as various texture and perimeter measurements.

# Methodology
To develop the machine learning model, I followed the following steps:

Data preprocessing: I performed basic data cleaning and preprocessing tasks, such as handling missing values and scaling the features.

Model training: I splitted the dataset into a training set and a test set, and trained several machine learning models using the training set. 

Model selection: I selected the model with the best performance on the training set and evaluated its performance on the test set.

Model evaluation: I then evaluated the performance of the final model using various evaluation metrics, such as accuracy, precision, and recall.

# Results
After training and evaluating several models, the Decision Tree classifier achieved the best performance on the test set, with an F1 score of [0.967]. I also found that the model had a high precision and recall for both classes (benign and malignant).

Conclusion
In this project, I developed a machine learning model for the task of breast cancer diagnosis based on digital image features. The model achieved high performance on the test set and has the potential to be used as a tool for assisting in the early detection of breast cancer.

Future Work
In the future, it would be interesting to explore other machine learning techniques, such as deep learning, for this task and compare their performance to the model developed in this project. It would also be valuable to incorporate additional data sources, such as patient history and demographic information, to further improve the performance of the model.

