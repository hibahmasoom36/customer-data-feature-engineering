# Customer Data Feature Engineering Project

## 📌 Overview
This project demonstrates end-to-end **data due diligence, cleaning, and feature engineering** on a customer dataset.  
The goal was to transform messy demographic and financial data into meaningful features that can be used for **predictive modeling, segmentation, and marketing analytics**.

## 🎯 Objectives
- Perform **data cleaning** and handle missing values appropriately.  
- Apply **normalization and scaling** to financial variables.  
- Engineer **new features** to capture customer behavior and financial health.  
- Conduct **exploratory visual analysis** to assess feature utility.  

## 🗂️ Deliverables
- `Customer_Dataset_Data.csv` → original dataset provided for analysis.  
- `customer_data_with_additional_features.csv` → final dataset with cleaned values and engineered features.  
- `data-due-diligence-report.pdf` → detailed analysis, cleaning decisions, and feature documentation.  

## 🛠️ Key Insights
- Missing data was imputed using mode (categorical) and median (continuous) values.  
- Financial variables such as **household income** and **car value** were normalized for consistency.  
- Engineered features included:  
  - `TotalDebt` → consolidated financial obligations.  
  - `DebtToAgeRatio` → measure of financial stress vs. life stage.  
  - `CardTenurePerAge` → proxy for financial maturity.  
  - `PetOwnership` & `PetDensity` → lifestyle indicators.  
  - `AnnualCardSpend` → estimated spending habits.  
  - `RetirementSavingsPotential` → long-term financial preparedness.  

## 📊 Visual Examples
Some exploratory plots from the analysis:
- Distribution of **Debt-to-Age Ratio**  
- Relationship between **Household Income vs. Debt-to-Age Ratio**  
- Relationship between **PetDensity vs. Household Size**  
- Distribution of **AnnualCardSpend**  

*(See full report for charts and additional analysis.)*

## 📂 Repo Structure
/README.md

/customer_data.csv

/data-due-diligence-report.pdf

## 🔮 Next Steps
- Extend feature set with **interaction variables** (e.g., income × household size).  
- Use engineered dataset for **predictive modeling** (churn, spend prediction).  
- Apply clustering methods (e.g., K-Means, DBSCAN) for **customer segmentation**.  
