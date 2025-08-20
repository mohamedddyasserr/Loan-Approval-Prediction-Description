# Loan Approval Prediction  

## Problem Statement  
The goal of this project is to **predict loan approval** for applicants based on demographic and financial attributes.  
This is a classic **binary classification** problem where the models determine whether a loan application should be **approved** or **not approved**.  

---

## Dataset Overview  
The dataset was sourced from **Kaggle (Loan Approval Prediction Dataset)**.  
It contains applicant details such as gender, marital status, dependents, income, loan amount, credit history, and property area.  

- **Total Records**: ~600  
- **Target Variable**: `Loan_Status` (Approved = 1, Not Approved = 0)  

---

## Features  
The key features include:  

- **ApplicantIncome** – Income of the applicant  
- **CoapplicantIncome** – Income of the co-applicant  
- **LoanAmount** – Loan amount requested  
- **Loan_Amount_Term** – Loan term in months  
- **Credit_History** – Credit history of the applicant  
- **Gender, Married, Education, Self_Employed, Property_Area** – Categorical attributes  

After preprocessing:  
- All categorical variables were encoded into numeric format.  
- Features were normalized and scaled.  

---

## Model Comparison  

| Model                | Accuracy | ROC-AUC | Notes |
|-----------------------|----------|---------|-------|
| Logistic Regression   | ~91%     | 0.97    | Strong baseline, interpretable |
| Support Vector Machine (SVM) | ~92.3%     | 0.97    | Slightly better accuracy, robust to high-dimensional data |

 **Both models performed strongly**, with SVM slightly outperforming Logistic Regression in terms of accuracy, while both achieved identical ROC-AUC values.  

---

## Visualization  


### Metrics (Confusion Matrices)  

| Logistic Regression | Support Vector Machine (SVM) |
|----------------------|------------------------------|
| <img width="500" height="397" alt="image" src="https://github.com/user-attachments/assets/fd9e1a13-c0b6-40ca-bbee-4bdb91c07c16" />| <img width="500" height="404" alt="image" src="https://github.com/user-attachments/assets/98993dfb-f4b9-47cb-9670-842d6d406489" />|

---

### ROC Curves  

| Logistic Regression | Support Vector Machine (SVM) |
|----------------------|------------------------------|
| <img width="500" height="404" alt="image" src="https://github.com/user-attachments/assets/92666604-2d0b-4d6d-b039-07a7686942f0" />| <img width="500" height="404" alt="image" src="https://github.com/user-attachments/assets/a67e6fdf-4b79-4940-a346-3944b11b5c67" />|

---

### Precision–Recall Curves  

| Logistic Regression | Support Vector Machine (SVM) |
|----------------------|------------------------------|
| <img width="500" height="404" alt="image" src="https://github.com/user-attachments/assets/e9da30d8-0f71-4507-8014-19aef1b3bf6b" />| <img width="500" height="404" alt="image" src="https://github.com/user-attachments/assets/fab02693-7732-4c2f-81fe-40fedfbd7a1a" />|

---

## Project Structure  


loan-approval-prediction/

├── raw_data/

├── processed_data/

├── notebooks/

│ ├── 01_preprocessing.ipynb 

│ ├── 02_model_training.ipynb

│ └── 03_evaluation.ipynb

├── plots/

└── README.md 
---

## Author 

<div>
<table align="center">
  <tr>    </td>
    </td>
        <td align="center">
      <a href="https://github.com/mohamedddyasserr" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/126451832?v=4" width="150px;" alt="Mohamed Yasser"/>
        <br />
        <sub><b>Mohamed Yasser</b></sub>
      </a>
    </td>    
  </tr>
</table>
</div>
  
