# VitalSense

Dataset Description 
This is a dataset from the UCI Machine Learning Repository. The dataset includes various attributes such as age, sex, cholesterol levels, blood pressure, and elctrocardiographic measurements. 


| Variable   | Role    | Type         | Description                                      | Units   | Possible Values                       |
|------------|---------|--------------|--------------------------------------------------|---------|---------------------------------------|
| age        | Feature | Numerical    | Age in years                                     | years   |                                       |
| sex        | Feature | Categorical  | Gender of the individual                         |         | 0 = female, 1 = male                  |
| cp         | Feature | Categorical  | Chest pain type                                  |         | 0, 1, 2, 3, 4                         |
| trestbps   | Feature | Numerical    | Resting blood pressure                           | mm Hg   |                                       |
| chol       | Feature | Numerical    | Serum cholesterol                                | mg/dl   |                                       |
| fbs        | Feature | Categorical  | Fasting blood sugar > 120 mg/dl                  |         | 0 = false, 1 = true                   |
| restecg    | Feature | Categorical  | Resting electrocardiographic results             |         | 0, 1, 2                               |
| thalach    | Feature | Numerical    | Maximum heart rate achieved                      |         |                                       |
| exang      | Feature | Categorical  | Exercise-induced angina                          |         | 0 = no, 1 = yes                       |
| oldpeak    | Feature | Numerical    | ST depression induced by exercise relative to rest|       |                                       |
| slope      | Feature | Numerical    | Slope of the peak exercise ST segment            |         |                                       |
| ca         | Feature | Both         | Number of major vessels (0-3) colored by fluoroscopy|   | 0, 1, 2, 3                           |
| thal       | Feature | Categorical  | Thalassemia type                                |         | 3 = normal, 6 = fixed defect, 7 = reversible defect|
| target     | Target  | Categorical  | Diagnosis of heart disease                       |         | 0 = false, 1 = true                   |