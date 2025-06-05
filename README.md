# AIML-Task-7-Support-Vector-Machines-SVM-
# 🧠 Task 7: Support Vector Machines (SVM)

## 📌 Objective
Train and evaluate SVM classifiers using both **linear** and **RBF (non-linear)** kernels on a binary classification dataset (Breast Cancer), and visualize decision boundaries.

---

## 📂 Dataset
- **Name**: Breast Cancer Wisconsin Dataset
- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Classes**: Malignant (1), Benign (0)
- **Features**: 30 numerical features (mean, error, worst of radius, texture, etc.)

---

## 🛠 Tools & Libraries
- Python 3  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn

---

## 🚀 Workflow

1. Load and normalize dataset
2. Train SVM using:
   - Linear Kernel
   - RBF Kernel
3. Evaluate models using accuracy, confusion matrix, classification report
4. Tune `C` and `gamma` using `GridSearchCV`
5. Use 5-fold cross-validation
6. Optional: Visualize decision boundary using 2D features

---

## 📊 Results

| Model               | Accuracy |
|---------------------|----------|
| SVM (Linear Kernel) | ~96–97%  |
| SVM (RBF Kernel)    | ~97–98%  |
| RBF + GridSearchCV  | ~98%     |

---

📃Created by: [MUMMADI RAMCHARAN]
