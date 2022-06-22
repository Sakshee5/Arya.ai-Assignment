# Arya.ai-Assignment

## Exploratory Data Analysis
### 1. General Data Characteristics:
    a. Size of Training Set - (3910, 58)
    b. Size of Testing Set - (691, 57)
    c. The column of responses i.e., ['Y'] is binary.
    d. There are 57 predictors, none of which have informative headers.
    
### 2. Data Imbalance: 
     There is no significant Data Imbalance in the dataset.
     
### 3. Missing Values: 
    a. There are no null values in any column (Missing data handling not required).
    b. There is no column filled with all zeroes. 

### 4. Outlier Detection: 
      The dataset has a significant amount of noise which gives rise to a lot of outliers whose elimination is not necessary since “An Outlier is that observation which is significantly different from all other observations.” which is not the case.
      
### 5. Feature Co-relation using Heatmaps

### 6. Dimensionality Reduction using PCA: 
     To handle highly co-related features since two or more collinear features (correlated in some way but not necessarily with a strictly linear relationship) can give unexpected results while computing feature importance.
     
     New Training Set Shape - (3910, 52)
     
### 6. Feature Importance using Random Forest Regressor 
    Final Training Set Shape - (3910, 36)

## Methodology

### 1. Machine learning Classifiers 

Step 1: Hyperparameter Tuning using GridSearch

Step 2: Training 

#### Classifiers Trained
    a. Logistic Regressor
    b. K-nearest Neighbors
    c. Support Vector Classifier
    d. Random Forest Classifier
    e. Extra Trees Classifier (BEST f1/auc score)
    f. Stochastic Gradient Descent Classifier


### 2. Binary Neural Network Classifier


## Result Visualizations

#### Confusion Matrix for best classifier
![image](https://user-images.githubusercontent.com/69002060/174968203-93d0f3d8-2f55-4b8d-b239-1a48fa2c8189.png)

#### Training and Validation Curves (Neural Network)
![image](https://user-images.githubusercontent.com/69002060/174968393-be4a9a6c-eb62-4119-be00-5c99f5df9246.png)

#### Confusion Matrix for Neural Network
![image](https://user-images.githubusercontent.com/69002060/174968423-79fb9783-2936-46b2-8e85-8723c7ae3bc3.png)

