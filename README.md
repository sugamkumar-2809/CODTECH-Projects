# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques. The model is trained on the famous Titanic dataset and uses passenger information such as age, gender, ticket class, fare, and family details to make predictions.

The project demonstrates the complete Machine Learning workflow including:

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Model Training
- Model Evaluation

---

## 🎯 Objective

The objective of this project is to build a classification model capable of predicting passenger survival based on historical Titanic passenger data.

---

## 📊 Dataset Information

The dataset contains **891 passenger records** and **12 features** including:

| Feature | Description |
|----------|------------|
| PassengerId | Unique Passenger ID |
| Survived | Survival Status (0 = No, 1 = Yes) |
| Pclass | Passenger Class |
| Name | Passenger Name |
| Sex | Gender |
| Age | Passenger Age |
| SibSp | Number of Siblings/Spouses |
| Parch | Number of Parents/Children |
| Ticket | Ticket Number |
| Fare | Ticket Fare |
| Cabin | Cabin Number |
| Embarked | Port of Embarkation |

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 🔄 Project Workflow

### 1️⃣ Data Collection

The Titanic dataset is loaded into a Pandas DataFrame for analysis and preprocessing.

### 2️⃣ Data Cleaning

Missing values were handled as follows:

- Cabin column removed due to excessive missing values.
- Missing Age values replaced with mean age.
- Missing Embarked values replaced with mode.

### 3️⃣ Exploratory Data Analysis (EDA)

Statistical analysis and visualizations were performed to understand:

- Survival distribution
- Gender distribution
- Passenger class distribution
- Survival rate based on gender
- Survival rate based on passenger class

### 4️⃣ Data Visualization

The following visualizations were created:

- Survival Count Plot
- Gender Count Plot
- Gender vs Survival Plot
- Passenger Class Distribution
- Passenger Class vs Survival Plot

### 5️⃣ Feature Encoding

Categorical variables were converted into numerical values:

#### Sex

| Value | Encoding |
|---------|---------|
| Male | 0 |
| Female | 1 |

#### Embarked

| Value | Encoding |
|---------|---------|
| S | 0 |
| C | 1 |
| Q | 2 |

### 6️⃣ Feature Selection

The following features were used for training:

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

Target Variable:

- Survived

### 7️⃣ Train-Test Split

Dataset split:

- Training Data: 80%
- Testing Data: 20%

Random State:
random_state = 2


## 📁 Project Structure

```text
Titanic_Survival_Prediction/
│
├── Project1_Titanic_Survival_Prediction.ipynb
├── Titanic-Dataset.csv
├── README.md
└── outputs/
    ├── survival_plot.png
    ├── gender_plot.png
    └── pclass_plot.png
```
    
## 📊 Key Insights

✔ Female passengers had significantly higher survival rates.

✔ First-class passengers were more likely to survive.

✔ Passenger class strongly influenced survival probability.

✔ Gender proved to be one of the most important predictive features.

✔ Logistic Regression achieved nearly 80% accuracy on this dataset.

## 🎓 Learning Outcomes

This project helped develop practical skills in:
```
Data Preprocessing
Handling Missing Values
Data Visualization
Feature Engineering
Classification Algorithms
Model Evaluation
Machine Learning Workflow
```
## ⭐ Acknowledgements

This project was developed as part of Machine Learning practice and demonstrates the application of Logistic Regression on the Titanic Survival Prediction dataset.

If you found this project useful, please ⭐ star the repository.
```python
