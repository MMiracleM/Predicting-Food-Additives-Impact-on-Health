# Food Additives Analysis

This repository presents a comprehensive analysis of food additives using data science, natural language processing (NLP), and interactive data visualization. It includes two Jupyter notebooks and a Power BI dashboard to explore and communicate key patterns in additive usage and descriptions.

## Repository Contents

Food-Additives-Analysis/


├── Food_Addictives.ipynb - Data cleaning, exploration, and visualization of food additives dataset

├── Food_Addictives_NLP - NLP analysis on additive-related articles

├── Food Additives.pbix - Power BI dashboard for interactive data exploration

├── cleanedfooddata.xlsx - Collected food addictives and intake dataset

├── requirements.txt - Required Libraries for running the python code

├── README.md - Project overview and usage guide


## Project Overview

The goal of this project is to explore, analyze food additives and developed a predictive machine learning model to predict the impact of the food addictives on health, through both structured data and unstructured text. It provides insights into the types, categories, and public perception of additives by combining:

- **Data cleaning and visualization**
- **Predictive Modelling**
- **Text analysis with NLP**
- **Interactive visual reporting in Power BI**

---

## 1. Food_Addictives.ipynb

### Objective
Analyze the food additives dataset to identify usage trends, common classifications, and distribution across categories. And then predict the healthly feeling

### Key Tasks
- Load and inspect dataset
- Clean missing values and remove duplicates
- Explore additive features
- Visualize top additives, categories, and classifications using bar charts and pie charts
- Prediction of the healthy feeling using machine learning models

### Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`

---

## 2. Food_Addictives_NLPipynb.ipynb

### Objective
Apply NLP techniques to the textual descriptions of food additives to extract meaningful insights and sentiment patterns.

### Key Tasks
- Preprocess text: tokenization, stopword removal, lemmatization
- Analyze word frequency
- Generate word clouds
- Perform sentiment analysis using TextBlob

### Libraries Used
- `nltk`
- `wordcloud`
- `textblob`
- `pandas`
- `matplotlib`

---

## 3. Food_Additives_Dashboard.pbix

### Objective
Enable interactive exploration of the dataset using Power BI.

### Features
- Visual breakdown of additive classifications and categories
- Drill-down charts and filters for exploring specific additives
- Integrated summary metrics for better decision support

> 📌 *To view the dashboard, open the `.pbix` file in Power BI Desktop.*



