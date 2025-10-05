# 🚢 Titanic Survival Prediction using Logistic Regression

### 🧠 Objective

This project aims to predict passenger survival on the Titanic using **Logistic Regression**, a powerful classification algorithm.

---

### 📚 Libraries Used

* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn (SkLearn)**

---

### 🗂️ About the Dataset

The dataset contains information about 891 passengers aboard the Titanic.
Below are the key columns:

| Column      | Description                       | Data Type |
| :---------- | :-------------------------------- | :-------- |
| survived    | Survival (0 = No, 1 = Yes)        | int64     |
| pclass      | Passenger class                   | int64     |
| sex         | Gender                            | object    |
| age         | Age in years                      | float64   |
| sibsp       | Number of siblings/spouses aboard | int64     |
| parch       | Number of parents/children aboard | int64     |
| fare        | Ticket fare                       | float64   |
| embarked    | Port of Embarkation               | object    |
| class       | Passenger class (categorical)     | category  |
| who         | Person type (man/woman/child)     | object    |
| adult_male  | Adult male flag                   | bool      |
| deck        | Deck information                  | category  |
| embark_town | Embarkation town                  | object    |
| alive       | Survival status                   | object    |
| alone       | Passenger traveling alone flag    | bool      |

---

### 🧩 Project Workflow

1. **Data Loading** – Imported dataset using Pandas.
2. **Exploratory Data Analysis (EDA)** – Checked for null and duplicate values.
3. **Data Cleaning** – Handled missing values appropriately.
4. **Data Processing** – Encoded categorical variables using **Label Encoding** and **One-Hot Encoding**.
5. **Data Splitting** – Split the dataset into **train (80%)** and **test (20%)** sets.
6. **Model Training** – Trained a **Logistic Regression** model using `X_train` and `y_train`.
7. **Model Testing** – Predicted survival outcomes using `X_test`.
8. **Model Evaluation** – Evaluated model performance using **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

---

### 📊 Results

| Metric        | Score |
| :------------ | :---- |
| **Accuracy**  | 0.81  |
| **Precision** | 0.83  |
| **Recall**    | 0.87  |
| **F1-Score**  | 0.85  |

---

### 🏁 Conclusion

An efficient **Logistic Regression model** was built to predict Titanic passenger survival with an impressive accuracy of **81%**.
This project demonstrates key steps in a **machine learning pipeline**, from data cleaning and preprocessing to model evaluation and performance measurement.

Would you like me to add a **GitHub-ready README layout** (with badges, table of contents, and folder structure)? It’ll make your repo look even more professional.
