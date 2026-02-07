# SVM
# 🚀 End-to-End SVM Classification Platform

A Streamlit-based web application that demonstrates a complete Machine Learning pipeline using Support Vector Machine (SVM).

🔗 Live App: https://v69zor7x25uhrxgvbtxkbl.streamlit.app/

---

## 📌 Features

- Upload CSV or download Iris dataset
- Perform basic EDA (shape, missing values, correlation heatmap)
- Handle missing values (Mean / Median / Drop rows)
- Save cleaned datasets
- Train SVM classifier with configurable:
  - Kernel (linear, poly, rbf, sigmoid)
  - C (Regularization)
  - Gamma
- View Accuracy and Confusion Matrix

---

## 🛠 Tech Stack

- Python
- Streamlit
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## ▶️ Run Locally

```bash
git clone <your-repo-link>
cd <repo-name>
pip install -r requirements.txt
streamlit run app.py
