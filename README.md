# 🌍 Where Should I Live?
### Programming for Data Science – Final Project

This repository contains the final group project developed for the **Programming for Data Science (2025/26)** course. 

The goal of this project is to analyze and compare European countries using data science techniques, helping users make informed decisions about where to live based on key quality-of-life indicators.

## 👥 Authors
* Miguel Melo
* Carolina Arez
* Henrique Madureira
* Noa Penas

---

## 📋 Project Overview
In an increasingly mobile world driven by remote work, international education, and economic opportunities, individuals are often faced with a critical question: **"Where should I live?"**

This project provides data-driven answers by analyzing:
* **Cost of Living:** Housing, groceries, and services.
* **Safety:** Crime rates and social stability.
* **Employment:** Market opportunities and economic health.
* **Quality of Life:** Health, environment, and happiness indicators.

---

## 🏗 Project Structure
The project follows a structured data science workflow to ensure reproducibility and clarity.

> **Directory Layout**
> ```text
> Programming-for-Data-Science-Final-Project
> │
> ├── Project.ipynb       # Main project notebook
> ├── city_data.csv       # Dataset used in the analysis
> └── README.md           # Project documentation
> ```

### Notebook Workflow
1.  **Data Importation**: Loading datasets, organizing columns, and adjusting data types.
2.  **Data Wrangling & Analysis**: Cleaning, handling missing values, and exploratory data analysis (EDA).
3.  **Advanced Topic – Interactive Map**: Web scraping and geospatial visualization.
4.  **Data Science in Action**: A recommendation system that suggests countries based on user-defined preferences.

---

## 🛠 Technologies Used
We leveraged the Python ecosystem to transform raw data into actionable insights:

| Category | Tools |
| :--- | :--- |
| **Core** | Python, NumPy |
| **Data Manipulation** | Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Data Collection** | BeautifulSoup, Selenium |
| **Machine Learning** | Scikit-learn (KNNImputer) |

---

## ✨ Key Features
* **Robust Cleaning:** Transformation of "messy" real-world datasets into structured formats.
* **Exploratory Insights:** Statistical analysis of European socio-economic indicators.
* **Web Scraping:** Automated data enrichment from external web sources.
* **Interactive Visuals:** Dynamic maps and graphs for intuitive data exploration.
* **Recommendation Engine:** A logic-based system that matches countries to user lifestyle goals.

---

## 🚀 How to Run the Project

**1. Clone the repository**
```bash
git clone [https://github.com/MiguelMelo006/Programming-for-Data-Science-Final-Project.git](https://github.com/MiguelMelo006/Programming-for-Data-Science-Final-Project.git)
 ```


**2. Navigate to the folder**
```bash
cd Programming-for-Data-Science-Final-Project 
```

**3. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn beautifulsoup4 selenium
```

**4. Launch the notebook**
(Then run the project notebook step by step.)

## 🎯 Project Goals
* Transform raw, unstructured data into structured insights.

* Apply Exploratory Data Analysis (EDA) to identify European trends.

* Integrate advanced data collection (Web Scraping) with traditional datasets.

* Build decision-support tools to solve real-world relocation dilemmas.

## 📊 Extra feature- Interactive Web Dashboard (Streamlit)


As a major component of this project, we developed a simple, dynamic, interactive web application using **Streamlit** and **Plotly**. This dashboard moves beyond static analysis, allowing users to generate personalized city recommendations based on their unique lifestyle priorities.

### 🌟 Dashboard Features
* **Custom Preference Weights:** Users can assign a weight (0–10) to 11 different indicators, including Disposable Income, Crime Index, Health Care Quality, and Climate (Very hot days).
* **Hard Constraints (Filters):** Users can set strict minimum or maximum thresholds for specific metrics (e.g., setting a maximum cap on average rent prices).
* **Smart Recommendation Engine:** The app computes a customized "Match %" for each city by ranking and weighting the user's active criteria (automatically adjusting for metrics where "lower is better", like unemployment or crime).
* **Dynamic Visualizations:** * **Podium & Rankings:** A clear breakdown of your top 5 matched cities.
    * **Economic Profile:** Grouped bar charts comparing salaries, rent, cost of living, and disposable income.
    * **Safety & Mobility:** Visual comparisons of crime rates, unemployment, and traffic indexes.
    * **Radar Charts:** A normalized comparison mapping how the top cities perform against each other across all your chosen metrics.

### 🖥️ How to Run the Dashboard

Make sure you have installed the required dashboard dependencies:
```bash
pip install streamlit plotly
```
