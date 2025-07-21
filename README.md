# 🌍 World Happiness Index Analysis
This repository contains a Python-based data analysis project focused on the World Happiness Index, exploring how various factors like GDP, inflation, and perceived corruption influence happiness levels across different countries.

# 📊 Project Overview
The goal of this project is to analyse and clean the World Happiness Index dataset and investigate the correlation between happiness scores and other contributing indicators. Using tools from the Python data science stack, the project examines:

GDP per capita

Perceived corruption

Inflation

Social support

Life expectancy

Freedom to make life choices

Generosity

And more

# 🛠 Features
✅ Data cleaning and preprocessing

✅ Correlation analysis using df.corr()

✅ Visualisation of key relationships

✅ Insights on the most influential happiness factors

✅ Summary statistics and exploratory data analysis (EDA)

# 📁 Project Structure
📦 world-happiness-index-analysis
📄 README.md
📊 WHI_Inflation.csv
📓 World_Happiness_Index.ipynb

WHI_Inflation.csv: Dataset containing happiness and contributing metrics by country

World_Happiness_Index.ipynb: Jupyter Notebook with code and visualizations

# 📈 Methods
Data Cleaning: Handled missing values, renamed columns for clarity, ensured numeric types where necessary.

Correlation Analysis: Used df.corr() to calculate Spearman correlation coefficients between happiness scores and other variables.

Visualisation: Created heatmaps to visualize relationships between variables.

# 🔍 Key Insights
Strongest drivers of happiness are perceived integrity, wealth, freedom, and health.

Inflation, especially for essentials like food, shows a small but consistent negative correlation with happiness.

The low correlation of energy inflation might reflect subsidies, delayed consumer effects, or government intervention.

<img width="790" height="590" alt="WHI Correlation" src="https://github.com/user-attachments/assets/87a253b1-5904-42c7-9d85-e99cb902233e" />

# 📜 Policy Implications
The insights from my analysis suggest several actionable directions for policymakers aiming to improve population well-being:

✅ Strengthen Institutional Integrity
What I found:
Perceived integrity has the strongest correlation with happiness.

Policy response:

Improve transparency and reduce corruption in public institutions.

Invest in civic education and open government initiatives.

Promote judicial independence and accountability mechanisms.

💰 Address Wealth Inequality and Economic Security
What I found:
wealth is a strong driver of happiness.

Policy response:

Support inclusive economic growth and upward mobility.

Expand social safety nets and minimum income guarantees.

Encourage asset-building programs, such as affordable housing and retirement savings.

🗽 Safeguard Personal Freedoms
What I found:
Freedom to make life choices is a key contributor to happiness.

Policy response:

Protect civil liberties and human rights.

Ensure access to education and diverse career opportunities.

Reduce regulatory burdens that limit personal or entrepreneurial choices.

🏥 Invest in Public Health
WhatI found: Health is foundational to life satisfaction.

Policy response:

Increase access to quality healthcare and mental health services.

Focus on preventative care and health literacy.

Mitigate health disparities across socioeconomic and demographic groups.

# 🔍 Further Analyses for Demographic-Level Wealth Insights
1. Wealth Distribution vs. Happiness
What to do: Use measures like the Gini coefficient, wealth quintiles/deciles, or income percentiles.

Goal: Identify whether wealth inequality within a country moderates the happiness effect.

Example analysis:

Compare happiness across income brackets within countries.

Test if happiness gains diminish at higher income levels (i.e., diminishing returns).

2. Regional Subnational Comparison
What to do: Analyse wealth and happiness at regional/state/provincial levels within countries.

Goal: Understand how local economic conditions correlate with subjective well-being.

# 📦 Data Sources You Might Need
National household surveys (e.g., LIS, World Bank, DHS)

OECD Income Distribution Database

# 📂 Data Source
The World Happiness Index data used in this project was obtained from [Kaggle](https://www.kaggle.com/).  
Dataset link: [World Happiness Report](https://www.kaggle.com/datasets/agrafintech/world-happiness-index-and-inflation-dataset)  
The dataset is created using publicly available data from World Happiness Report, Gallup World Poll, and the World Bank. It has been structured for research, machine learning, and policy analysis purposes.
