# 🌸 Iris Classification using XGBoost

## 📌 Project Overview
This project performs classification on the Iris dataset using the XGBoost algorithm.  
It also demonstrates how to handle a common machine learning error related to label encoding.



## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost



## 🧠 Key Concepts
- Label Encoding
- Train-Test Split
- XGBoost Classifier
- Model Training



## ❌ Problem Faced
During model training, an error occurred:
Invalid classes inferred from y



## ✅ Solution
The issue was fixed by properly encoding the target variable:
```python
y = LabelEncoder().fit_transform(y)
