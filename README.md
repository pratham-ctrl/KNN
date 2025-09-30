# K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 📌 Overview
This project implements the **K-Nearest Neighbors (KNN)** algorithm for multi-class classification using the **Iris dataset**.  
Objective: Classify flowers into **Setosa, Versicolor, Virginica** based on sepal and petal measurements.

---

## 📂 Project Structure


---

## ⚙️ Steps Performed
1. **Dataset Loading** – Iris dataset from scikit-learn.
2. **Data Preprocessing** – Normalized features with `StandardScaler`.
3. **KNN Classifier** – Implemented with different K values (3, 5, 7, 9).
4. **Evaluation** – Accuracy, Confusion Matrix, Classification Report.
5. **Visualization** – Confusion Matrix heatmap & Decision Boundaries (2D).
6. **Analysis** – Compared performance across different K values.

---

## 📊 Results
- **Best Accuracy (K=5):** ~97%  
- **Confusion Matrix (K=5):**  

- Decision boundaries clearly separate Setosa, Versicolor, Virginica.

---

## 📷 Sample Outputs
### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

### Decision Boundary
![Decision Boundary](decision_boundary.png)

---

## 💡 Key Learnings
- KNN is an **instance-based algorithm** (lazy learning).
- **Normalization** is crucial since KNN relies on distance metrics.
- Smaller K → more variance (overfitting). Larger K → more bias (underfitting).
- Works well for small datasets, but slow for large/high-dimensional ones.

---

## 🚀 How to Run
1. Clone this repository:
 ```bash
 git clone https://github.com/your-username/KNN-Classification-Task.git
 cd KNN-Classification-Task
