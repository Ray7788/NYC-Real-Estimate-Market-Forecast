# Core code directory
**This directory includes data preprocessing: data cleaning feature engineering, and benchmark and individual model development: model training and evaluation, and model stacking**

## Step1
- Raw data is preprocessed by Wang Ruijue: 
  - outputs are EBITDA_preprocess.csv and revenue_preprocess.csv
  - preprocessing steps are in the root file directory: **Cleaned Data/data_construction.ipynb**
## Step2
- The preprocessed data is re-loaded and implement data cleaning, feature engineering by Xu Rui:
  - outputs is called **EBITDA_new.csv** (revenue column is also included in this file, all in one file)
  - feature engineering steps are in the Cleaned Data file directory: **Cleaned Data/data_clean.ipynb**
## Step3
- Lin Xiao implemented a benchmark for datasets EBITDA_new.csv
  
## Step4
- Xu Rui implemented individual models for datasets EBITDA_new.csv(EBITDA and revenue are all included), and then merged into unified files called **classicML_EBITDA.ipynb** and **classicML_revenue.ipynb**

## Step5
- Zou Zeren implemented stacking models for datasets EBITDA_new.csv(EBITDA and revenue are all included), and then merged into a unified file called **stacking_EBITDA.ipynb** and **stacking_revenue.ipynb**

Depreciated files(in "old" directory) will be removed in the future, please do not use them.