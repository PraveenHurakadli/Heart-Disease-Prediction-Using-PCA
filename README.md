# Heart-Disease-Prediction-Using-PCA 🫀


Description:

Utilizing Principal Component Analysis (PCA) for insightful feature reduction and predictive modeling, this GitHub repository offers a comprehensive approach to forecasting heart disease risks. Explore detailed data analysis, PCA implementation, and machine learning algorithms to predict and understand factors contributing to heart health.

# Medical Phenomenon 🩺

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year. CVDs are a group of disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. Four out of 5CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age.
Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.



<p align="center">
<img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbDZ0a20zMXZxdGZkM3BoaG92YXhhcnEzcjc2MDNweDBzYmVpaXAzMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/l6JC0IxMDIS4QrUxO5/giphy.gif" width="400" height="500" />
</p>
Individuals at risk of CVD may demonstrate raised blood pressure, glucose, and lipids as well as overweight and obesity. These can all be easily measured in primary care facilities. Identifying those at highest risk of CVDs and ensuring they receive appropriate treatment can prevent premature deaths. Access to essential noncommunicable disease medicines and basic health technologies in all primary health care facilities is essential to ensure that those in need receive treatment and counselling.

# Dataset  

The dataset contains medical records of 304 patients who had heart failure, collected during their follow-up period, where each patient profile has 12 clinical features. https://github.com/PraveenHurakadli/Heart-Disease-Prediction-Using-PCA/blob/main/heart.csv

# Attributes Information:
<table>
<thead><tr>
<th>Attribute</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Age</strong></td>
<td>Age of a patient [years]</td>
</tr>
<tr>
<td><strong>Sex</strong></td>
<td>Gender of the patient [M: Male, F: Female]</td>
</tr>
<tr>
<td><strong>ChestPain</strong></td>
<td>Chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]</td>
</tr>
<tr>
<td><strong>RestingBP</strong></td>
<td>Blood pressure in Hg (Normal blood pressure - 120/80 Hg)</td>
</tr>
<tr>
<td><strong>Cholesterol</strong></td>
<td>Serum cholestrol level in blood (Normal cholesterol level below for adults 200mg/dL)</td>
</tr>
<tr>
<td><strong>FastingBS</strong></td>
<td>Fasting Blood Sugar (Normal less than 100mg/dL for non diabetes for diabetes 100-125mg/dL)</td>
</tr>
<tr>
<td><strong>RestingECG</strong></td>
<td>Resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of &gt; 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]</td>
</tr>
<tr>
<td><strong>MaxHR</strong></td>
<td>Maximum heart rate achieved [Numeric value between 60 and 202]</td>
</tr>
<tr>
<td><strong>ExerciseAngina</strong></td>
<td>Exercise-induced angina [Y: Yes, N: No]</td>
</tr>
<tr>
<td><strong>Oldpeak</strong></td>
<td>oldpeak = ST [Numeric value measured in depression]</td>
</tr>
<tr>
<td><strong>ST_Slope</strong></td>
<td>The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]</td>
</tr>
<tr>
<td><strong>HeartDisease</strong></td>
<td>output class [1: heart disease, 0: Normal]</td>
</tr>
</tbody>
</table>


# Procedural Overview

Here is the overview of the procedural steps to perform Principal Component Analysis (PCA) using machine learning algorithms for a heart disease prediction project.

## Steps:

### 1. Data Collection and Preprocessing:
Gather a dataset containing relevant features related to heart health (e.g., age, blood pressure, cholesterol levels, etc.).
Handle missing values, encode categorical variables, and normalize/standardize the data.

### 2. Exploratory Data Analysis (EDA):
Perform descriptive statistics, visualizations, and correlation analysis to understand the dataset.
Assess feature importance and relationships to gain insights.

### 3. Feature Selection and PCA:
Identify features relevant for predicting heart disease.
Apply PCA to reduce the dimensionality of the dataset while retaining important information.
Determine the number of principal components to keep (using variance explained or scree plot).

### 4. Split Data for Training and Testing:
Divide the dataset into training and testing sets (e.g., 70-30 or 80-20 split).

### 5. Model Selection and Training:
Choose appropriate machine learning algorithms (e.g., Logistic Regression, Random Forest, SVM) for classification.
Fit the model on the training data.

### 6. Model Evaluation:
Evaluate the model's performance using the testing data (accuracy, precision, recall, F1-score, ROC curve, etc.).
Use cross-validation to assess model robustness.

### 7. Tuning and Optimization:
Fine-tune hyperparameters of the models to improve performance (e.g., GridSearchCV or RandomizedSearchCV).

### 8. Prediction and Interpretation:
Make predictions on new/unseen data using the trained model.
Interpret the results and assess the factors contributing to heart disease prediction.

# Performance Results

KNN model gives an accuracy of : 87%

Random forest gives an accuracy of : 86%

Suport Vector Classifier gives an accuracy of : 86%

Gradient Boosting Classifier gives an accuracy of: 82%
