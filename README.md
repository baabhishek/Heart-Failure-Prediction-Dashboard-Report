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

The analysis of survival rates in relation to high blood pressure shows the following distribution-

###### Individuals with Positive High Blood Pressure:
- Died: 13.04%
- Survived: 22.07%
###### Individuals with Negative High Blood Pressure:
- Died: 19.06%
- Survived: 45.82%
The data reveals that individuals with high blood pressure have a lower survival rate compared to those without high blood pressure. Specifically, 13.04% of those with high blood pressure have died, while 22.07% have survived. In contrast, individuals without high blood pressure show a higher survival rate, with 19.06% having died and 45.82% surviving.

This indicates that high blood pressure is associated with an increased risk of death among heart failure patients. The lower survival rate among those with high blood pressure underscores its critical role as a risk factor. Effective management of blood pressure is essential for improving survival outcomes in heart failure patients. This highlights the need for targeted interventions and monitoring of blood pressure to enhance overall patient survival.

##### Diabetes and Survival::
<img width="468" alt="Screenshot 2567-07-21 at 2 14 53 PM" src="https://github.com/user-attachments/assets/5c35942a-fd6b-4825-936f-6980e91306df">

###### Individuals with Positive Diabetes:
- Died: 13.38%
- Survived: 28.43%
###### Individuals with Negative Diabetes:
- Died: 18.73%
- Survived: 39.46%
The data shows that individuals with diabetes have a lower survival rate compared to those without diabetes. Specifically, 13.38% of those with diabetes have died, and 28.43% have survived. In contrast, individuals without diabetes have a higher survival rate, with 18.73% having died and 39.46% surviving.

### Key Insights::
<img width="1319" alt="Screenshot 2567-07-21 at 2 39 04 PM" src="https://github.com/user-attachments/assets/e75ff1e5-fc15-4187-a865-e9bc4a927aa7">

- Individuals without anaemia have a significantly higher survival rate compared to those with anaemia. This suggests that anaemia worsens the condition of heart failure patients and negatively impacts their chances of survival.
- Males generally exhibit a higher survival rate compared to females. This difference may stem from biological factors or disparities in treatment and disease progression.
- The survival rate is notably higher among non-smokers than smokers. This indicates that smoking has a detrimental effect on heart health and survival, emphasizing the need for smoking cessation initiatives.
- Younger individuals aged 21-30 show an unexpected elevated risk of death. This anomaly suggests the presence of additional underlying health issues or lifestyle factors that need further exploration.
- Lower creatinine phosphokinase levels are associated with a reduced mortality rate. Elevated levels may indicate more severe heart conditions, contributing to higher mortality risks.
- Individuals with high blood pressure have a lower survival rate compared to those without. This highlights high blood pressure as a significant risk factor for reduced survival in heart failure patients.
- While diabetes impacts survival rates, its effect is moderate. Effective diabetes management is crucial, as it plays a role in influencing survival outcomes in heart failure patients.

### Strategic Considerations::
- Targeted Interventions: Focus on managing anaemia, smoking, and high blood pressure to enhance survival rates.

- Gender-Specific Strategies: Develop tailored treatment approaches based on gender differences in survival rates.

- Age-Specific Considerations: Investigate and address the elevated risk among individuals aged 21-30 with targeted management strategies.

- Smoking Cessation: Implement robust smoking cessation programs to improve outcomes in heart failure patients.

- Regular Monitoring: Continuously monitor and manage blood pressure and diabetes to improve survival and reduce mortality.

- Further Research: Conduct additional research into the risks for younger individuals and the role of creatinine phosphokinase to refine treatment strategies.


