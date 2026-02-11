# Credit Card Customer Churn Analysis & Business Insights

## Project Overview

Customer attrition is a major challenge in the credit card industry, directly impacting revenue, customer lifetime value, and acquisition costs.

This project analyzes customer behavior data to identify key drivers of churn and generate actionable business insights to improve retention strategies.

The primary objective is to classify customers as:

* **Existing Customer**
* **Attrited Customer**

The analysis integrates:

* Exploratory Data Analysis (EDA)
* Univariate and Bivariate Analysis
* Statistical Hypothesis Testing (T-Test, Chi-Square Test, ANOVA)
* Behavioral Pattern Evaluation
* Business Insight Development

---

## Business Problem

High churn rates result in:

* Revenue loss
* Increased marketing and acquisition expenses
* Reduced long-term profitability

The goal of this analysis is to:

1. Identify characteristics of high-risk customers
2. Detect early warning signals of churn
3. Provide data-driven retention strategies

---

## Key Analytical Findings

### 1. Behavioral Indicators Are Strong Predictors

Statistical testing confirms that transaction activity is a significant differentiator between churned and active customers.

* Churned customers demonstrate lower transaction counts.
* Total transaction amounts decline prior to attrition.
* Engagement reduction is a measurable early warning signal.

This suggests that behavioral metrics are stronger churn predictors than static demographic variables.

---

### 2. Credit Utilization Patterns

Credit utilization ratio shows meaningful variation across churn groups.

* High utilization may indicate financial stress.
* Extremely low utilization may reflect disengagement.

Both patterns are associated with increased churn probability.

---

### 3. Customer Engagement & Contact Activity

Customers with reduced interaction frequency exhibit higher churn likelihood.

ANOVA testing indicates significant differences in engagement levels across customer segments, reinforcing the importance of proactive communication.

---

### 4. Demographic & Income Segmentation

Chi-Square testing reveals statistically significant differences in churn rates across:

* Income categories
* Certain age segments

While demographics contribute to churn risk, behavioral indicators remain the strongest predictors.

---

## Strategic Recommendations

### 1. Implement an Early Warning System

Develop monitoring dashboards to flag customers showing:

* Declining transaction frequency
* Decreasing total transaction amount
* Abnormal credit utilization patterns

Proactive outreach during this phase can reduce churn.

---

### 2. Personalized Retention Strategy

Segment customers based on risk level and behavioral profile:

* Offer targeted rewards for declining activity customers.
* Provide credit counseling or structured repayment options for high-utilization customers.
* Introduce loyalty benefits for high-value customers.

---

### 3. Improve Customer Engagement

Increase proactive communication through:

* Personalized financial insights
* Usage-based reward campaigns
* Retention-focused marketing interventions

Retention should be prioritized over aggressive acquisition to improve profitability.

---

## Technical Approach

### Data Processing

* Handling missing values
* Encoding categorical variables
* Feature preparation for statistical analysis

### Analysis Performed

* Univariate Analysis (distribution & outlier detection)
* Bivariate Analysis (numeric-numeric, numeric-categorical)
* Correlation Analysis
* Statistical Hypothesis Testing

### Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

## Project Structure

```
├── data/
│   └── credit_card_customers.csv
├── notebooks/
│   ├── 01_data_overview.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_univariate_bivariate_eda.ipynb
│   ├── 04_statistical_analysis.ipynb
├── reports/
│   └── figures/
└── README.md
```

---

## How to Run the Project

1. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scipy
```

2. Place the dataset inside the `/data` folder.

3. Execute notebooks in sequential order to reproduce analysis and results.

---

## Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Statistical Testing
* Customer Segmentation
* Business Insight Generation
* Analytical Storytelling
* Data Visualization

---

## Author

Shahana Sherin
Aspiring Data Analyst
