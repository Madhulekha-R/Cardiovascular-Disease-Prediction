## CARDIOVASCULAR DISEASE PREDICTION

![image](https://github.com/user-attachments/assets/26b9c89b-b1db-48ae-b8ba-0b45527b12d4)

## TABLE OF CONTENTS

- [About the Project](#about-the-project)
- [Dataset Description](#dataset-description)
- [Model Implementation](#model-implementation)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Libraries Used](#libraries-used)
- [Contact](#contact)

### ABOUT THE PROJECT : 

The Cardiovascular disease remains a pervasive global health challenge, with significant implications for mortality rates and healthcare systems worldwide. Despite advancements in medical technology and treatment protocols, variability in healthcare professionals' expertise often leads to suboptimal diagnosis and treatment decisions, contributing to adverse patient outcomes. To address this issue, predictive modeling using machine learning algorithms presents a promising avenue for improving heart disease diagnosis and management. Thus, the project **Cardiovascular Disease Prediction** aims to evaluate the performance of machine learning models in predicting heart disease, leveraging a diverse set of health parameters and data mining techniques. The project focuses on assessing the models' accuracy and generalization ability through comprehensive evaluation on both training and test datasets. By analyzing the models' performance metrics and detecting potential overfitting, the research seeks to identify the most effective predictive model for heart disease diagnosis.

### DATASET DESCRIPTION:

The dataset is been taken from **Kaggle** for the research paper. And the dataset incudes following attributes within it.</br>

- **id** : Personal identification number (Unique)</br>
- **age** : Age of the patient (Continuous)</br>
- **gender** : Male or Female (Nominal)</br>
- **height** : Height of the patient (Continuous)</br>
- **weight** : Weight of the patient (Continuous)</br>
- **ap_hi** : Systolic blood pressure of the patient</br>
- **ap_lo** : Diastolic blood pressure of the patient</br>
- **cholesterol** : Cholestral of the patient</br>
- **gluc** : Glucose level of the patient</br>
- **smoke** : Smoking status of the patient</br>
- **alco** :  Alcohol consumption of the patient</br>
- **active** : Physical activity level of the patient</br>
- **cardio** : Cardio metrics of the patient</br>

### MODEL IMPLEMENTATION:

**Five** models were implemented on the scaled data. The models were:

Logistic Regression
Decision Tree
K-Nearest Neighbours
Support Vector Machine
Random Forest

### MODEL EVALUATION:

Here's the flowchart that represents the flow of the project:

![image](https://github.com/user-attachments/assets/6f045626-48f1-45fd-b1b7-12822a9b5c84)

## RESULTS:

On implementing various machine learning algorithms over the dataset, ended up with the following output.

**LOGISTIC REGRESSION** : Logistic Regression is a machine learning algorithm that measures the relationship between the dependent variable and one or more independent variable by estimating probabilities using logistic function

 Classification report:</br>
 ![image](https://github.com/user-attachments/assets/d54e2730-cf6b-46fd-a535-0bbd15d0f937)</br>
 Accuracy Rate:</br>
 ![image](https://github.com/user-attachments/assets/2190b3d3-ef95-42f0-ae89-f381997921f3)
</br>

**SUPPORT VECTOR MACHINE**: The Support Vector Machine training algorithm builds a model that assigns new test samples to one category or other, making it a non-probabilistic binary linear classification.

 Classification report:</br>
 ![image](https://github.com/user-attachments/assets/d5e45069-e452-44f4-adfb-f9b066713c9c)</br>
 Accuracy Rate:</br>
 
### CONCLUSION:

![Screenshot 2024-08-05 194727](https://github.com/user-attachments/assets/52d0a16b-fad2-4b0a-883f-a439e4408d60)

The blue line represents the training accuracy and red line represents the test accuracy. Thus, it is concluded that the model is overfitted where the model excels in its performance on the training data but lacks the ability to generalize effectively to novel, unseen data.

### Libraries Used
### Contact

