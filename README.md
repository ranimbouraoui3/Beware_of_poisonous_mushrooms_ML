# 🍄 Beware_of_poisonous_mushrooms - Machine Learning Project

This project uses machine learning to classify mushrooms as **edible** or **poisonous** based on their physical characteristics. The dataset used is the Mushrooms Dataset, which contains categorical features describing each mushroom sample.

## 📌 Objectives

- Preprocess and encode categorical data
- Train and optimize models:
  - **K-Nearest Neighbors (KNN)**
  - **Decision Tree Classifier**
- Evaluate models using:
  - **Accuracy**, **Recall (TPR)**, **Precision**
  - **ROC Curve**, **Precision-Recall Curve**
- Visualize decision boundaries and model logic

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

## 📊 Results Highlights

- **KNN** optimized with GridSearchCV for `n_neighbors` and `distance` metric
- **Decision Tree** tuned for depth, split rules, and leaf size
- **Perfect accuracy** on test set (overfitting is analyzed)
- Visualization of:
  - ROC and PR curves
  - Final decision tree

## 📂 Structure

```
├── mushrooms/                    # Dataset and preprocessing  
├── Beware_of_poisonous_mushrooms/ # Jupyter notebooks for exploration  
└── README.md                     # Project overview and instructions  
```


## 🚀 Goal

To explore model performance on a real-world classification task, understand trade-offs between accuracy and interpretability, and practice applying ML workflows end-to-end.
