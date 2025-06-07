# PRODIGY_DS_03

# 📊 Customer Purchase Prediction Using Decision Tree

## 📝 Project Overview

This project aims to build a **Decision Tree Classifier** to predict whether a customer will purchase a product or service, using **demographic** and **behavioral** data. The dataset used is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing).

---

## 📁 Dataset

**Bank Marketing Dataset** contains data related to direct marketing campaigns of a Portuguese banking institution. The classification goal is to predict whether the client will subscribe to a term deposit.

- **Source**: UCI Machine Learning Repository
- **Instances**: ~41,000
- **Features**: 16 input variables (categorical and numerical), 1 output (binary: 'yes' or 'no')

---

## ⚙️ Features Used

| Feature   | Description                                   |
|-----------|-----------------------------------------------|
| age       | Age of the client                             |
| job       | Type of job                                   |
| marital   | Marital status                                |
| education | Level of education                            |
| default   | Has credit in default?                        |
| balance   | Average yearly balance in euros               |
| housing   | Has housing loan?                             |
| loan      | Has personal loan?                            |
| contact   | Contact communication type                    |
| day       | Last contact day of the month                 |
| month     | Last contact month of the year                |
| duration  | Last contact duration (in seconds)            |
| campaign  | Number of contacts during this campaign       |
| pdays     | Days since the client was last contacted      |
| previous  | Number of contacts performed before this campaign |
| poutcome  | Outcome of the previous marketing campaign    |
| **target**| **Subscribed to term deposit (yes/no)**       |

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- Jupyter Notebook

---

## 📈 Model

A **Decision Tree Classifier** is used due to its interpretability and effectiveness on tabular data.

### Steps:
1. **Data Preprocessing**:
   - Handling categorical features (label encoding / one-hot encoding)
   - Dealing with missing values
   - Feature scaling (if necessary)

2. **Model Training**:
   - Train/Test split (e.g., 80/20)
   - Fit Decision Tree Classifier

3. **Evaluation**:
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - Feature Importance Visualization

---

## 📊 Results

The model achieved promising performance on the test set, showing potential for real-world marketing use cases. Further tuning and testing with ensemble methods (e.g., Random Forests) are possible for improved accuracy.
