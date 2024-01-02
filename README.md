# Data Science Portfolio

## Introduction
Hi, this is Kirill. Welcome to my Data Science Portfolio! This repository contains a series of projects showcasing my skills in data analysis, machine learning, and data visualization.

## Projects

### Project 1: [Cross-Market Insurance Customer Prediction (Cross-Market_Pred)]
- **Objective**: 1. To find patterns of customer cross-market purchases based on EDA and Visualizations for an insurance company; 2. Prepare the dataset for model building; 3. To find an ML algorithm that provides better binary predictive results out of five: Logarithmic Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost.
- **Data Source**: The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction?resource=download). It contains 12 attributes and 381K observations.
- **Tools Used**: 1. Python (Numpy, Pandas, Matplotlib, Seaborn, Skikit); 2. Tableau.
- **Findings**:  1. The list of insights resulting from the EDA phase was found (*EDA_Visualizations folder*). 2. The dataset was enriched with 3 new features and resampled to avoid negative bias during the model-building phase; 3. The random Forest model was the best-performing one out of 5 tested algorithms based on the ROC_AUC, accuracy, and precision measures. (*Models_Permormance_Measures folder*).

### Project 2: [E-Commerce Platform Customer Behavior Analysis (E-Commerce_Cust_Analysis)]
- **Objective**: To capture the insightful details of user behavior over one month of October on an E-Commerce Marketplace through EDA and model building;
- **Data Source**: The dataset was obtained from [Kaggle](https://www.kaggle.com/ecommerce). It contains 9 attributes and 300K randomly picked observations.
- **Tools Used**: Python (Numpy, Pandas, Matplotlib, Seaborn, Skikit, Mlxtend);
- **Findings**: *EDA phase*: 1. Conducted Conversion Analysis and formulated a weak point dealers of sight-attractive items should focus on; 2. Analyzed Prices and explained why there is no explicit correlation between price and purchases; 3. Time Series Analysis was conducted to unravel sales patterns over specific time periods; *Model building phase*: 4. Conducted Customer Segmentation and formulated recommendations to the e-store on how to use this model; 5. Market Basket Analysis was applied to uncover support(frequency) of top products and to find out the association rules;

## How to Use
- To run the notebooks, you will need Jupyter Notebook software. To install Jupyter, you can use Python's package manager, pip. First, ensure that you have Python installed on your computer. Then, open your command line or terminal and run the following command: `pip install notebook`. This command will install Jupyter Notebook. After installation, you can start Jupyter Notebook by running `jupyter notebook` in your terminal. This will open the Jupyter Notebook interface in your default web browser, where you can run the notebooks.

## Contact
Feel free to contact me at **nartovk@umich.edu** for any questions or collaboration opportunities.
