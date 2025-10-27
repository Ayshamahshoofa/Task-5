# Task-5
Exploratory Data Analysis (EDA)

---

## 📊 Exploratory Data Analysis (EDA) — Titanic Dataset

### 🧠 Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** using Python.
The objective is to extract insights, discover patterns, and visualize relationships between passenger attributes and survival chances.

---

### 🎯 Objective

* To apply statistical and visual exploration on the Titanic dataset.
* To identify key factors influencing passenger survival.
* To practice Python-based data analysis and visualization techniques.

---

### 🧰 Tools & Libraries Used

* **Python**
* **Pandas** — data handling and analysis
* **NumPy** — numerical computations
* **Matplotlib** & **Seaborn** — visualizations
* **Jupyter Notebook** — interactive development environment

---

### 📂 Dataset Information

**Dataset:** `train.csv` (Titanic Dataset from Kaggle)
👉 [Kaggle Titanic Data](https://www.kaggle.com/c/titanic/data?select=train.csv)

**Key Columns:**

| Column        | Description                                                          |
| ------------- | -------------------------------------------------------------------- |
| `PassengerId` | Unique ID of each passenger                                          |
| `Survived`    | Survival (0 = No, 1 = Yes)                                           |
| `Pclass`      | Passenger class (1 = Upper, 3 = Lower)                               |
| `Name`        | Passenger name                                                       |
| `Sex`         | Gender                                                               |
| `Age`         | Age in years                                                         |
| `SibSp`       | Number of siblings/spouses aboard                                    |
| `Parch`       | Number of parents/children aboard                                    |
| `Ticket`      | Ticket number                                                        |
| `Fare`        | Passenger fare                                                       |
| `Cabin`       | Cabin number                                                         |
| `Embarked`    | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

### 🪜 **Steps Performed (Simple Explanation)**

1. **Loaded the Dataset**

   * Imported the Titanic dataset using Pandas.
   * Checked the first few rows, data types, and missing values.

2. **Cleaned the Data**

   * Filled missing values in `Age` and `Embarked`.
   * Dropped the `Cabin` column (too many missing values).
   * Created new columns like `FamilySize` and extracted `Title` from names.

3. **Explored the Data (EDA)**

   * Used `.info()`, `.describe()`, and `.value_counts()` to understand data.
   * Plotted graphs to see how each column looks (Age, Fare, Sex, Pclass).

4. **Visualized Relationships**

   * Compared survival with other features using countplots and boxplots.
   * Checked how gender, class, and fare affected survival.

5. **Found Correlations**

   * Created a heatmap to see which features are most related to survival.
   * Used a pairplot to visualize how features interact.

---

#### **Summary of Findings**

| Factor       | Insight                                                  |
| ------------ | -------------------------------------------------------- |
| **Gender**   | Females had a higher survival rate than males.           |
| **Class**    | 1st class passengers had higher survival than 3rd class. |
| **Fare**     | Higher fare = greater chance of survival.                |
| **Age**      | Younger passengers were more likely to survive.          |
| **Embarked** | Passengers from port 'C' had better survival rates.      |

---

### 📈 Visualizations Included

* **Countplots** — Survival by gender, class, embarked port
* **Histograms** — Age and Fare distribution
* **Boxplots** — Age vs. Survival, Fare vs. Survival
* **Heatmap** — Correlation between numerical features
* **Pairplot** — Relationships between Age, Fare, Class, and Survival

---

### 📁 Files in Repository

| File                                    | Description                |
| --------------------------------------- | -------------------------- |
| `Exploratory Data Analysis (EDA).ipynb` | Main Jupyter Notebook      |
| `train.csv`                             | Titanic dataset            |
| `report.pdf`                            | observation and summary    |
| `README.md`                             | Project documentation      |

---
