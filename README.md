# SpaceX Falcon 9 Landing Prediction 🚀

**Predicted the success of Falcon 9 first-stage landings** using real mission data — with the goal of estimating potential launch costs and helping competitors evaluate bids against SpaceX.  

**Key highlights:**  
- 📥 **Data collection & wrangling** from SpaceX API, Wikipedia, and web scraping.  
- 🔍 **Exploratory data analysis** to uncover mission, payload, and launch site patterns.  
- 📊 **Visualization** of trends, correlations, and geographic launch locations.  
- 🤖 **Predictive modeling** using classification algorithms to forecast landing success.  
- 📄 Final **capstone report** summarizing findings and business implications.  

---

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Modules](#modules)
- [Data Sources](#data-sources)
- [Tools & Libraries](#tools--libraries)
- [Results](#results)
- [Installation](#installation)

---

## Overview
SpaceX’s Falcon 9 rockets cost about **$62M** per launch — far less than the ~$165M charged by many competitors. A major reason: SpaceX reuses its **first stage** after successful landings.  

In this project, we use real mission data to **predict whether the first stage will land successfully**.  
If a competitor could forecast this with reasonable accuracy, they could better estimate launch costs and bid competitively.

---

## Objectives
- Develop Python code to manipulate data in Pandas.  
- Convert JSON data into Pandas DataFrames.  
- Apply data science methodology to define and solve a real-world business problem.  
- Load, clean, and explore datasets to extract meaningful insights.  
- Create sharable Jupyter Notebooks hosted on GitHub.

---

## Modules
### **Module 1 — Data Collection & Wrangling**
- Pulled launch records from **SpaceX API** and Wikipedia.
- Cleaned, formatted, and merged datasets for analysis.

### **Module 2 — Exploratory Data Analysis**
- Investigated relationships between payload, orbit, launch site, and landing outcome.
- Used SQL queries for structured exploration.

### **Module 3 — Data Visualization**
- Created bar charts, scatter plots, and maps with Matplotlib, Seaborn, and Folium.
- Highlighted patterns in launch success by mission profile.

### **Module 4 — Predictive Analysis**
- Applied classification models: Logistic Regression, Decision Trees, Support Vector Machines, and K-Nearest Neighbors.
- Compared model accuracy and selected the best predictor.

### **Module 5 — Results**
- Summarized findings in a final PDF report.
- Discussed business implications and potential competitive advantages.

---

## Data Sources
- **SpaceX REST API** (launch data)  
- **Wikipedia** (mission metadata)  
- Web scraping & JSON data files

---

## Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium)
- SQL (SQLite)
- Jupyter Notebook
- Git & GitHub

---

## Results
- Developed an end-to-end data science workflow from raw data to predictive model.
- Identified key mission features correlated with landing success.
- Achieved predictive accuracy sufficient for competitive cost estimation.


---

## Installation
```bash
# Clone the repository
git clone https://github.com/dgazeyreyn/falcon_9_rocket_launch.git

# Navigate into the repo
cd falcon_9_rocket_launch

# Open any Jupyter Notebook
jupyter notebook
