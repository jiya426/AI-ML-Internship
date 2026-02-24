
# 📌 K-Nearest Neighbors (KNN) Classification

### AI & ML Internship – Task 6

## 🔍 Project Overview

This project implements the **K-Nearest Neighbors (KNN)** algorithm for solving a classification problem.
KNN is an instance-based learning algorithm that classifies data points based on the majority class of their nearest neighbors.

The model was trained and evaluated using Scikit-learn, and different values of **K** were tested to analyze performance.

---

## 🎯 Objective

* Implement KNN classifier using Scikit-learn
* Normalize features before training
* Experiment with different values of K
* Evaluate model performance
* Visualize decision boundaries

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```id="knn12x"
├── Task6.ipynb           # Implementation notebook
├── dataset.csv           # Dataset used (e.g., Iris Dataset)
├── task 6.pdf            # Internship task instructions
├── README.md             # Project documentation
```

---

## ⚙️ Implementation Steps

1. Imported and explored the dataset
2. Performed feature normalization (scaling)
3. Split data into training and testing sets
4. Applied KNeighborsClassifier
5. Experimented with different values of K
6. Evaluated model using:

   * Accuracy Score
   * Confusion Matrix
7. Visualized decision boundaries

---

## 📊 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Performance comparison for different K values

### 🔎 Observations

* Smaller K values may cause overfitting.
* Larger K values may lead to underfitting.
* Normalization is important because KNN is distance-based.

---

## 📘 Concepts Covered

* Instance-Based Learning
* Euclidean Distance
* Distance Metrics
* Feature Scaling
* Overfitting & Underfitting
* Multi-class Classification

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash id="knn33y"
git clone https://github.com/your-username/knn-classification.git
```

2. Install required libraries:

```bash id="knn44z"
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash id="knn55a"
jupyter notebook
```

4. Run `Task6.ipynb`

---

## 📈 What I Learned

* How KNN works using nearest neighbors
* Importance of selecting the right K value
* Why normalization is necessary
* How distance metrics impact model performance

---

## 👩‍💻 Author

**Jiya Jain**
B.Tech Computer Science
AI/ML & Data Science Intern
