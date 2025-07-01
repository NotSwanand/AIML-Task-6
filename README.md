# 🤖 Iris Flower Classification – K-Nearest Neighbors (KNN)

## 📌 Objective
Implement and understand the K-Nearest Neighbors (KNN) algorithm to classify iris flower species based on sepal and petal measurements.

---

## 📁 Dataset
- **Source**: [Iris Dataset (Kaggle / UCI ML Repo)](https://www.kaggle.com/datasets/uciml/iris)
- **File Used**: `Iris.csv`

---

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Scikit-learn (KNN, metrics, scaling)
- Matplotlib, Seaborn

---

## ✅ Steps Performed

### 1. Data Preparation
- Loaded the dataset from `Iris.csv`
- Confirmed no missing values
- Features: `sepal length`, `sepal width`, `petal length`, `petal width`
- Target: Class label (0, 1, 2) representing species

### 2. Feature Normalization
- Used `StandardScaler` to normalize features
- **Why?**: KNN is a distance-based algorithm, so feature scales must be equal

### 3. Train-Test Split
- 80% training, 20% testing using `train_test_split`

### 4. KNN Model Training
- Trained KNN models for `k = 1` to `k = 20`
- Plotted **Accuracy vs K** to choose the optimal `k`

### 5. Final Model (K = 5)
- Trained `KNeighborsClassifier(n_neighbors=5)`
- Evaluated using accuracy, confusion matrix, and classification report

---

## 📊 Evaluation

### ✅ Confusion Matrix:
[[10 0 0]
[ 0 9 0]
[ 0 0 11]]


### ✅ Classification Report:
- **Accuracy**: 100%
- **Precision, Recall, F1-Score**: All **1.00**

---

## 📈 Visualization
- **Line plot** of accuracy vs K (1–20)
- (Optional) Decision boundary plot for 2D version using first 2 features

---

## 📂 Files Included
- `Task6.ipynb` – Notebook with all steps and plots
- `Iris.csv` – Dataset used
- `README.md` – Documentation of the task

---

## 📝 Submission
This project was completed as part of the **AI & ML Internship**  
**Task 6: K-Nearest Neighbors Classification**

