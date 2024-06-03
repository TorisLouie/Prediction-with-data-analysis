# A Practical Approach: Running Test cycle with different choices of Loss function and Activation Functions.

We will use Heart failure clinical record data set (source:https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data/data). We will use ANN model with several activation functions with the same loss function.

We are trying to predict / classify …..  

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide.

Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

By utilizing population-wide methods to address behavioral risk factors like tobacco use, unhealthy food and obesity, physical inactivity, and harmful alcohol consumption, most cardiovascular diseases can be averted.

A ML or DL model can be very helpful in the early detection and management of cardiovascular disease or high-risk individuals.

Based only on serum creatinine and ejection fraction, we will be able to forecast the survival of individuals suffering from heart failure. For that, our goal is:

- To classify / predict whether a patient is prone to heart failure depending on multiple attributes.
- It is a binary classification with multiple numerical and categorical features.


## About the data:
- age: Age of the patient
- anemia: If the patient had the hemoglobin below the normal range
- creatinine_phosphokinase: The level of the creatine phosphokinase in the blood in mcg/L
- diabetes: If the patient was diabetic
- ejection_fraction: Ejection fraction is a measurement of how much blood the left ventricle - - pumps out with each contraction
- high_blood_pressure: If the patient had hypertension
- platelets: Platelet count of blood in kilo platelets/mL
- serum_creatinine: The level of serum creatinine in the blood in mg/dL
- serum_sodium: The level of serum sodium in the blood in mEq/L
- sex: The sex of the patient
- smoking: If the patient smokes actively or ever did in past
- time: It is the time of the patient's follow-up visit for the disease in months
- DEATH_EVENT: If the patient deceased during the follow-up period

## Summary of Validation Accuracy(Closing Call)
![alt text](media/tb1.PNG)</br>
![alt text](media/tb2.PNG)</br>
![alt text](media/image10.png)</br>
![alt text](media/tb3.PNG)</br>
![alt text](media/image9.png)</br></br>

## Classification:
![alt text](media/tb4.PNG)</br>
<b>Classification - Loss Function: Categorical_crossentropy : </b>
![alt text](media/image2.png)</br>
![alt text](media/tb5.PNG)</br>
<b>Classification - Loss Function: Mean_squared_error :</b>

![alt text](media/tb6.PNG)</br>
<b>Classification - Loss Function: Binary_crossentropy : </b>
![alt text](media/image4.png)</br>

## Contribution
Follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Commit your changes.
- Submit a pull request.

