# 🧬 Breast Cancer Detection using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a tumor is **malignant (cancerous)** or **benign (non-cancerous)** using machine learning algorithms. The model is trained on a breast cancer dataset and evaluates multiple classification techniques to achieve accurate predictions.

---

## 🎯 Objectives

* Analyze breast cancer dataset
* Perform data preprocessing and feature scaling
* Train multiple machine learning models
* Compare performance of different classifiers
* Predict cancer diagnosis with high accuracy

---

## 📊 Dataset

The dataset used in this project contains medical features such as:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness

Target variable:

* **0 → Benign**
* **1 → Malignant**

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas (Data handling)
* NumPy (Numerical operations)
* Matplotlib & Seaborn (Visualization)
* Scikit-learn (Machine Learning)

---

## 🔍 Machine Learning Models Used

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

## 🚀 Workflow

1. Import libraries
2. Load dataset (`breast_cancer_data.csv`)
3. Data preprocessing
4. Split dataset into training and testing sets
5. Feature scaling using StandardScaler
6. Train multiple models
7. Evaluate models using:

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

---

## 📈 Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 🧪 Results

The models are evaluated and compared to determine which performs best for breast cancer detection. Typically:

* Random Forest gives higher accuracy
* Logistic Regression provides good baseline performance

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install dependencies:

   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the notebook:

   ```
   jupyter notebook Brest_cancer.ipynb
   ```

---

## 📂 Project Structure

```
├── Brest_cancer.ipynb
├── breast_cancer_data.csv
├── model.bin (optional)
└── README.md
```

---

## ⚠️ Notes

* Ensure dataset file is in the same directory
* If using Google Colab, upload dataset manually
* Large `.bin` files may not upload directly to GitHub

---

## 💡 Future Improvements

* Use Deep Learning models (ANN/CNN)
* Hyperparameter tuning
* Deploy as a web app
* Use real-world medical datasets

---

## 📌 Conclusion

This project demonstrates how machine learning can assist in early detection of breast cancer, helping improve diagnosis accuracy and decision-making in healthcare.

---

