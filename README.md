# AI / ML Project: BMI Assessment 🏋️

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/141758659-95fbcedc-ecb2-4213-859c-765541a3ef3f.jpg" style="width: 1000px;"/></p>


### Description:

A simple yet challenging project, to estimate the BMI based on the Gender, Height & Weight.
The complexity arises due the fact that dataset has less samples, & is highly imbalanced.
Can you overcome these obstacles & build a good predictive model to classify them?

**This data frame contains the following columns:**

* Gender : Male / Female

* Height : Number (cm)

* Weight : Number (Kg)

* Index :
0 - Extremely Weak
1 - Weak
2 - Normal
3 - Overweight
4 - Obesity
5 - Extreme Obesity

**Source:**

Kaggle - 
https://www.kaggle.com/yersever/500-person-gender-height-weight-bodymassindex

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification models to predict the various categories of BMI.
- Compare the evaluation metrics of vaious classification algorithms.

### The Project is divided into the following steps:
1. Data Exploration
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Selection/Extraction
5. Feature Scaling
6. Predictive Modeling
7. Project Outcomes & Conclusions

### Some Visuals of the Project:

**1. Target Variable Distribution**
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/141759098-056607e4-8f0d-40e9-8bb4-4c006079c782.png" /></p>

**2. Categorical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141759248-04c88851-7edc-46c6-8ae4-3c5498ef7061.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/141759303-b614aa1f-4923-437b-b927-06e795c4b4ae.png)
![image](https://user-images.githubusercontent.com/54996245/141759315-c15fd9a9-81fa-4901-b6c4-65245379491d.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/141759549-7182de06-ef04-45b1-b17f-172b89aa8ecf.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/141759612-f7c76d72-5b27-4c0e-b209-bbfea185db04.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/141759715-06c1d620-fba5-406c-8968-b94494ce2b8c.png)

**7. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/141759915-f8195733-0f5c-40f7-a442-6fb8d079ac09.png)


**5. ML Algorithm's Scores for the Iris Dataset**
![image](https://user-images.githubusercontent.com/54996245/141759947-88ce8f81-c4bc-4e0d-977b-73b8a5237e9f.png)
![image](https://user-images.githubusercontent.com/54996245/141759958-cb5b259e-e012-479b-820c-816c62ab7cb7.png)


### Here are some of the key outcomes of the project:
- The Dataset was small totally around 500 samples & after preprocessing 2.2%a of the datasamples were dropped. 
- The samples were highly imbalanced, hence SMOTE Technique was applied on the data to  balance the classes, adding 36.6% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the featureset.
- Feature Selection/Eliminination was not carried out due to less number of features.
- Testing multiple algorithms with default hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The ensemble & boosting algorithms perform the best on the current dataset, followed by Nearest Neighbours Algorithm.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive.
