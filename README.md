# 🪨 Rock vs Mine Prediction

A beginner machine learning project that classifies sonar signals as either **Rock** or **Mine** using Logistic Regression.

---

## 📌 Project Overview

Sonar works by sending sound waves and analyzing the echo. This project trains a model on those echo readings to predict whether the object underwater is a rock or a naval mine — a classic binary classification problem.

- **Algorithm:** Logistic Regression
- **Dataset:** UCI Sonar Dataset (208 samples, 60 features)
- **Language:** Python

---

## 📊 Dataset

| Property | Value |
|---|---|
| Total Samples | 208 |
| Features | 60 sonar frequency readings |
| Classes | Rock (R), Mine (M) |
| Train / Test Split | 90% / 10% (stratified) |

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))

---

## 🛠️ Tech Stack

- Python 3.x
- NumPy
- Pandas
- Scikit-learn

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/rock-vs-mine-prediction.git
   cd rock-vs-mine-prediction
   ```

2. **Install dependencies**
   ```bash
   pip install numpy pandas scikit-learn jupyter
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook Rock_vs_Mine_Prediction.ipynb
   ```

---

## 📁 Project Structure

```
rock-vs-mine-prediction/
├── Rock_vs_Mine_Prediction.ipynb   # Main notebook
├── sonar_data.csv                  # Dataset
└── README.md                       # You are here
```

---

## 📈 Results

| Metric | Score |
|---|---|
| Training Accuracy | ~83% |
| Test Accuracy | ~76% |

---

## ⚠️ Limitations

- Small dataset (208 samples) — may not generalize to real-world sonar data
- No feature scaling applied (can improve results with `StandardScaler`)
- Single train/test split — results vary with different `random_state` values

---

## 🧠 What I Learned

- Loading and exploring data with Pandas
- Splitting data using `train_test_split` with stratification
- Training and evaluating a Logistic Regression model with Scikit-learn
- Building a basic prediction system from a trained model

---

## 📚 Acknowledgements

- Dataset from the [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))
- Built as part of my machine learning learning journey
