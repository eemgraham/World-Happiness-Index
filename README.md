# World-Happiness-Index
🌍 World Happiness Index Analysis
This repository contains a Python-based data analysis project focused on the World Happiness Index, exploring how various factors like GDP, inflation, and perceived corruption influence happiness levels across different countries.

📊 Project Overview
The goal of this project is to analyse and clean the World Happiness Index dataset and investigate the correlation between happiness scores and other contributing indicators. Using tools from the Python data science stack, the project examines:

GDP per capita

Perceived corruption

Inflation

Social support

Life expectancy

Freedom to make life choices

Generosity

And more...

🛠 Features
✅ Data cleaning and preprocessing

✅ Correlation analysis using df.corr()

✅ Visualisation of key relationships

✅ Insights on the most influential happiness factors

✅ Summary statistics and exploratory data analysis (EDA)

📁 Project Structure
perl
Copy
Edit
📦 world-happiness-index-analysis
├── 📄 README.md
├── 📄 requirements.txt
├── 📊 world_happiness_data.csv
├── 📓 analysis.ipynb
└── 🐍 analysis.py
world_happiness_data.csv: Dataset containing happiness and contributing metrics by country

analysis.ipynb: Jupyter Notebook with code and visualizations

analysis.py: Python script for command-line usage (optional)

requirements.txt: Python dependencies

📈 Methods
Data Cleaning: Handled missing values, renamed columns for clarity, ensured numeric types where necessary.

Correlation Analysis: Used df.corr() to calculate Pearson correlation coefficients between happiness scores and other variables.

Visualisation: Created heatmaps and scatterplots to visualize relationships between variables.

🔍 Key Insights
Countries with higher GDP per Capita and Freedom to make life choices consistently score higher on the happiness index.

A negative correlation was observed between perceived corruption and happiness.

Social support and life expectancy are also good indicators of higher happiness levels.

📂 Data Source

The World Happiness Index data used in this project was obtained from [Kaggle](https://www.kaggle.com/).  
Dataset link: [World Happiness Report](https://www.kaggle.com/datasets/agrafintech/world-happiness-index-and-inflation-dataset)  
The dataset is created using publicly available data from World Happiness Report, Gallup World Poll, and the World Bank. It has been structured for research, machine learning, and policy analysis purposes.
