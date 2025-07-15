

# ❤️ Heart Disease Prediction using Decision Trees & Random Forests

This project applies **Decision Tree** and **Random Forest** classifiers to predict the presence of heart disease based on patient attributes. It also analyzes overfitting, tunes model depth, evaluates performance using cross-validation, and interprets feature importances.

---

## 📌 Project Summary

* **Dataset:** 1025 records with 14 clinical features (e.g., age, cholesterol, resting blood pressure, etc.)
* **Target:** `1` → Heart disease present, `0` → No disease

---

## 🔍 Project Workflow

### ✅ 1. Data Loading & Exploration

* Loaded dataset using `pandas`
* Checked data types, missing values, and dataset structure
* Confirmed no null entries

### ✅ 2. Decision Tree Classifier

* Trained a `DecisionTreeClassifier` on the training data
* Visualized the decision tree using `plot_tree`
* Analyzed **overfitting** by varying `max_depth` from 1 to 20
* Plotted training and test accuracy vs. tree depth

### ✅ 3. Random Forest Classifier

* Trained a `RandomForestClassifier` with 100 trees
* Achieved **Test Accuracy: 98.5%**
* Trained model showed **perfect accuracy on training data (100%)**

### ✅ 4. Feature Importance

* Ranked the importance of each feature using the trained random forest
* Visualized important features using a `Seaborn` barplot

### ✅ 5. Cross-Validation

* Performed **5-fold cross-validation**
* **Mean Accuracy:** 99.7%
* **Standard Deviation:** 0.0058

---

## 📈 Evaluation Metrics

| Model         | Train Accuracy  | Test Accuracy       | CV Mean Accuracy |
| ------------- | --------------- | ------------------- | ---------------- |
| Decision Tree | Varies by depth | Peaks around 85–90% | —                |
| Random Forest | 100%            | **98.5%**           | **99.7%**        |

---

## 🧠 Techniques & Concepts Used

* Decision Tree & Random Forest (Ensemble Learning)
* Overfitting analysis using model depth
* Feature importance interpretation
* Cross-validation for robust evaluation
* Tree visualization for model interpretability

---

## 🧰 Tech Stack

* Python
* Scikit-learn
* Pandas, NumPy
* Seaborn, Matplotlib

---

## 🔗 Notebook Access

Check out the notebook here:
👉 [Open in Colab](https://colab.research.google.com/drive/1j4XLfAGMHpv3il24fhAVcYJ-gGKgo-Yh)

