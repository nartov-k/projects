# Data Science Portfolio

## Introduction
Hi, this is Kirill. Welcome to my Data Science Portfolio! This repository contains a series of projects showcasing my skills in **data analysis, machine learning, and data visualization**.

## Projects

### Project 1: Cross-Market Insurance Policy Purchase Prediction (Cross-Market_Pred)
- **Objective**: 1. To find patterns of customer cross-market purchases based on EDA and Visualizations for an insurance company; 2. Prepare the dataset for model building; 3. To find an ML algorithm that provides better binary predictive results out of five: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost.
- **Data Source**: The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction?resource=download). It contains 12 attributes and 381K observations.
- **Tools Used**: 1. Python (Numpy, Pandas, Matplotlib, Seaborn, Skikit); 2. Tableau.
- **Outcomes**:  1. The list of insights resulting from the EDA phase was found (*EDA_Visualizations folder*). 2. The dataset was enriched with 3 new features, one feature was aggregated for the sake of data reduction, and the dataset was resampled to avoid negative bias during the model-building phase; 3. The random Forest model was the best-performing one out of 5 tested algorithms based on the ROC_AUC, accuracy, and precision measures. (*Models_Permormance_Measures folder*).

### Project 2: E-Commerce Platform Customer Behavior Analysis (E-Commerce_Cust_Analysis)
- **Objective**: To capture the insightful details of user behavior over one month of October on an E-Commerce Marketplace through EDA and model building;
- **Data Source**: The dataset was obtained from [Kaggle](https://www.kaggle.com/ecommerce). It contains 9 attributes and 300K randomly picked observations.
- **Tools Used**: Python (Numpy, Pandas, Matplotlib, Seaborn, Skikit, Mlxtend).
- **Outcomes**: *EDA phase*: 1. Conducted Conversion Analysis and formulated a weak point dealers of sight-attractive items should focus on; 2. Analyzed Prices and explained why there is no explicit correlation between price and purchases; 3. Time Series Analysis was conducted to unravel sales patterns over a specific time period; *Model building phase*: 4. Conducted Customer Segmentation (k-means clustering) and formulated recommendations to the e-store on how to use this model; 5. Market Basket Analysis (FP-Growth, Apriori) was applied to uncover the support(frequency) of top products and to find out the association rules.

### Project 3: Real Estate Database (Real_Estate_db)
- **Objective**: 1. To design a conceptual model (ER diagram) of a potential Database that can be made up of several smaller datasets taken from the real estate company Zillow; 2. To translate a conceptual model into an SQL schema by using DDL Statements; 3. To create a PostgreSQL Database and populate it by using DML Statements; 4. To write SQL queries to analyze the tendencies of the real estate market; 5. To analyze the performance of SQL queries;
- **Data Source**: The dataset consists of 5 files that were downloaded from the [Zillow website](https://www.zillow.com/research/data/).
- **Tools Used**: 1. PostgreSQL 13; 2. Python (Numpy, Pandas).
- **Outcomes**: 1. The data was transformed and prepared to populate the database (*data_transformation folder*); 2. The database was created and populated; 3. The tendencies of the real estate market were analyzed by running the corresponding SQL queries against the database; 4. The complexity and performance of queries were analyzed.

### Project 4: Insurance Policy Purchase Prediction (Policy_Purchase_Pred)
- **Objective**: 1. To find out what characteristics define a potential customer mostly; 2. To highlight the features of the policy that correlate with a customer's decision to purchase a policy; 3. To build a binary predicting model to forecast the policy purchasing based on the given features;
- **Data Source**: The dataset was taken from the [Allstate competition on Kaggle](https://www.kaggle.com/c/allstate-purchase-prediction-challenge/data). It contains 25 features and 665K observations.
- **Tools Used**: 1. SAS Enterprise Miner; 2. Tableau; 3. Tableau Prep Builder.
- **Outcomes**: 1. Insights that can help in defining a target audience were visualized as the result of the EDA stage; 2. The dataset was prepared for model building; 3. The number of models (Logistic Regression and Decision Tree) with different feature selection approaches was examined to pick the most optimal model in terms of its complexity and accuracy.

### Project 5: Kohl's Storage Optimization (Storage_Optimization)
- **Objective**: 1. To analyze business requirements and constraints; 2. To conduct the exploratory data analysis to formulate recommendations on the items allocation optimization in the storage.
- **Data Source**: The dataset was provided by [Kohl's Corporation](https://corporate.kohls.com/company/about-kohl-s). It consisted of 6 Excel sheets. The dataset contained 20 columns and 1400 records per sheet.
- **Tools Used**: 1. Tableau; 2. Tableau Prep Builder.
- **Outcomes**: The recommendations that can lead to $16K/year savings were formulated.

### Project 6: Steel Dynamics Financial Analysis (Fin_Analysis)
- **Objective**: To conduct a financial analysis of Steel Dynamics to statistically examine their financial and business performance compared to their competitors based on the next financial metrics: Contribution Margin Ratio, Operating Leverage Effect, Debt to Equity Ratio, and Financial Leverage.
- **Data Source**: All financial metrics are available on this [website](https://www.macrotrends.net/).
- **Tools Used**: Excel. 
- **Outcomes**: 1. Identified weaknesses in Steel Dynamics' financial performance by running statistical comparison analysis (Hypothesis one-way ANOVA testing) of 4 competitors' financial metrics; 2. Formulated the recommendations for Steel Dynamics based on the findings;

### Project 7: Maven Roasters Cofee Shop BI Analysis (BI_Analysis)
- **Objective**: To help a small batch coffee roasting company called Maven Roasters (a fictional name) conduct a business analysis based on their data about customers, employees, stores, and products in order to operate the business more effectively through data-driven business decisions.
- **Data Source**: This dataset requires a subscription to get acquired, and can only be accessed through the data collection of [Maven Analytics](https://www.linkedin.com/company/maven-analytics/)
- **Tools Used**: Tableau.
- **Outcomes**: The Business Intelligence analysis was conducted: 1) the array of helpful data visualizations and dashboards was prepared; 2) The insightful details about their low-selling products were brought to light and store managers' KPIs were formulated.

## How to Use
- To run the notebooks, you will need Jupyter Notebook software. To install Jupyter, you can use Python's package manager, pip. First, ensure that you have Python installed on your computer. Then, open your command line or terminal and run the following command: `pip install notebook`. This command will install Jupyter Notebook. After installation, you can start Jupyter Notebook by running `jupyter notebook` in your terminal. This will open the Jupyter Notebook interface in your default web browser, where you can run the notebooks.

## Contact
Feel free to contact me at **nartovk@umich.edu** for any questions or collaboration opportunities.
