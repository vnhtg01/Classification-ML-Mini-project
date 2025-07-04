
<img width="851" alt="image" src="https://github.com/user-attachments/assets/4e6c3b06-e9e9-4fd6-942a-f5639d8a0ca4" />


<h1 align="center">ML Classification Project For Diabetes Prediction</h1>
<h4><u>Objective :</u></h4> 
Build a machine learning model to perform <b>Binary Classification</b> based on a real dataset from Kaggle. Project done in python on jupyter notebook.

<h4><u>Notes :</u></h4> 

Class `0` represents *healthy*, class `1` represents *sick*  

# Table of Contents

- [A. Pipeline Overview](#apipeline-overview)
  - [A.1. Data Import](#a1-data-import--from-kaggle)
  - [A.2. Exploratory Data Analysis (EDA) & Data Visualization](#a2-exploratory-data-analysis-eda--data-visualization)
  - [A.3. Data Preprocessing](#a3-data-preprocessing)
  - [A.5. Model Training](#a5-model-training)
  - [A.6. Model Evaluation](#a6-model-evaluation)
  - [A.7. Model Deployment](#a7-model-deployment--not-included)
- [B. Report File extracted by ydata-profiling](#breport-file-extracted-by-ydata-profiling)
- [C. Prediction Model Summary](#c-the-file-summarizing-the-prediction-models-includes-the-accuracy-f1-score-and-time-taken-parameters-and-prediction-execution-time-based-on-this-dataset)
  - [C.1. Models sorted by speed and accuracy](#c1-this-list-of-trained-models-sorted-by-fast-execution-time-and-high-balanced-accuracy-parameter)
  - [C.2. Top 5 as horizontal bar charts](#c2-top-5-as-horizontal-bar-charts)
- [D. Results](#d-results)

  

# A.Pipeline-Overview
1. **Data Import** : from kaggle
2. **Exploratory Data Analysis (EDA) & Data Visualization**  
   - Check for missing values  
   - Analyze variable distributions  
   - Compute correlation matrix
   - Create a report of dataset from ydata_profiling
3. **Data Preprocessing**  
   - Standardization (scaling)
   - Train/Test split
   - (Bonus) GridSearchCV to find the best hyperparameter
5. **Model Training** 
   - Logistic Regression  
   - Decision Tree  
   - Random Forest
   - (Bonus) LazyPredict to show performances of 30-40 differents models
6. **Model Evaluation** 
   - Accuracy, Precision, Recall, F1-score  
   - Classification report  
   - Confusion matrix
7. **Model Deployment** : not included

# B.Report-File-extracted-by-ydata-profiling

![image](https://github.com/user-attachments/assets/0d9e51ca-5ba6-4fcf-b06b-17b0a6ac4069)
![image](https://github.com/user-attachments/assets/479b9973-3245-40c8-9a68-8e0fab7e87a1)
![image](https://github.com/user-attachments/assets/e5c42623-e90b-4e15-b83a-89b460e71d97)
![image](https://github.com/user-attachments/assets/4f8dc8b1-b8fb-4503-97f8-40dd97f88140)
![image](https://github.com/user-attachments/assets/29a138f7-dde7-4e6c-9d37-d837943b5879)
![image](https://github.com/user-attachments/assets/3fee7f52-b6b8-4f48-93f5-e70c4aa45f3d)
![image](https://github.com/user-attachments/assets/3740c905-8df1-47ba-a80a-f5ad0bb97001)
![image](https://github.com/user-attachments/assets/387b025d-47a5-4622-a3dd-bca33dd61f4e)
![image](https://github.com/user-attachments/assets/1bb4ce57-5455-48cb-8bb2-51ac28df146a)
![image](https://github.com/user-attachments/assets/3020b72d-04a9-459c-ad3b-8ac1874093c4)



![image](https://github.com/user-attachments/assets/f606a684-9f55-47b3-823f-da131b244a27)
![image](https://github.com/user-attachments/assets/4aa609da-4054-4dae-8631-0d82211abb94)
![image](https://github.com/user-attachments/assets/281c6f43-3e9c-4370-88c3-e4d4fb1e84e5)
![image](https://github.com/user-attachments/assets/23f2357e-d351-4aab-9592-a5c27f9eeeab)


# C. The file summarizing the prediction models includes the Accuracy, F1 score and Time Taken parameters and prediction execution time based on this dataset. 

#### C.1. This list of trained models sorted by fast execution time and high Balanced-Accuracy parameter

![image](https://github.com/user-attachments/assets/c9f57597-cf36-4983-b4b3-ac684d975bdb)


#### C.2. Top 5 as horizontal bar charts

![image](https://github.com/user-attachments/assets/6fdd69b0-aae6-4fe0-843e-fdc674067ba0)

# D. Results
- All models were trained and evaluated to identify the best-performing one for this classification task.
- Reusability on other datasets thanks to calling the pickle library to store the models.
