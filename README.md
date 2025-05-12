# Feature-Transformation
# 🔄 Feature Transformation using PCA & LDA

This repository explores two fundamental dimensionality reduction techniques in machine learning: **Principal Component Analysis (PCA)** and **Linear Discriminant Analysis (LDA)**. These techniques are implemented on two classic datasets to demonstrate their utility in reducing dimensionality while retaining essential data characteristics.

---

## 📌 Project Overview

### 1. 🍷 PCA on Wine Dataset

**Principal Component Analysis (PCA)** is an unsupervised learning method used for transforming high-dimensional data into fewer dimensions while preserving most of the variance.

#### 🎯 Objective
To apply PCA on the Wine dataset to reduce dimensionality while retaining key information, simplifying the analysis and aiding in visual distinction between wine types.

#### ✅ Key Outcomes
- Successfully reduced dimensionality while preserving ~95% of the dataset’s variance.
- Identified that the **first two principal components** capture the majority of the data’s variability.
- Visualized the transformed dataset showing clear separation of wine classes.

#### 📊 Applications
- Dimensionality reduction
- Data visualization
- Improved model performance by reducing multicollinearity

---

### 2. 🌸 LDA on Iris Dataset

**Linear Discriminant Analysis (LDA)** is a supervised learning technique used to reduce feature dimensions by maximizing class separability.

#### 🎯 Objective
To use LDA on the Iris dataset to project data into a space that best separates the three flower species (Setosa, Versicolor, Virginica).

#### ✅ Key Outcomes
- Achieved effective **class separation** in lower-dimensional space.
- Improved classification performance with more interpretable visualizations.
- Demonstrated LDA's utility in **supervised dimensionality reduction**.

#### 📊 Applications
- Preprocessing for classification tasks
- Class-based feature extraction
- Noise reduction
  ---

## 🧰 Tools & Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
