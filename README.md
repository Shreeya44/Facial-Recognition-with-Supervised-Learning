# Facial Recognition with Supervised Learning

## Problem Statement:
You are a member of an elite group of data scientists, specialising in advanced facial recognition technology, this firm is dedicated to identifying and safeguarding prominent individuals from various spheres—ranging from entertainment and sports to politics and philanthropy. The team's mission is to deploy AI-driven solutions that can accurately distinguish between images of notable personalities and the general populace, enhancing the personal security of such high-profile individuals. You're to focus on Arnold Schwarzenegger, a figure whose accomplishments span from bodybuilding champion to Hollywood icon, and from philanthropist to the Governor of California. 

### **The Data**
The `data/lfw_arnie_nonarnie.csv` dataset contains processed facial image data derived from the "Labeled Faces in the Wild" (LFW) dataset, focusing specifically on images of Arnold Schwarzenegger and other individuals not identified as him. This dataset has been prepared to aid in the development and evaluation of facial recognition models. There are 40 images of Arnold Schwarzenegger and 150 of other people.

| Column Name | Description |
|-------------|-------------|
| PC1, PC2, ... PCN | Principal components from PCA, capturing key image features. |
| Label | Binary indicator: `1` for Arnold Schwarzenegger, `0` for others. |

## Key Features
#### Class Imbalance Handling: 
Utilizes SMOTE (Synthetic Minority Oversampling Technique) to balance the dataset.
#### Model Selection:
Employs Random Forest Classifier for robust and interpretable predictions.
#### Hyperparameter Optimization:
Implements GridSearchCV to find the best model configuration.
#### Pipeline Integration:
Combines preprocessing and model training into a seamless pipeline.
#### Evaluation Metrics:
Measures accuracy, precision, recall, F1-score, and confusion matrix.
