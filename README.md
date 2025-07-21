# ml_mnist_practise-code
Code and notes for Chapter 3 - Classification

# MNIST Digit Classification – Chapter 3 Practice (Hands-On ML)

This repository contains my practice implementation from **Chapter 3** of *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron.  
The chapter focuses on a **classification task** using the **MNIST** dataset (handwritten digits 0–9), and applies basic machine learning models to understand how classification works.

---

## 🚀 Project Overview

- **Goal:** Classify grayscale 28x28 images of digits into 10 classes (0 to 9)
- **Dataset:** MNIST (provided by `sklearn.datasets.fetch_openml`)
- **Models Used:**
  - Stochastic Gradient Descent (SGD) Classifier
  - Random Forest Classifier
  - Cross-validation & Confusion Matrix
- **Evaluation Techniques:**
  - Accuracy score
  - Precision, Recall, F1-score
  - Confusion Matrix
  - Error Analysis using images

---

## 🧠 Key Learnings

- How to fetch and visualize MNIST data
- Binary vs. Multiclass classification
- One-vs-One & One-vs-All strategies
- Precision/Recall tradeoff and ROC curves
- Confusion matrix analysis to improve model understanding

---

## 📂 Project Structure

mnist_ch3/
├── mnist_ch3.ipynb         # Jupyter notebook with code and outputs  
├── mnist_ch3.py            # Optional: Script version of the notebook  
├── images/                 # Optional: Saved error analysis or sample digit images  
├── README.md               # Project documentation (this file)  
└── requirements.txt        # List of Python dependencies

---

## 🛠️ Requirements

- Python 3.7+
- scikit-learn
- matplotlib
- numpy
- pandas
- Jupyter Notebook (optional)

Install with:

pip install -r requirements.txt

---

## 📊 Sample Output

- Confusion Matrix
- Digit examples the model got wrong
- Visual ROC curve and PR curve

---

## 📌 Note

This is a **practice project** based on *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron.  
It is meant for **educational use only**.  
All rights for the original content and methods belong to the original author.

---

## 📚 Reference

- [Hands-On Machine Learning (3rd Edition)](https://github.com/ageron/handson-ml3) by Aurélien Géron  
- Scikit-learn Documentation: https://scikit-learn.org/
