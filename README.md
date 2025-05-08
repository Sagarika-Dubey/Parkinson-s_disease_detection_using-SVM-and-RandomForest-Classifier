# Parkinson’s Disease Detection using SVM and Random Forest

## 📁 Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set/data)
- **Dataset**: Parkinson’s Disease Data Set
- **Credits**: Vikas Ukani

## 🩺 Problem Statement
This project aims to detect whether a person has Parkinson’s disease using vocal and biomedical measurements.

**Parkinson’s disease** is a progressive nervous system disorder that affects movement. It causes shaking, stiffness, and difficulty with balance and coordination. Symptoms worsen over time, making early detection essential.

## 🧪 Approach

### 🔧 Preprocessing
- Applied feature scaling using `StandardScaler`
- Reshaped the input for prediction compatibility

### 🤖 Models Used
- **Support Vector Machine (SVM)** with `SVC` for baseline performance
- **Random Forest Classifier** to improve accuracy and handle non-linear patterns

### 📈 Evaluation
- SVM served as a baseline classifier.
- Random Forest showed higher accuracy and better generalization on test data.

## ✅ Results
The final model predicts whether a person is likely to have Parkinson’s disease based on the provided features. Random Forest outperformed SVM in terms of accuracy and robustness.

## Getting Started

### Dependencies
- Python 3.x
- `scikit-learn`
- `numpy`
- `pandas`

### Installation
```bash
pip install numpy pandas scikit-learn 
