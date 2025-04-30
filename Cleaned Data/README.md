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