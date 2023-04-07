# Wine Classification Project

# 1. Business Problem
### Introduction
  The challenge is to explore the data and train a classification model to analyze the chemical and visual features of wine samples and classify them based on their cultivar (grape variety).It is necessary that achieves an overall Recall metric of over 0.95 (95%). After that, the trained model should be saved and then used to classify the Wine Variety for following two new wine samples.
  
**WineVariety**
- 0 (variety A)
- 1 (variety B)
- 2 (variety C)

| Alcohol | Malic_acid | Ash | Alcalinity | Magnesium | Phenols | Flavanoids | Nonflavanoids | Proanthocyanins | Color_intensity | Hue | OD280_315_of_diluted_wines | Proline |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| 13.72 | 1.43 | 2.5 | 16.7 | 108 | 3.4 | 3.67 | 0.19 | 2.04 | 6.8 | 0.89 | 2.87 | 1285 |
| 12.37 | 0.94 | 1.36 | 10.6 | 88 | 1.98 | 0.57 | 0.28 | 0.42 | 1.95 | 1.05 | 1.82 | 520 |

# 2. Solution Strategy
  My strategy to solve this challenge was:
  
  Step 01. Data Description: My goal is to use statistics metrics to identify data outside the scope of business.
  
  Step 02. Data Filtering: Filter rows and select columns that do not contain information for modeling or that do not match the scope of the business.
  
  Step 03. Exploratory Data Analisys: Explore the data to find insights and better undestand the impact of variables on model training.
  
  Step 04. Data Preparation: Prepare the data so that the Machine Learning models can learn the specific behavior.
  
  Step 05. Feature Selection: Selection of the most significant attributes for training the model.
  
  Step 06. Machine Learning Modeling: Machine Learning model training.
  
  Step 07. Use the model to predict the column 'WineVariety' of the new two wine samples.

# 4. Machine Learning Model Applied
    - Logistic Regression
  
# 5. Machine Learning Model Performance 
### Metrics
| Accuracy  | Overall Precision | Overall Recall  | Average AUC | 
| ------------- | ------------- | ------------- | ------------- |
| 0.9815 | 0.9762  | 0.9848 | 0.9990 |

<div align="center">
<img src="https://user-images.githubusercontent.com/126209562/230531900-bf6b2386-6385-401b-9ad8-d325923a1250.png" width="700px" />
</div>

# 6. Results 
  When the model trained was used in the new dataframe the results obtained for the 'WineVariety' column were the following:
| WineVariety |
| ------------- | 
| 0  |
| 1 |
 
