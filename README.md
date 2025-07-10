# PRODIGY_DS-02
Repository about Prodigy Data Science Task-02

# Overview
This repository presents a comprehensive Exploratory Data Analysis (EDA) on the famous Titanic Dataset. The goal is to uncover hidden trends, understand feature importance, and clean the data for future machine learning applications.

# Key Objectives

-  Handle and clean missing values  
-  Encode categorical features for analysis  
-  Visualize survival trends across various attributes  
-  Understand correlation between features  
-  Prepare dataset for future machine learning tasks

 # Data Cleaning Steps

-  Dropped irrelevant columns: `Name`, `Ticket`, `Cabin`, `PassengerId`
-  Filled missing `Age` values with **median**
-  Filled missing `Embarked` values with **mode**
-  Encoded `Sex` and `Embarked` into numerical format
-  Created new feature: `FamilySize` = `SibSp + Parch + 1`

Visualizations Included

1. **Survival Count**
<img width="917" height="544" alt="image" src="https://github.com/user-attachments/assets/84b282cf-c282-4148-882a-06e5d0c8f354" />

2. **Survival by Sex**
<img width="914" height="539" alt="image" src="https://github.com/user-attachments/assets/631b96ec-0222-4b97-b09f-552e271b1436" />

3. **Survival by Passenger Class**
<img width="912" height="549" alt="image" src="https://github.com/user-attachments/assets/e5120816-e4a5-4e4f-8a23-aa896147fd84" />
   
4. **Age Distribution vs Survival**
<img width="916" height="545" alt="image" src="https://github.com/user-attachments/assets/f27f87be-4a5f-4bef-8d6e-f34a2140280d" />
   
5. **Fare vs Survival**
<img width="919" height="553" alt="image" src="https://github.com/user-attachments/assets/f2a229bc-793c-4826-82fb-4d1f2f04a328" />
   
6. **Embarkation Port vs Survival**
<img width="915" height="546" alt="image" src="https://github.com/user-attachments/assets/d27977bd-7a45-4e94-bbaa-4c5462a906b3" />
    
7. **Family Size vs Survival**
<img width="919" height="538" alt="image" src="https://github.com/user-attachments/assets/adbe239c-8a09-43ab-8b79-9951b4552385" />
    
8. **Correlation Heatmap**
<img width="864" height="535" alt="image" src="https://github.com/user-attachments/assets/ea166d06-104f-4846-b899-d4f6675153fe" />
    
9. **Pairwise Relationships (Pairplot)**
<img width="892" height="800" alt="image" src="https://github.com/user-attachments/assets/fb1ab65c-1ce9-4dcc-b7eb-e44c72be64bd" />

# Key Insights

-  **Females** had a significantly higher survival rate than males  
-  **1st class passengers** were more likely to survive than those in 2nd or 3rd class  
-  **Children** and younger passengers had slightly better survival rates  
-  Higher **fare** paid was positively associated with survival  
-  **Embarkation port** had a subtle impact on outcomes  
-  Medium-sized families (2–4) had higher survival odds
