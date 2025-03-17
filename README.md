# Humana_Machine_Learning_Project
# 🏥 Predicting Factors Influencing Insurance Members' Non-Adherence to Preventive Visits  

## 📌 Overview  
This project was developed for the **Humana-Mays 2024 Case Competition**, aiming to analyze factors affecting **preventive visit adherence** among **Medicare Advantage (MA) members**. Using **data analysis and machine learning**, we identified key factors influencing healthcare engagement and proposed targeted business strategies to improve preventive care participation.  

## 📊 Problem Statement  
Approximately **45% of LPPO (Local Preferred Provider Organization) members** do not attend preventive visits, leading to **worse health outcomes and financial impacts** on Humana’s **CMS Star ratings**. This project explores the reasons for low engagement and provides **predictive modeling and strategic recommendations** to improve member participation.  

## 📂 Dataset  
The dataset consists of **14 data tables** with **demographic, behavioral, and healthcare utilization information**, including:  
- **Target Members Data**  
- **Medical Visit Claims**  
- **Pharmacy Utilization**  
- **Demographics & Social Determinants of Health**  
- **Healthcare Quality Metrics**  

### **Target Variable:**  
- **Preventive Visit Participation** (Binary: 1 = No Visit, 0 = Visit)  

## 🔍 Exploratory Data Analysis (EDA)  
- **Demographic Analysis:** Trends in preventive visit rates based on race, gender, age, and veteran status.  
- **Geographic Analysis:** Identified states with lower engagement in preventive care.  
- **Feature Engineering:** Created new variables such as **chronic conditions, financial costs, and digital engagement**.  

## 🤖 Machine Learning Models  
To predict **preventive visit non-adherence**, we implemented and compared:  
- **Logistic Regression**  
- **Random Forest**  
- **XGBoost**  
- **LightGBM** *(Selected final model with highest AUC: 0.769)*  

## 🎯 Key Findings  
✅ **Socioeconomic factors** (poverty, income levels) strongly impact preventive visit engagement.  
✅ **Veterans** have a significantly lower engagement rate (only **35.14%** attend preventive visits).  
✅ **Gender disparities** exist, with females having a **higher participation rate** than males.  
✅ **LightGBM model** outperformed others in predicting non-adherence with an accuracy of **70.13%**.  

## 💡 Business Recommendations  
🔹 **Targeted Awareness Campaigns:** Community outreach with **free health screenings & incentives**.  
🔹 **Telehealth Integration:** Increase **digital outreach & virtual consultations** for preventive care.  
🔹 **Mobile Health Clinics:** Deploy services in **low-engagement regions** for better access.  
🔹 **Veteran-Focused Initiatives:** Address **mental health & accessibility barriers** to improve engagement.  

## 🛠 Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Optuna for Hyperparameter Tuning)  
- **Power BI** (Data Visualization)  
- **Excel** (Initial EDA & Report Analysis)  


