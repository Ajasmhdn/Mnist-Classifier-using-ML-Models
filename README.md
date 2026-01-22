# MNIST Classifier using ML Models

This project focuses on building a **handwritten digit classifier** using the popular **MNIST dataset**.  
Multiple **Machine Learning models** are trained and compared to classify digits from **0 to 9**.

---

## 📌 Project Overview

MNIST is a benchmark dataset in Machine Learning and Computer Vision.  
In this project, we:

- Load and preprocess MNIST images
- Convert images into usable input for ML models
- Train different ML classification models
- Evaluate and compare model performance
- Predict handwritten digits from test samples / user input

---

## 🧠 Models Used

The following ML models are trained and evaluated:

✅ Logistic Regression  
✅ K-Nearest Neighbors (KNN)  
✅ Support Vector Machine (SVM)  
✅ Decision Tree  
✅ Random Forest  
✅ Naive Bayes (optional)  

> (You can update this list based on what you actually implemented)

---

## 🗂 Dataset

- Dataset: **MNIST Handwritten Digits**
- Total images: **70,000**
  - Training: 60,000
  - Testing: 10,000
- Image size: **28 × 28 grayscale**
- Classes: **10 digits (0–9)**

---

## 🔧 Preprocessing Steps

- Normalization (0–255 → 0–1)
- Flattening images (28×28 → 784 features) for ML models
- Train-test split (or use official MNIST split)

---

## ⚙️ Requirements

Install required libraries:

```bash
pip install -r requirements.txt
