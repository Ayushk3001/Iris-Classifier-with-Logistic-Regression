# 🌸 Iris Classifier with Logistic Regression

A clean, end‑to‑end ML demo that trains a **Logistic Regression** model to classify **Iris** flower species using sepal/petal measurements. Built as a Jupyter Notebook (`MLDemo2.ipynb`) for clarity and learning.

---

## 📌 Project Overview
This notebook walks through a minimal, production‑style workflow:

1. Load data
2. Preprocess & split
3. Scale features
4. Train Logistic Regression
5. Evaluate on a hold‑out set
6. Predict on new samples

It’s ideal for beginners who want a compact example of the classical ML pipeline.

---

## 📂 Dataset
- **Source (Kaggle):** https://www.kaggle.com/datasets/saurabh00007/iriscsv  
- **Samples:** 150  
- **Features:** SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm  
- **Labels:** Iris-setosa, Iris-versicolor, Iris-virginica

> ℹ️ Download the CSV from Kaggle and place it at `data/Iris.csv` (or update the path in the notebook).

---

## 🛠️ Tech Stack
- **Python 3.x**
- **NumPy**, **pandas**
- **scikit-learn** (LogisticRegression, train_test_split, StandardScaler)
- **Jupyter Notebook**

---

## 🧪 What You’ll See
- **Accuracy** on test split (typically ~0.9–0.97 depending on random state)
- **Predictions** for sample inputs
- Clean, well‑commented cells showing each step of the pipeline

---

## 📊 Nice Extensions (Optional)
- Confusion matrix & classification report
- Decision boundary plots (for 2D projections)
- Trying other models: SVM, RandomForest, KNN
- Simple web demo via **Streamlit** or **Flask**

---

## 📁 Project Structure (suggested)
```
.
├─ MLDemo2.ipynb            # main notebook
├─ data/
│  └─ Iris.csv              # Kaggle dataset file
├─ requirements.txt         # dependencies (optional)
└─ README.md
```

**Example `requirements.txt`:**
```
numpy
pandas
scikit-learn
jupyter
```

---

## 🙌 Credits
- Dataset by **Saurabh** on Kaggle: https://www.kaggle.com/datasets/saurabh00007/iriscsv
- Original Iris dataset attributed to Fisher (1936)

---

## 📜 License
This repository is for educational purposes. Please review the Kaggle dataset’s terms of use on its page before redistribution.
