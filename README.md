# Hybrid Ensemble-Based Water Quality Prediction

This project presents a hybrid machine learning framework for water quality classification using ensemble boosting algorithms combined with deep learning models.

---

## 🚀 Models Implemented

- AdaBoost + ANN (Proposed)
- LightGBM + ANN
- LightGBM + LSTM
- XGBoost + ANN
- CatBoost + ANN

---

## 📊 Workflow

1. Data preprocessing
2. Feature scaling
3. Hybrid model training
4. Performance evaluation using Accuracy, Precision, Recall, F1-score
5. Comparative analysis

---

## 🛠 Tech Stack

Python, Scikit-learn, TensorFlow/Keras, LightGBM, XGBoost, CatBoost, NumPy, Pandas, Matplotlib

---

## 📈 Results

The AdaBoost + ANN model achieved the best classification performance among all tested models.

Algorithm     	Accuracy   Precision 	Recall 	F1-Score
XGBoost + ANN	   0.8994	     0.89	     0.90	    0.89
CatBoost + ANN	 0.8994	     0.90	     0.91   	0.90
LightGBM + LSTM  0.9000	     0.89	     0.90	    0.89
LightGBM + ANN	 0.9081	     0.90	     0.91	    0.90
AdaBoost + ANN	 0.9213	     0.92	     0.92	    0.92


---

## 📌 Research Status

Conference paper submitted (Under Review).

---

## ▶️ How to Run

```bash
git clone https://github.com/SUNDAR-RAJAAN/Water-Quality-Hybrid-Model.git
cd Water-Quality-Hybrid-Model
pip install -r requirements.txt
