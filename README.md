# Building-Machine-Learning-API-s-With-FastAPI

## Introduction
The project focused on analyzing trends and predictors in patient data to uncover the factors contributing to sepsis occurrences. Machine learning models were developed to provide accurate and efficient classification of sepsis cases, utilizing the FastAPI framework and Docker for implementation.

## Project Objective
The objective of this project is to develop a predictive model that identifies ICU patients at risk of developing sepsis. Early identification of such patients can significantly improve treatment outcomes, reduce mortality rates, and lower healthcare costs by enabling timely interventions.

## Key objectives 
Early Detection: Predict which patients in the ICU are likely to develop sepsis, allowing healthcare providers to intervene early and improve patient outcomes.

-Resource Allocation: Optimize the allocation of medical resources by focusing attention and care on high-risk patients.
 
-Cost Reduction: Reduce healthcare costs associated with sepsis by preventing its occurrence through early interventions.

## Summary

| Name                       | Description        |
| -------------------------- | ------------------ | 
| Code                       | LP5                | 
| Project Name               | Builnding a Machine Learning API's with FastAPI | 
| Published Article          | https://medium.com/@mberaalice7/predicting-sepsis-status-of-patients-with-machine-learning-and-fast-api-828254bd7865 |
| Deployed App               | https://gabcares-team-curium.hf.space/   |
|                            |                    | 

## Data understanding 


| Column Name | Data Features | Description                                      |
|-------------|-----------------|--------------------------------------------------|
| ID          | N/A             | Unique number to represent patient ID             |
| PRG         | Attribute 1     | Plasma glucose                                   |
| PL          | Attribute 2     | Blood Work Result-1 (mu U/ml)                    |
| PR          | Attribute 3     | Blood Pressure (mm Hg)                           |
| SK          | Attribute 4     | Blood Work Result-2 (mm)                         |
| TS          | Attribute 5     | Blood Work Result-3 (mu U/ml)                    |
| M11         | Attribute 6     | Body mass index (weight in kg/(height in m)^2)   |
| BD2         | Attribute 7     | Blood Work Result-4 (mu U/ml)                    |
| Age         | Attribute 8     | Patient's age (years)                            |
| Insurance   | N/A             | If a patient holds a valid insurance card         |
| Sepsis      | Target          | Positive: if a patient in ICU will develop sepsis,<br> Negative: otherwise |

## Hypothesis 
- Null Hypothesis(Ho): Older patients (age 60 and above) are less likely to develop sepsis compared to younger patients (below 60 years).

- Alternate Hypothesis(Ha): Older patients (age 60 and above) are more likely to develop sepsis compared to younger patients (below 60 years).

The above hypothesis aided in providing more insight for further analysis.

## Analytical Questions answered

- Is there a relationship between body mass index (M11) and the development of sepsis?
- Are there noticeable differences in blood pressure (PR) readings between sepsis-positive and sepsis-negative patients?
- How do plasma glucose levels (PRG) differ between patients who develop sepsis and those who do not?
- Does a patient having an Insurance card influence Sepsis development?
- What is the average/median age of patients who develop sepsis and those without sepsis?

## API Documentation
API documentation can accessed  by visiting the /docs endpoint after starting the server. https://gabcares-team-curium.hf.space/

![D3](https://github.com/user-attachments/assets/ee221f57-d2aa-457b-b397-7beb4c29e6bb)

![D5](https://github.com/user-attachments/assets/13c1358f-d9fb-4268-8658-8b146a8535e8)

## Docker Container
Below is a screenshot of my **FASTAPI** runing successfully in my docker desktop using. 

![D1](https://github.com/user-attachments/assets/76392046-90b3-467d-8db9-d2ec4ab97fc9)

![D2](https://github.com/user-attachments/assets/28764afc-1f49-4c0d-b28a-baffec5e5c48)



## STREAMLIT APP PREDICTED RESULTS
Below is an interface of predicted results in streamlit.

![D4](https://github.com/user-attachments/assets/706cae96-29f4-44c3-8f2a-0c048296a3fd)




## Author

Alice Mbera








  

  





