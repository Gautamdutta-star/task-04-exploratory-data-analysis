# Exploratory Data Analysis & Statistical Insights using Pandas

## Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) and statistical analysis using Python, Pandas, NumPy, SciPy, and Matplotlib.

The objective is to explore an e-commerce transaction dataset, understand statistical distributions, identify potential anomalies, analyze relationships between business variables, test business hypotheses, and summarize important business insights.

---

## Dataset

Dataset: Maven Fuzzy Factory E-Commerce Orders

The cleaned dataset contains:

- 32,313 transaction records
- 15 analytical columns

The analysis is performed using the cleaned dataset generated during the data cleaning and preprocessing workflow.

---

## Objectives

The project focuses on:

- Computing descriptive statistics
- Analyzing mean, median, standard deviation, and quartiles
- Understanding variable distributions using histograms
- Detecting potential anomalies using box plots
- Creating a correlation matrix
- Visualizing correlations using a heatmap
- Formulating and testing three business hypotheses
- Using Pearson correlation for statistical testing
- Interpreting p-values at the 0.05 significance level
- Summarizing the top five business findings

---

## Exploratory Data Analysis

### Descriptive Statistics

Summary statistics were calculated for the following variables:

- items_purchased
- price_usd
- cogs_usd
- revenue_usd
- total_cost_usd
- profit_usd
- profit_margin_pct

The analysis includes:

- Count
- Mean
- Median
- Standard deviation
- Minimum
- 25th percentile
- 50th percentile
- 75th percentile
- Maximum

---

## Data Visualizations

### Histograms

Histograms were generated to analyze the distributions of:

- Items Purchased
- Price USD
- Revenue USD
- Profit USD
- Profit Margin %

### Box Plots

Box plots were created to identify potential anomalies and understand the spread of:

- Items Purchased
- Price USD
- Revenue USD
- Profit USD
- Profit Margin %

### Correlation Heatmap

A correlation matrix and heatmap were generated for:

- items_purchased
- price_usd
- cogs_usd
- revenue_usd
- total_cost_usd
- profit_usd
- profit_margin_pct

---

## Business Hypothesis Testing

Three business hypotheses were formulated and tested using Pearson correlation.

### Hypothesis 1 — Price vs Revenue

There is a strong positive association between product price and revenue.

Correlation: 0.9783  
P-value: < 0.05

The result indicates a statistically significant association between price and revenue in the analyzed dataset.

### Hypothesis 2 — Price vs Profit

There is a strong positive association between product price and profit.

Correlation: 0.9731  
P-value: < 0.05

The result indicates a statistically significant association between price and profit in the analyzed dataset.

### Hypothesis 3 — COGS vs Profit

There is a strong positive association between COGS and profit.

Correlation: 0.9270  
P-value: < 0.05

The result indicates a statistically significant association between COGS and profit in the analyzed dataset.

---

## Top 5 Business Findings

### 1. Strong Price–Revenue Association

Product price and revenue show a very strong positive correlation (r = 0.9783, p < 0.05), indicating a strong statistical association between the two variables.

### 2. Strong Price–Profit Association

Product price and profit show a very strong positive correlation (r = 0.9731, p < 0.05), indicating a strong statistical association between price and profit.

### 3. Strong COGS–Profit Association

COGS and profit show a strong positive correlation (r = 0.9270, p < 0.05), indicating a strong statistical association between cost of goods sold and profit.

### 4. Purchase Quantity Distribution

The items_purchased variable contains only 1 and 2 units per transaction. One-unit purchases occur substantially more frequently than two-unit purchases.

### 5. Profit Margin Shows Limited Variation

The profit_margin_pct variable has relatively low variation compared with its mean, indicating that profit margins are fairly concentrated around the dataset's central value.

---

## Statistical Note

All three tested hypotheses produced p-values below the 0.05 significance level, indicating statistically significant associations in the analyzed sample.

These results describe correlation/association and do not establish causation.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Google Colab
- Jupyter Notebook
- GitHub

---

## Project Structure

task-04-exploratory-data-analysis/
├── Task_04_Exploratory_Data_Analysis.ipynb
└── README.md

---

## Key Outcomes

- Successfully analyzed 32,313 e-commerce transactions
- Computed comprehensive descriptive statistics
- Generated histogram distributions
- Used box plots for anomaly detection
- Created a correlation matrix and heatmap
- Tested three business hypotheses statistically
- Identified strong statistical associations among key business variables
- Documented the top five EDA findings
- Applied a 0.05 significance level for hypothesis testing

---

## Author

Gautam Kumar Dutta

B.Tech – Computer Science Engineering
