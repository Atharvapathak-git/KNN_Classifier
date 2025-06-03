# 🔍 K-Nearest Neighbors (KNN) Classifier

This project implements a **K-Nearest Neighbors (KNN)** classification algorithm using a real-world dataset. It includes data preprocessing, feature scaling, model training, and evaluation using accuracy metrics and visualizations.

## 📁 Dataset

**File:** `KNNAlgorithmDataset.csv`  
The dataset includes features used for classification tasks, such as:

- Age
- Salary
- Purchased (Target variable)

## 📌 Features of the Project

- Loading and inspecting dataset
- Handling missing data (if any)
- Feature scaling using `StandardScaler`
- Splitting data into training and testing sets
- Implementing the KNN classifier using `scikit-learn`
- Evaluating model using:
  - Confusion Matrix
  - Accuracy Score
- Visualizing decision boundaries

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **scikit-learn**

## 📊 Key Steps

1. Load and explore dataset
2. Scale features to improve KNN performance
3. Train KNN classifier with optimal `k` value
4. Predict and evaluate results on the test set
5. Visualize decision boundary (2D feature space)

## ▶️ How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

