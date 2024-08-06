# Data Science Project

## 💡 Project Overview

This project focuses on analyzing multiple datasets related to e-commerce. The primary goal is to gain insights into customer behavior, sales patterns, and other key performance indicators to help drive business decisions.

## ☝️ Project Goals

1. Understand customer demographics and purchasing patterns.
2. Analyze sales performance and identify trends.
3. Examine the effectiveness of different payment methods.
4. Evaluate customer reviews and satisfaction levels.

## 💼 Tasks

1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Data Visualization
4. Statistical Analysis
5. Reporting Insights and Recommendations

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🗂️ Data Sources

1. **customers.csv** - Customer information.
2. **geolocation.csv** - Geolocation data.
3. **order_items.csv** - Order items details.
4. **order_payments.csv** - Payment information for orders.
5. **order_reviews.csv** - Customer reviews on orders.
6. **orders.csv** - Order information.
7. **products.csv** - Product details.
8. **sellers.csv** - Seller information.
9. **product_category_name_translation.csv** - Product category name translations.

## 💻 Process and Steps

### 1️⃣ Step 1: Data Cleaning and Preprocessing
The first step involves cleaning and preprocessing the data to ensure it is ready for analysis. This includes handling missing values, correcting data types, and merging datasets where necessary.

**Tasks:**
1. Load datasets using Pandas.
2. Inspect data for missing values and inconsistencies.
3. Handle missing values appropriately (e.g., fill, drop).
4. Convert data types as needed for analysis.
5. Merge datasets to create a unified view for analysis.

### 2️⃣ Step 2: Exploratory Data Analysis (EDA)
This step involves exploring the data to understand its structure, relationships, and patterns. This is essential to form hypotheses and guide further analysis.

**Tasks:**
1. Descriptive Statistics: Summarize the data using descriptive statistics to understand the central tendency, dispersion, and shape of the data's distribution.
2. Data Visualization: Create visualizations such as histograms, box plots, and scatter plots to visually inspect the data and identify patterns, trends, and outliers.
3. Correlation Analysis: Examine correlations between different variables to identify potential relationships and dependencies.
4. Feature Engineering: Create new features or modify existing ones to improve the performance of predictive models.

### 3️⃣ Step 3: Building Predictive Models (Demand Forecasting)
For this task, we need to build two types of models: a machine learning model and a classical time series forecasting model.

**Tasks:**
1. Data Preparation: Prepare the data specifically for modeling, which includes creating lag features, aggregating data as needed, and splitting the data into training and test sets.
2. Machine Learning Model: Build a machine learning model (e.g., Random Forest, XGBoost) for short-term demand forecasting. Train the model using historical transaction data.
3. Time Series Model: Build a classical time series forecasting model (e.g., ARIMA, SARIMA). Use historical transaction data to fit the model.
4. Model Evaluation: Evaluate the models using appropriate metrics (e.g., MAE, RMSE) to compare their performance.
5. Scoring Script: Develop a script that can be used to generate forecasts for the next 14 days, starting from 7 days after the last date in the dataset.

### 4️⃣ Step 4: Sentiment Analysis of Product Reviews
This step involves analyzing the textual comments to determine the sentiment (positive, negative, neutral) and extracting any mentioned prices.

**Tasks:**
1. Sentiment Classification: Develop a sentiment analysis model to classify comments based on their emotional tone. Use NLP techniques and libraries like NLTK or SpaCy.
2. Price Extraction: Create an algorithm to extract numerical price values mentioned in the comments. This may involve regular expressions and NLP parsing.
3. Model Evaluation: Evaluate the sentiment classification model using metrics like accuracy, precision, and recall.
4. Integration and Visualization: Integrate the sentiment analysis results and extracted prices into a visual report (e.g., using Matplotlib or a BI tool).

## 🌿 Results and Conclusion
