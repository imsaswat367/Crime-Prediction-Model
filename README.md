## A Machine Learning Approach for Crime Classification and Prediction

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-97.3%25%20Accuracy-success)
![License](https://img.shields.io/badge/License-Academic-orange)

---

## 📖 Overview

Crime prediction has become a critical challenge in modern smart cities, helping law enforcement agencies improve public safety through data-driven decision-making.

This research presents a **Machine Learning-based Crime Classification and Prediction Framework** that combines:

- 🔹 Support Vector Machine (SVM) for Crime Classification
- 🔹 XGBoost for Crime Prediction
- 🔹 SMOTE for Class Imbalance Handling
- 🔹 Spatial and Temporal Feature Analysis

The proposed framework was evaluated using the **Chicago Crime Dataset** and achieved a remarkable prediction accuracy of **97.3%**, demonstrating the effectiveness of ensemble learning techniques in predictive policing.

---

##  Research Objectives

- Predict future crime occurrences using historical crime records.
- Classify different categories of crimes accurately.
- Handle class imbalance using SMOTE.
- Identify important temporal and spatial crime patterns.
- Support law enforcement agencies in proactive crime prevention.

---

##  Proposed Framework

```text
Raw Crime Data
        │
        ▼
Data Preprocessing
        │
        ▼
Class Imbalance Handling
      (SMOTE)
        │
        ▼
Crime Classification
       (SVM)
        │
        ▼
Crime Prediction
     (XGBoost)
        │
        ▼
Performance Evaluation
```

---

## 📊 Dataset

The experiments were conducted using the **Chicago Crime Dataset**, containing crime incidents reported by the Chicago Police Department.

### Dataset Features

- Crime Type
- Date and Time
- Location Description
- Arrest Status
- District
- Latitude & Longitude
- Spatial and Temporal Attributes

### Dataset Source

🔗 https://www.kaggle.com/

---

##  Methodology

###  Data Preprocessing

- Missing Value Handling
- Duplicate Removal
- Feature Scaling
- Label Encoding
- Feature Selection

###  Class Imbalance Handling

To address the imbalance among crime categories, **SMOTE (Synthetic Minority Over-sampling Technique)** was used.

Benefits:

- Better minority class learning
- Improved model generalization
- Reduced prediction bias

###  Crime Classification using SVM

Support Vector Machine was used to classify different crime categories based on historical patterns.

###  Crime Prediction using XGBoost

XGBoost was employed to forecast future crime occurrences and demonstrated superior predictive performance.

---

#  Experimental Results

## Support Vector Machine (SVM)

| Metric | Score |
|----------|--------|
| Accuracy | 53.2% |
| Precision | 48% |
| Recall | 53% |
| F1-Score | 42.52% |

---

## XGBoost

| Metric | Score |
|----------|--------|
| Accuracy | **97.3%** |
| Precision | **98%** |
| Recall | **97%** |
| F1-Score | **96.67%** |

---

##  Performance Comparison

| Algorithm | Accuracy | Precision | Recall | F1 Score |
|------------|------------|------------|------------|------------|
| SVM | 53.2% | 48% | 53% | 42.52% |
| XGBoost | **97.3%** | **98%** | **97%** | **96.67%** |

### Key Observation

✅ XGBoost significantly outperformed SVM across all evaluation metrics.

✅ Ensemble learning effectively captured complex crime patterns.

✅ The model demonstrated strong generalization capabilities.

---

## 🛠️ Technologies Used

- Python
- Scikit-Learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Imbalanced-Learn (SMOTE)
- Google Colab

---

## 📂 Repository Structure

```text
CrimePredict/
│
├── Crime_Prediction_Paper.pdf
├── crime_prediction.py
├── svm_model.py
├── xgboost_model.py
├── preprocessing.py
├── requirements.txt
├── dataset/
│   └── chicago_crime_dataset.csv
│
└── README.md
```


---

## 🌟 Key Contributions

- Developed a hybrid crime prediction framework.
- Integrated SMOTE for class imbalance handling.
- Applied SVM for crime classification.
- Applied XGBoost for crime forecasting.
- Achieved **97.3% prediction accuracy**.
- Provided insights into temporal and spatial crime patterns.
- Demonstrated the effectiveness of ensemble learning for predictive policing.

---

##  Publication

### A Machine Learning Approach for Crime Classification and Prediction

Published in **SN Computer Science (Springer Nature)**

DOI:

https://doi.org/10.1007/s42979-025-04679-7

---

##  Authors

- Sanjit Kumar Dash
- Surajit Mohanty
- **Saswat Choudhury**
- Aanchal Mohanty
- Pulak Ranjan Mohanty
- Biranchi Kumar Nayak

---

## Citation

@article{dash2026crimeprediction,
  title={A Machine Learning Approach for Crime Classification and Prediction},
  author={Dash, Sanjit Kumar and Mohanty, Surajit and Choudhury, Saswat and Mohanty, Aanchal and Mohanty, Pulak Ranjan and Nayak, Biranchi Kumar},
  journal={SN Computer Science},
  volume={7},
  pages={74},
  year={2026},
  publisher={Springer Nature}
}


