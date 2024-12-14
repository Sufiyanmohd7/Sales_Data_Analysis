# Project Overview

This repository contains Jupyter notebooks and datasets for conducting a sales and budget analysis. The files focus on data cleaning, exploratory analysis, budget forecasting, and sales reporting. Below is a detailed description of the files and their roles in the project.

---

## Files:

### **Notebooks**

#### 1. `1. Data loading and Cleaning.ipynb`
- **Purpose:** Initial data processing and cleaning.
- **Key Steps:**
  - Loading raw datasets.
  - Handling missing or inconsistent data.
  - Preparing data for further analysis and visualization.

#### 2. `2. Exploratory Data Analysis EDA.ipynb`
- **Purpose:** Perform exploratory data analysis to understand trends and patterns.
- **Key Steps:**
  - Descriptive statistics and visualizations.
  - Identifying relationships between variables.
  - Highlighting insights for actionable recommendations.

#### 3. `3. Sales Report Analysis.ipynb`
- **Purpose:** Detailed analysis of sales performance.
- **Key Steps:**
  - Aggregating and summarizing sales data.
  - Evaluating sales trends across dimensions like time, geography, and products.
  - Generating sales reports.

#### 4. `4. Budget Forecasting.ipynb`
- **Purpose:** Develop forecasting models for budget planning.
- **Key Steps:**
  - Utilizing statistical and machine learning models.
  - Comparing forecast results with actual data.
  - Providing budget recommendations based on forecasts.

---

### **Datasets**

#### 1. `Budget_Data.csv`
- Contains budget-related information for forecasting.

#### 2. `FACT_InternetSales.csv` and `FACT_InternetSales_final.csv`
- Internet sales data for analysis.
- The final dataset includes cleaned and processed sales information.

#### 3. `fact_sales_20.csv`
- Year-specific sales data for focused analysis.

#### 4. `dim_prod.csv`
- Product dimension table for mapping product details.

#### 5. `fact_budget.csv`
- Contains forecasted budget figures.

#### 6. `monthly_sales.csv`
- Aggregated sales data by month.

#### 7. `dim_cust.csv`
- Customer dimension table for analyzing sales by customer demographics.

#### 8. `fact_sales.csv`
- Core sales dataset for trend and pattern analysis.

---

## How to Use

1. **Prerequisites:**
   - Install Python and Jupyter Notebook.
   - Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, etc.

2. **Execution Order:**
   - Start with `1. Data loading and Cleaning.ipynb` to prepare the datasets.
   - Proceed to `2. Exploratory Data Analysis EDA.ipynb` for initial insights.
   - Use `3. Sales Report Analysis.ipynb` for sales-focused analysis.
   - Move to `4. Budget Forecasting.ipynb` for budget predictions.

3. **Datasets:**
   - Ensure datasets are stored in the same directory as the notebooks for seamless execution.

---

## Contact
For queries or assistance, reach out to the repository owner or refer to the documentation embedded within the notebooks.
