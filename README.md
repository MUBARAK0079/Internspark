
# 🍽️ Zomato Restaurant Data Analysis

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on the Zomato Restaurant Dataset using Python. The objective is to clean the data, explore restaurant trends, visualize customer preferences, and generate meaningful business insights from the dataset.

The project demonstrates the complete data analysis workflow, including data preprocessing, visualization, and interpretation of results.

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Handle missing values and duplicate records.
- Analyze restaurant ratings.
- Identify the most popular cuisines.
- Explore restaurant locations.
- Analyze pricing versus ratings.
- Generate visualizations for better understanding.
- Provide business recommendations based on the analysis.

---

## 📂 Dataset

**Dataset Name:** Zomato Restaurant Dataset

The dataset contains information about restaurants including:

- Restaurant Name
- Address
- Location
- Online Order Availability
- Table Booking
- Ratings
- Votes
- Restaurant Type
- Cuisines
- Approximate Cost for Two
- Popular Dishes

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Imported dataset
- Checked dataset information
- Identified missing values
- Removed duplicate records
- Filled missing values
- Converted ratings into numeric format
- Prepared data for visualization

---

## 📈 Exploratory Data Analysis

The project includes the following analyses:

### ⭐ Restaurant Rating Distribution

- Distribution of restaurant ratings using histogram.

### 🍛 Top 10 Cuisines

- Most frequently served cuisines.

### 💰 Price vs Rating

- Relationship between restaurant cost and ratings.

### 📍 Top Restaurant Locations

- Locations with the highest number of restaurants.

### 🔥 Correlation Heatmap

- Correlation among numerical features.

### ☁️ Cuisine Word Cloud

- Visualization of the most common cuisines.

---

## 📌 Key Findings

- Most restaurants have ratings between **3.5 and 4.2**.
- North Indian cuisine is the most popular cuisine.
- Expensive restaurants do not always receive higher ratings.
- Restaurant density is highest in commercial areas.
- Data cleaning significantly improved dataset quality.

---

## 💡 Business Recommendations

- Focus on maintaining food quality rather than increasing prices.
- Expand restaurants in high-demand locations.
- Promote popular cuisines such as North Indian and Chinese.
- Encourage customers to leave ratings and reviews.
- Improve customer engagement through online ordering and promotions.

---

## 📷 Sample Visualizations

The notebook generates the following charts:

- Rating Distribution
- Top 10 Cuisines
- Price vs Rating Scatter Plot
- Correlation Heatmap
- Top Restaurant Locations
- Cuisine Word Cloud

---

## 📁 Project Structure

```
Zomato-Data-Analysis/
│
├── zomato.csv
├── zomato_analysis.ipynb
├── report.pdf
├── README.md
└── images/
```

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/yourusername/Zomato-Data-Analysis.git
```

2. Install required libraries.

```bash
pip install pandas numpy matplotlib seaborn wordcloud
```

3. Open the notebook in Google Colab or Jupyter Notebook.

4. Run all cells sequentially.

---

## 📚 Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from wordcloud import WordCloud
```

---

## 📌 Results

The project successfully identifies:

- Popular cuisines
- Customer rating patterns
- Restaurant distribution across locations
- Pricing trends
- Business insights for restaurant owners


