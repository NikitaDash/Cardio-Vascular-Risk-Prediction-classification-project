

# Project Title : Cardiovascular Risk Prediction

# Project Summary

The Machine Learning Cardiovascular Risk Prediction project aims to create an accurate predictive model for evaluating an individual's risk of developing cardiovascular disease (CVD). This ambitious undertaking involves the application of advanced machine learning techniques to analyze diverse data sources, such as electronic health records and lifestyle information from patients. The primary objective of this model is to use these data points to forecast an individual's probability of developing CVD and pinpoint specific risk factors.

The project encompasses multiple essential phases, including the collection and thorough cleansing of data, the process of feature engineering to enhance the predictive capabilities, and the development of a robust machine learning model. This model will be meticulously trained on a comprehensive dataset of patient information.

Ultimately, the project's success hinges on the precision of the predictive model and its capacity to accurately identify individuals who are at elevated risk of CVD. By achieving this, the project holds the potential to significantly contribute to the early detection and prevention of cardiovascular disease, thereby improving overall public health.

# Objective :

Develop a predictive model to assess an individual's risk of developing cardiovascular disease (CVD).

# Problem Statement :
* The dataset we have here is from the Ongoing Cardiovascular study on the residents of the town of Framingham, Massachusetts.

* The Classfication goal is to predict whether the Patient has a 10-yrs. risk of Future Coronary Heart Disease (CHD).

* On the basis of the dataset we have to build such model that can predict whether Patient will be diseased or not.?

# Data Description :

* Demographic:

Sex: male or female("M" or "F")

Age: Age of the patient

* Behavioral:

is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

Cigs Per Day: the number of cigarettes that the person smoked on average in one day.

* Medical( history):

BP Meds: whether or not the patient was on blood pressure medication

Prevalent Stroke: whether or not the patient had previously had a stroke

Prevalent Hyp: whether or not the patient was hypertensive

Diabetes: whether or not the patient had diabetes

* Medical( current):

Tot Chol: total cholesterol level

Sys BP: systolic blood pressure

Dia BP: diastolic blood pressure

BMI: Body Mass Index

Heart Rate: heart rate

Glucose: glucose level

# Work Flow:
1. Data Collecting
2. Data Filtering
3. EDA
4. Feature Enginnering
5. Data Modeling

# Strategy:
1. Utilize statistical metrics to discern the distributions of data.

2. Create additional attributes derived from the original variables to enhance the description of the phenomenon being modeled.

3. Conduct exploratory data analysis to uncover insights and gain a deeper understanding of how variables influence model learning.

4. Selection of the most significant attributes for training the model.

5. Implement the machine learning algorithm such as LogisticRegression, KNeighborsClassifier, DecisionTreeClassifier, 

6. Employed cross-validation and hyperparameter tuning for each algorithm to improve the accuracy of the model.

7. Conclude by comparing the classifiers using ROC curves.

   
   ![image](https://github.com/NikitaDash/Cardio-Vascular-Risk-Prediction-classification-project/assets/139312819/2139b661-4c2a-4625-a718-c3c8f974efed)

# Conclusion:

Out of the three machine learning algorithms utilized—Logistic Regression, K-Nearest Neighbors Classifier, and Decision Tree—we determined that the K-Nearest Neighbors Classifier was the most suitable and effective having 89% accuracy. Therefore, we proceeded with implementing it.



