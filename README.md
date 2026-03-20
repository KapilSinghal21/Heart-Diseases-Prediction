# ❤️ Heart Disease Prediction using Logistic Regression

This project predicts whether a patient is **likely to have heart disease** based on medical attributes from the **UCI Heart Disease dataset** using a Logistic Regression model.

---

## 📌 Project Overview
Heart disease is one of the leading causes of death globally.  
Early detection can help in timely medical intervention and prevention of severe health complications.  

In this project, we:
- Load and preprocess the dataset
- Train a *Logistic Regression* model
- Evaluate its performance using metrics like accuracy, precision, recall, and F1-score
- Create a prediction pipeline for new patient data

---

## 📂 Dataset
- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)  
- **Instances:** 303 samples  
- **Features:** 13 medical attributes (e.g., age, cholesterol level, blood pressure)  
- **Target:**  
  - 0 → No Heart Disease  
  - 1 → Heart Disease  

---

## 🛠️ Technologies Used
- *Python 3.x*
- *Pandas* – data manipulation  
- *NumPy* – numerical computations  
- *Matplotlib / Seaborn* – data visualization  
- *Scikit-learn* – model building and evaluation  

---

## 📊 Model Performance
| Metric      | Score |
|-------------|-------|
| Accuracy    | 85%   |
| Precision   | 83%   |
| Recall      | 87%   |
| F1-Score    | 85%   |

> The model achieves good accuracy and recall, making it effective for early screening.

## 📈 Visualization
- **Feature distribution** to understand data spread  
- **Correlation heatmap** to identify relationships between features.  
- **Confusion matrix** to evaluate classification results.  

---

## 🔮 Future Improvements
- Deploy as a **Streamlit web app** for real-time predictions.
- Try advanced models like **Random Forest** or **XGBoost**.  
