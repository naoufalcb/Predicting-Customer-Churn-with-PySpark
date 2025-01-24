# Predicting Customer Churn with PySpark

This project aims to predict customer churn using PySpark, leveraging its distributed computing capabilities for efficient data analysis and machine learning. The notebook demonstrates end-to-end processes, from data exploration to building a predictive model.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Technologies Used](#technologies-used)
5. [Usage](#usage)

## Project Overview
Customer churn is a critical issue for businesses, as retaining existing customers is often more cost-effective than acquiring new ones. This project explores customer data to identify patterns and build a predictive model that helps in targeting at-risk customers.

The project covers a range of essential tasks, including:
- Data loading
- Exploratory data analysis
- Data preprocessing
- Feature preparation
- Model training, evaluation, and deployment

The machine learning model is used to identify factors contributing to customer churn, providing actionable insights to reduce churn and increase customer retention. The project provides hands-on experience with the steps required to create a machine learning model in PySpark, equipping you with the tools to deliver an AI-driven solution for customer churn.

### Prerequisites
- Basic knowledge of Machine Learning and Decision Trees
- Familiarity with Python programming concepts such as loops, if statements, and lists

## Dataset
The dataset used in this project includes the following features:
- **Numerical features:** e.g., tenure, monthly charges, total charges.
- **Categorical features:** e.g., gender, contract type, payment method.

The dataset contains customer demographic, account, and service usage details. It also includes a target variable indicating whether a customer churned.

### Key Insights from Dataset
- Distribution analysis of numerical and categorical variables.
- Correlation between features to identify relationships.
- Handling missing values and outliers for improved model performance.

## Methodology
The project follows these main steps:

1. **Set Up the Project Environment:**
   - Configure the environment and dependencies for PySpark.

2. **Exploratory Data Analysis (EDA):**
   - Analyze numerical columns using histograms and descriptive statistics.
   - Analyze categorical columns for unique values and distribution.

3. **Data Preprocessing and Cleaning:**
   - Handle missing values with PySpark's `Imputer`.
   - Remove outliers to ensure robust predictions.
   - Encode categorical variables for machine learning compatibility.

4. **Feature Preparation:**
   - Prepare numerical features for the model.
   - Prepare categorical features through encoding.

5. **Model Training and Evaluation:**
   - Train a Decision Tree model using PySpark MLlib.
   - Evaluate the model using metrics such as accuracy and F1-score.

6. **Model Deployment:**
   - Deploy the trained model for use in real-world scenarios.

7. **Challenge Activity:**
   - Apply the concepts learned to predict employee attrition in a similar dataset.

## Technologies Used
- **PySpark** for distributed data processing and machine learning.
- **Python** for scripting and data manipulation.
- **Pandas and Matplotlib** for additional data exploration and visualization.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/naoufalcb/Predicting-Customer-Churn-with-PySpark.git
   ```

2. Install dependencies:
   ```bash
   pip install pyspark
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Predicting-Customer-Churn-with-PySpark.ipynb
   ```

Feel free to modify the notebook to suit your specific dataset or modeling requirements.
