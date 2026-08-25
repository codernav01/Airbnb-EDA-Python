# Exploratory Data Analysis on Airbnb Listings in Python

# 📌 Project Overview

Real-world data is rarely clean.  
Before building dashboards, machine learning models, or generating business insights, the data must first be explored, cleaned, and properly understood.

In this project, I performed a complete **Exploratory Data Analysis (EDA)** and **Data Cleaning workflow** on an Airbnb listings dataset from New York using **Python**.

The notebook focuses on identifying and treating:

- Missing values
- Incorrect data types
- Duplicate records
- Inconsistent categorical values
- Outliers
- Invalid date relationships
- General data quality issues

The final goal was to transform raw Airbnb data into a clean, structured, and analysis-ready dataset.

---

# 🎯 Project Objectives

- Understand the Airbnb dataset structure
- Diagnose data quality issues
- Perform data cleaning using Python
- Handle missing and inconsistent values
- Visualize important insights
- Prepare the dataset for future analytics and machine learning

---

# 🛠️ Technologies & Libraries Used

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import missingno as msno
```

---

# 📂 Dataset Features

The dataset contains important Airbnb listing information such as:

- Listing ID
- Host Name
- Room Type
- Price
- Ratings
- Number of Reviews
- Availability
- Coordinates
- Neighbourhood Details
- Listing Dates
- Stay Statistics

---

# 🔍 Key Tasks Performed

## ✅ Data Cleaning

- Removed invalid symbols from columns
- Converted incorrect data types
- Split coordinate columns into latitude & longitude
- Cleaned inconsistent categorical values
- Treated duplicate records
- Fixed out-of-range values
- Handled missing values logically

---

## 📊 Exploratory Data Analysis

Performed analysis on:

- Missing values
- Room type distribution
- Price distribution
- Rating patterns
- Duplicate records
- Date consistency
- Outlier detection

---

# 📈 Data Visualization

Visualization techniques used in this project:

- Missingness Matrix
- Missingness Barplot
- Histograms
- Countplots
- Distribution Plots
- Boxplots

---

# 💡 What I Learned

Through this project, I improved my understanding of:

- Real-world messy datasets
- Data preprocessing workflows
- Exploratory Data Analysis techniques
- Data cleaning strategies
- Visualization storytelling
- Analytical thinking

---

# 🚀 Why This Project Matters

In real industry scenarios, a large portion of a data analyst’s work involves cleaning and understanding raw data before analysis.

This project demonstrates:

- Practical EDA skills
- Data cleaning techniques
- Problem-solving ability
- Structured notebook documentation
- Real-world data handling experience

---

# 📁 Project Structure

```bash
├── Exploratory Data Analysis In Python Airbnb.ipynb
├── airbnb.csv
└── README.md
```

---

# ▶️ How to Run

Install required libraries:

```python
pip install pandas numpy matplotlib seaborn plotly missingno
```

Open the notebook:

```bash
jupyter notebook
```

---

# 📬 Connect With Me

If you liked this project or have suggestions for improvement, feel free to connect with me on LinkedIn or GitHub.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
