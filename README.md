# predictive-analytics-lab-exam-2
# Predictive Analytics Lab Exam-2

##  Objective

This project performs a **binary classification task** using machine learning. It includes data preprocessing, exploratory data analysis (EDA), model training, decision boundary visualization, and performance evaluation.

---

## Dataset

* File: `Lab_Exam_binary_classification_dataset.xlsx`
* The dataset contains multiple features and a target column named **Target**
* Target values:

  * **Yes → 1**
  * **No → 0**

---

##  Exploratory Data Analysis (EDA)

The following analysis was performed:

* Displayed dataset structure using `.info()` and `.describe()`
* Checked for missing values using `.isnull()`
* Removed rows with missing target values
* Visualized feature distributions using histograms
* Generated correlation heatmap using Seaborn

---

##  Data Preprocessing

* Converted categorical target values into numeric format
* Split data into training and testing sets (80% training, 20% testing)
* Applied **StandardScaler** for feature normalization

---

## Models Implemented

### 🔹 Logistic Regression

* Used as an initial classification model

### 🔹 Support Vector Machine (SVM)

* Kernel: RBF
* Used scaled features
* Provided better performance compared to baseline

---

## Decision Boundary Visualization

* Used first two features for visualization
* Created mesh grid to plot classification regions
* Displayed training and testing points with different styles
* Saved plot as: `decision_boundary.png`

---

##  Model Evaluation

### Metrics Used:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

### Output:

* Printed accuracy of the model
* Displayed confusion matrix (raw and normalized)
* Generated detailed classification report

---

##  Cross-Validation

* Performed **5-Fold Cross Validation**
* Calculated:

  * Mean accuracy
  * Standard deviation

---

##  Results Summary

* Model: SVM (RBF Kernel)
* Train/Test Split: 80% / 20%
* Achieved good classification performance
* Balanced results across both classes (Yes / No)

---

##  Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Files Included

* Python code file (`.py`)
* Dataset (`.xlsx`)
* Output images:

  * Decision boundary plot
  * Confusion matrix

---

##  Conclusion

The SVM model successfully classified the dataset with high accuracy. Proper preprocessing, scaling, and visualization contributed to improved model performance.

---
