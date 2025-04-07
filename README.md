
# Enhancing Student Success: Predicting Early Dropout and At-Risk Students

🚀 **Empowering education with data-driven insights to enhance student success.**

<img width="1066" alt="image" src="https://github.com/SanketKumarP/Student-Success-Prediction/blob/2c77e409115572a8003999ea6b921a92c354dac1/Poster_Presentation.png">

## Overview
This project focuses on predicting early student dropouts and at-risk students using advanced machine learning models on the Open University Learning Analytics Dataset (OULAD). By leveraging time series data and meta modeling approaches, our goal is to proactively identify students in need of support to improve educational outcomes.

## Dataset
**OULAD** - The Open University Learning Analytics Dataset, which includes:
- Demographics
- Assessment results
- Virtual Learning Environment (VLE) interaction data

---

## Key Features
- **Predictive Modeling**:  
  Developed machine learning models, including **Time Series Forest (TSF)**, **Random Forest (RF)**, and **XGBoost**, for high accuracy in predicting at-risk students.

- **Meta-Modeling**:  
  Combined demographic, behavioral, and assessment data to achieve superior performance metrics.

- **Class Imbalance Handling**:  
  Applied **SMOTE** to address data imbalance and improve model fairness.

- **Feature Engineering**:  
  - Time-series data extraction  
  - Clustering (K-Prototypes, K-Means) for better data segmentation  
  - Analysis of submission patterns and activity rates

---

## Tech Stack
- **Programming Language**: Python  
- **Tools & Platforms**:  
  - Google Colab  
  - VS Code  
- **Libraries Used**:  
  - `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`  
  - `imbalanced-learn`, `xgboost`, `time-series-forest`

---

## Project Workflow
1. **Data Preprocessing**:  
   - Cleaned and transformed raw data  
   - Handled missing values and normalized features  

2. **Feature Engineering**:  
   - Extracted time-series features  
   - Clustering for behavioral segmentation  

3. **Model Training and Evaluation**:  
   - Built and fine-tuned ML models  
   - Evaluated using AUC, Recall, Accuracy  

4. **Insights Generation**:  
   - Identified trends influencing student success  

---

## Key Results

### Dropout Prediction
- **Best Model:** Sampled Time Series Forest  
- Recall: Up to 90.9%  
- AUC: Up to 92.8%  
- Accuracy: Up to 85.7%

### At-Risk Prediction
- **Best Model:** Meta Model  
- Recall: Up to 85.1%  
- AUC: Up to 96.3%  
- Accuracy: Up to 91.3%

---

## Lessons Learned
- Importance of data preprocessing and feature engineering  
- Combining various data types improves model accuracy  
- Meta modeling and time series models outperform traditional ML approaches

## Future Work
- Model deployment for real-time use  
- Build dashboards for educational stakeholders  
- Explore additional advanced ML techniques

---

## Team Members
- Sanketkumar Patel
- Bala Gopinath Kuchibatla
- Abhi Subramaniyam Kamuju
- Rajashekar Allam
- Kyung Jin Kwak

## Instructor
Prof. Yong Zheng  
Illinois Institute of Technology

## Acknowledgements
This project was developed as part of the Data Science Practicum course at Illinois Institute of Technology under the guidance of Prof. Yong Zheng.
