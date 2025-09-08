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
- `data-due-diligence-report.pdf` → detailed report including cleaning steps, feature engineering, and visual analysis:contentReference[oaicite:2]{index=2}.  
- `DATA_DICTIONARY.md` → documentation of variables and engineered features.  

## 🛠️ Key Insights
- Missing data imputed using mode (categorical) and median (continuous) values.  
- Financial variables (e.g., HHIncome, CarValue) normalized for consistency.  
- Engineered features included:  
  - `TotalDebt` → consolidated financial obligations.  
  - `DebtToAgeRatio` → measure of financial stress vs. life stage.  
  - `CardTenurePerAge` → proxy for financial maturity.  
  - `PetOwnership` & `PetDensity` → lifestyle indicators.  
  - `AnnualCardSpend` → estimated spending habits.  
  - `RetirementSavingsPotential` → long-term financial preparedness.  

## 📊 Visual Highlights
- Distribution of **Debt-to-Age Ratio** (financial stress signals).  
- **Household Income vs. Debt-to-Age Ratio** (correlation with income levels).  
- **PetDensity vs. Household Size** (segmentation opportunity).  
- Distribution of **AnnualCardSpend** (high-value customers).  

*(See report for full set of visualizations.)*

## 📂 Repo Structure
/README.md

/customer_data.csv

/data-due-diligence-report.pdf

## 🔮 Next Steps
- Extend feature set with **interaction variables** (e.g., income × household size).  
- Use engineered dataset for **predictive modeling** (churn, spend prediction).  
- Apply clustering methods (e.g., K-Means, DBSCAN) for **customer segmentation**.  
