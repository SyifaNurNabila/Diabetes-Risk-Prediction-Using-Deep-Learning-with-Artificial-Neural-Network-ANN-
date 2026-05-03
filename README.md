# Diabetes Risk Prediction Using Deep Learning (Artificial Neural Network)

## Project Overview
This project focuses on predicting the risk of diabetes using a Deep Learning approach based on an Artificial Neural Network (ANN) model. The model is trained using the NHANES (National Health and Nutrition Examination Survey) dataset, which contains clinical, demographic, and laboratory data.

The goal of this research is to develop a data-driven predictive system that can assist early detection of diabetes risk using machine learning techniques.

---

## Machine Learning Approach
- Algorithm: Artificial Neural Network (ANN)
- Type: Feed-forward Neural Network
- Framework: TensorFlow / Keras
- Problem Type: Binary Classification

---

## Dataset
- Source: NHANES Dataset (CDC)
- Size: 52,390 records
- Features: 45 clinical and demographic variables
- Target:
  - 0 = Non-diabetes
  - 1 = Diabetes

Dataset link:
https://github.com/hongweihaha/Diabetes-NHANESDataset/blob/main/Diabetes-NHANESDataset.csv

---

## Data Preprocessing
The following preprocessing steps were applied:
- Handling missing values using median imputation
- Feature engineering (clinical feature relationships)
- Dimensionality reduction using PCA
- Data normalization using StandardScaler
- Train-test split (80:20 stratified)

---

## Model Architecture
- Input Layer: 5 PCA components
- Hidden Layer 1: 64 neurons (ReLU)
- Hidden Layer 2: 32 neurons (ReLU)
- Output Layer: 1 neuron (Sigmoid)

---

## Evaluation Metrics
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

## Results Summary
- Best model accuracy: ~85%
- Stable performance across regularization techniques
- Challenge: class imbalance affecting recall for diabetes class
- SMOTE improved recall but reduced overall generalization

---

## Tools & Technologies
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- Google Colab

---

## Conclusion
This project demonstrates that ANN-based models can effectively be used for diabetes risk prediction using structured medical data. However, class imbalance remains a key challenge that requires further optimization techniques.

---

## 🔒 Copyright Notice

© 2026 Syifa Nur Nabila & Contributors. All Rights Reserved.

This project is created for academic purposes only.  
Unauthorized copying, redistribution, modification, or commercial use of this project or its contents is strictly prohibited without explicit permission from the authors.

This includes:
- Source code
- Report/documentation
- Dataset preprocessing pipeline
- Model architecture and implementation

---

## ⚖️ License
This project is protected under a **Custom "All Rights Reserved" License**.

You are allowed to:
- View the project for educational purposes only

You are NOT allowed to:
- Copy or reuse code
- Modify and redistribute
- Use for commercial purposes
- Publish without permission

For collaboration or permission requests, please contact:
syifanurnabila.contact@gmail.com

## Copyright

© 2026 Syifa Nur Nabila. All rights reserved.

This repository is for academic purposes only.  
No part of this project may be copied, modified, or redistributed without permission.
