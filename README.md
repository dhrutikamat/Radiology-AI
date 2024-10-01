# Radiology-AI
# Project Overview
This project uses a machine learning model to assist radiologists in determining whether a tumor is malignant or benign based on radiology data. Early and accurate diagnosis of tumors can greatly improve patient outcomes, and this project aims to support radiologists with an AI tool that can help differentiate between cancerous and non-cancerous tumors. The main objective of this project is to build a predictive model that can classify tumors as either malignant (cancerous) or benign (non-cancerous). Using machine learning, the model analyzes radiology data and provides predictions to assist radiologists in making informed decisions.

# Libraries Used
1. Pandas: For data manipulation and analysis.
2. Scikit-Learn: For building and evaluating machine learning models.
3. NumPy: For numerical computations.
4. Matplotlib / Seaborn: For visualizations and plotting.

# Model Overview
The project uses the following machine learning models to classify the tumors:
1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest Classifier

The dataset is split into training and testing sets, and the models are trained to maximize accuracy in distinguishing between the two classes.
The dataset used for this project is stored in a CSV file named cancer.csv. It contains features extracted from radiology images and a labeled diagnosis column:
1: Malignant (Cancerous)
0: Benign (Non-Cancerous)

# Model Accuracy
The model achieved the following accuracy scores on the test data:
● Logistic Regression: 95%
● Support Vector Machine (SVM): 96%
● Random Forest Classifier: 97%
