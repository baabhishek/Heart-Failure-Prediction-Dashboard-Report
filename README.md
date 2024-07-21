# Heart-Failure-Prediction-Dashboard-Report
A detailed Heart Failure Prediction Report brought to life through Tableau Visualisation, telling a story from the data.

![banner-hf-awareness-month-2023_02](https://github.com/user-attachments/assets/63cb9c01-6ada-4a29-b1ec-aa903ff71819)

### Overview of the Data
The dataset consists of health and demographic metrics for individuals with heart failure, including age, presence of anaemia, levels of creatinine phosphokinase, diabetes status, ejection fraction, high blood pressure, platelet count, serum creatinine, serum sodium, sex, smoking status, and the time of observation. The key outcome variable is DEATH_EVENT, which denotes whether an individual survived or died. The objective of this analysis is to uncover significant patterns and relationships between these factors and survival rates.

### Methodology
- Data Source: Heart failure prediction dataset.
- Tools Used: Excel for initial data preparation and Tableau for visualization and dashboard creation.

### Visualizations:
- Dual-Axis Donut Chart: To illustrate the proportion of deaths and survival.
- Histogram: To show the distribution of key variables.
- Scatter Plot: To explore relationships between continuous variables.
- Box Plot: To visualize the spread and outliers in numerical data.
- Calculated Fields: Used to derive survival rates and other metrics.

### Analysis: 

#### Overall Statistics:
<img width="1287" alt="Screenshot 2567-07-21 at 2 09 05 PM" src="https://github.com/user-attachments/assets/896f97a9-9fa8-4bbe-915e-35c4d8aab80f">

The dataset includes 299 individuals, with 96 recorded deaths, reflecting a mortality rate of approximately 32.1%. This high death rate underscores the critical nature of heart failure and highlights the need for effective treatment and management strategies.

##### Demographic Breakdown::
- Total Males: 194
- Total Females: 105
  
The gender distribution shows a higher number of males (194) compared to females (105). This demographic distribution is important for understanding how sex-specific factors might influence survival rates.

##### Average Age::
The average age of individuals in the dataset is 60.83 years. This average age aligns with the common demographic of heart failure patients, who are typically older. The relatively high average age indicates that the majority of the patients are elderly, which is consistent with the increased prevalence of heart failure in older adults.

##### Anaemia and Survival Status::
<img width="397" alt="Screenshot 2567-07-21 at 2 10 14 PM" src="https://github.com/user-attachments/assets/98a4a9a4-ef14-4bb5-bc18-396d67d822d1">

###### Negative Anaemia
- Died: 16.72% (50 individuals)
- Survived: 40.13% (120 individuals)

###### Positive Anaemia
- Survived: 27.76% (83 individuals)

The analysis of survival based on anaemia status reveals that individuals without anaemia have a higher survival rate. Specifically, 16.72% of those without anaemia have died, whereas 40.13% survived. In contrast, individuals with anaemia show a lower survival rate, with 27.76% surviving. This suggests that anaemia exacerbates the severity of heart failure and negatively impacts survival.

##### Sex and Survival Status::
<img width="416" alt="Screenshot 2567-07-21 at 2 10 55 PM" src="https://github.com/user-attachments/assets/7fb4ec64-3cae-480a-b44c-380f0d69dae5">

###### Male:
- Died: 20.74%
- Survived: 44.15%
###### Female:
- Died: 11.37%
- Survived: 23.75%

The data suggests that males generally have a higher survival rate compared to females. This could be attributed to biological differences, disparities in treatment, or variations in disease progression between sexes.

##### Smoking Status and Survival::
<img width="532" alt="Screenshot 2567-07-21 at 2 11 52 PM" src="https://github.com/user-attachments/assets/18272ab0-fdcf-4e0e-a345-17ed924d175f">

The impact of smoking on survival is significant:
- Smokers: 10.03% have died and 22.07% survived.
- Non-Smokers: 22.07% have died, while 45.82% survived.

Non-smokers exhibit a notably higher survival rate compared to smokers. This underscores the detrimental effect of smoking on heart health and survival, highlighting the importance of smoking cessation for improving outcomes in heart failure patients.

##### Age and Survival::
<img width="486" alt="Screenshot 2567-07-21 at 2 12 34 PM" src="https://github.com/user-attachments/assets/a7288319-0822-4868-b1a3-55cd2275521f">

###### Age Group 21-30 >
An unusual finding in the dataset is that individuals aged between 21 and 30 show an elevated risk of death compared to other age groups. While heart failure is more common in older individuals, this age group’s increased risk may be due to other underlying health conditions or lifestyle factors not directly captured by the dataset.

#####  Creatinine Phosphokinase and Survival::
<img width="598" alt="Screenshot 2567-07-21 at 2 13 17 PM" src="https://github.com/user-attachments/assets/a7681f5e-e194-4dce-bce5-96458e28aafe">

Creatinine phosphokinase levels also play a role in survival-
- Individuals with lower levels of creatinine phosphokinase tend to have a lower mortality rate.
- This suggests that elevated levels of this enzyme may indicate more severe heart conditions or complications, contributing to a higher risk of death.

##### High Blood Pressure and Survival::
<img width="540" alt="Screenshot 2567-07-21 at 2 13 51 PM" src="https://github.com/user-attachments/assets/5c60fbe7-2de8-45e5-b374-de9f2f89b813">

High blood pressure has a significant impact on survival-
- Individuals with high blood pressure: 16.19% have died, while 25.71% survived.
- Individuals without high blood pressure: 41.90% survived, with 16.19% having died.
- Those without high blood pressure have a considerably higher survival rate, emphasizing the importance of managing blood pressure to improve heart failure outcomes.

##### Diabetes and Survival::
<img width="468" alt="Screenshot 2567-07-21 at 2 14 53 PM" src="https://github.com/user-attachments/assets/5c35942a-fd6b-4825-936f-6980e91306df">

Diabetes status affects survival as follows-

###### Positive Diabetes:
- Died: 19.05%
- Survived: 33.33%

###### Negative Diabetes:
- Died: 13.33%
- Survived: 34.29%

- Individuals with diabetes: 19.05% have died, and 33.33% survived.
- Individuals without diabetes: 13.33% have died, with 34.29% surviving.
- While diabetes does affect survival rates, the impact is relatively moderate compared to factors such as smoking and high blood pressure. Nonetheless, managing diabetes is crucial for improving overall survival in heart failure patients.

##### Key Insights::
- The descriptive analysis highlights several factors that significantly influence survival in heart failure patients. 
- Key factors include the presence of anaemia, smoking status, high blood pressure, and age. 
- The higher survival rates among non-smokers, individuals without high blood pressure, and those without anaemia suggest that these are crucial areas for intervention. The unexpected risk associated with younger individuals and the role of creatinine phosphokinase levels further inform the need for targeted management strategies.

- High Risk Factors: The presence of anaemia, high blood pressure, and smoking are associated with lower survival rates.
- Age: Younger individuals (21-30) show an elevated risk of death, which could be due to other underlying conditions.
- Sex: Men generally have a higher survival rate compared to women.


