# Bank Marketing Campaign Analysis

## 📌 Project Overview
This project focuses on **exploratory data analysis (EDA) of a bank marketing campaign dataset** using Python and Jupyter Notebook.

The objective is to understand customer characteristics, campaign performance, and factors associated with whether a customer subscribes to a **term deposit**.

The analysis includes data inspection, statistical analysis, data visualization, correlation analysis, and exploration of customer subscription behavior.

---

## 🎯 Objectives
* Understand the structure and characteristics of the bank marketing dataset.
* Identify missing values, duplicate records, and data types.
* Perform descriptive statistical analysis.
* Analyze the distribution of the target variable.
* Explore relationships between customer attributes and term-deposit subscriptions.
* Identify important numerical and categorical patterns.
* Visualize customer and campaign behavior.
* Generate insights that can support future predictive modeling.

---

## 📊 Dataset
The project uses the **Bank Marketing dataset** containing customer and marketing campaign information.

### Dataset Details
* **Records:** 41,188
* **Features:** 21
* **Target Variable:** `y`
* **Target Values:**

  * `yes` – Customer subscribed to a term deposit
  * `no` – Customer did not subscribe to a term deposit

### Major Features
| Feature     | Description                                    |
| ----------- | ---------------------------------------------- |
| `age`       | Age of the customer                            |
| `job`       | Type of occupation                             |
| `marital`   | Marital status                                 |
| `education` | Education level                                |
| `default`   | Whether the customer has credit in default     |
| `housing`   | Whether the customer has a housing loan        |
| `loan`      | Whether the customer has a personal loan       |
| `contact`   | Communication type                             |
| `month`     | Month of the last contact                      |
| `duration`  | Duration of the last contact                   |
| `campaign`  | Number of contacts during the current campaign |
| `pdays`     | Number of days since previous campaign contact |
| `previous`  | Number of previous contacts                    |
| `poutcome`  | Outcome of the previous campaign               |
| `y`         | Term-deposit subscription result               |

---

## 🛠️ Technologies Used
* **Python**
* **Jupyter Notebook**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization

---

## 🔍 Analysis Performed

### 1. Data Loading
The dataset is imported using Pandas and initially inspected to understand its structure.

### 2. Data Inspection
The notebook examines:
* Number of rows and columns
* Column names
* Data types
* Dataset information
* Unique values

### 3. Data Quality Analysis
The project checks for:
* Missing values
* Duplicate records
* Incorrect or unexpected data types
* Percentage of missing values

### 4. Statistical Analysis
Descriptive statistics are generated for both numerical and categorical variables.

### 5. Target Variable Analysis
The distribution of the `y` variable is analyzed to understand the proportion of customers who subscribed to a term deposit.

### 6. Correlation Analysis
A correlation matrix is created for numerical features to identify relationships between variables.

### 7. Customer Analysis
Subscription behavior is explored across different customer characteristics, including:
* Job
* Education
* Marital status
* Age
* Housing loan
* Personal loan

### 8. Campaign Analysis
The project analyzes marketing campaign characteristics such as:
* Call duration
* Number of campaign contacts
* Previous campaign outcome
* Contact month

---

## 📈 Visualizations
The notebook includes several visualizations, including:
* Target variable distribution
* Target percentage distribution
* Correlation heatmap
* Numerical feature distributions
* Subscription rate by job
* Subscription rate by education
* Subscription rate by marital status
* Subscription rate by housing loan
* Age distribution by subscription status
* Campaign contact analysis
* Call-duration analysis
* Month-wise subscription rate
* Previous campaign outcome analysis

---

## 💡 Key Insights
The exploratory analysis helps identify patterns in customer subscription behavior.

Some important observations include:
* The target variable is **imbalanced**, with more customers not subscribing than subscribing.
* Customer demographics such as **job and education** show differences in subscription rates.
* **Call duration** provides useful information about campaign outcomes.
* Previous campaign outcomes can be associated with the likelihood of a customer subscribing.
* Campaign-related variables can provide valuable signals for predicting customer responses.

These insights can be used as a foundation for developing a machine learning model.

---

## 🚀 Future Scope
This project can be extended into a complete machine learning pipeline.

Possible future improvements include:
* Data preprocessing
* Categorical variable encoding
* Feature engineering
* Feature selection
* Handling class imbalance
* Train-test splitting
* Machine learning classification
* Model comparison
* Hyperparameter tuning
* Accuracy, precision, recall, and F1-score evaluation
* ROC-AUC analysis
* Customer subscription prediction

Possible models include:
* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost

---

## 📚 Learning Outcomes
Through this project, I gained practical experience in:
* Exploratory Data Analysis
* Data cleaning and inspection
* Pandas and NumPy
* Statistical analysis
* Data visualization
* Correlation analysis
* Categorical data analysis
* Identifying patterns in customer behavior
* Interpreting business insights
* Preparing data for machine learning

---

## 👨‍💻 Author

**Jainoor Singh Saini**
Computer Science Engineering Student
Chandigarh University

