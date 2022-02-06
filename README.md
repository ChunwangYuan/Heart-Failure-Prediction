# Heart-Failure-Prediction 

<center>
<img src= "https://health.clevelandclinic.org/wp-content/uploads/sites/3/2018/08/GettyImages-944106494.jpg" width="1000">
</center>
Built various Machine Learning algorithms (Logistic Regression, Random Forest, KNN, Gradient Boosting and XGBoost. etc). Structured a custom ensemble model and a neural network.
Found a outperformed model for heart failure prediction accuracy of 88 percent. 

## Introduction

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or who are at high cardiovascular risk need early detection and management wherein a machine learning model can be of great help.


<h3> Table of Contents</h3>
    
* [Data]
    * [What We need to do]

* [Exploratory Data Analysis]
    * [Target Variable]
    * [Features]

* [Model Selection]  
    * [Model Creation and Comparison]
    * [Bulid a custom ensemble (superlearner) with best three of models]
    * [Neural Networks]
    * [Feature Importance]   
    
* [Conclusion]

<h3>  DATA	</h3>				
						
1	**Age**: 			Age of the patient [years] 		

2	**Sex**:  			 Sex of the patient [M: Male, F: Female] 		

3	**ChestPainType**: 			[TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic] 		

4	**RestingBP**:			Resting blood pressure [mm Hg] 		

5	**Cholesterol**:			Serum cholesterol [mm/dl] 		

6	**FastingBS**:			 Fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]		

7	**RestingECG**:			 Resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria] 		

8	**MaxHR**:			Maximum heart rate achieved [Numeric value between 60 and 202]		

9	**ExerciseAngina**:			Exercise-induced angina [Y: Yes, N: No]		

10	**Oldpeak**:			 ST [Numeric value measured in depression] (		

11	**ST_Slope**:			 The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping] 		

12	**HeartDisease**:			 Output class [1: heart disease, 0: Normal] 		

Reference: https://www.kaggle.com/fedesoriano/heart-failure-prediction
