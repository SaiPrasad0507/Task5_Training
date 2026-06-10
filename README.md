# 🏏 Exploratory Data Analysis (EDA) on IPL Matches Dataset Using NumPy and Pandas

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an IPL Matches Dataset using Python libraries NumPy and Pandas. The objective is to analyze team performances, match outcomes, scoring patterns, venue statistics, and player achievements in the Indian Premier League (IPL).

EDA helps in understanding the structure of the dataset, identifying trends, discovering patterns, and extracting meaningful insights from cricket match data.

---

## 🎯 Objectives

- Load and explore the IPL dataset.
- Understand the structure of match data.
- Check for missing and duplicate values.
- Generate statistical summaries.
- Analyze team performances and winning trends.
- Study scoring and wicket patterns.
- Visualize data using charts and graphs.
- Extract meaningful insights from IPL matches.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab

---

## 📂 Dataset Features

The dataset contains the following columns:

| Column Name | Description |
|------------|-------------|
| Match_ID | Unique match identifier |
| Match_Date | Date of match |
| Team1 | First team |
| Team2 | Second team |
| Venue | Match venue |
| Team1_Score | Runs scored by Team 1 |
| Team2_Score | Runs scored by Team 2 |
| Winner | Match winner |
| Team1_Wickets | Wickets lost by Team 1 |
| Team2_Wickets | Wickets lost by Team 2 |
| Player_of_Match_Runs | Runs scored by Player of the Match |

---

## 🚀 Project Workflow

### 1. Import Required Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

### 2. Load Dataset

```python
df = pd.read_csv("IPL_Matches_Analysis_Dataset.csv")
```

### 3. Data Exploration

- Display first and last records
- Check dataset shape
- View column names
- Analyze data types

### 4. Data Cleaning

- Check missing values
- Check duplicate records

### 5. Statistical Analysis

- Mean
- Median
- Standard Deviation
- Minimum Value
- Maximum Value

### 6. Correlation Analysis

- Analyze relationships between scores, wickets, and player performance.

### 7. Data Visualization

The following visualizations were created:

- Team-wise Wins Distribution
- Venue-wise Match Distribution
- Team 1 Score Distribution
- Team 2 Score Distribution
- Team 1 vs Team 2 Score Comparison
- Team 1 Wickets Distribution
- Team 2 Wickets Distribution
- Player of Match Runs Distribution
- Average Scores by Venue

### 8. Insights and Conclusions

- Identified the most successful IPL teams.
- Analyzed scoring trends across matches.
- Examined venue-wise performance patterns.
- Studied wicket distributions.
- Evaluated player performance statistics.

---

## 📊 Visualizations Included

1. Team-wise Wins Bar Chart
2. Venue-wise Match Distribution Bar Chart
3. Team 1 Score Histogram
4. Team 2 Score Histogram
5. Team1 vs Team2 Scatter Plot
6. Team 1 Wickets Histogram
7. Team 2 Wickets Histogram
8. Player of Match Runs Histogram
9. Average Scores by Venue Bar Chart

---

## 🔍 Key Findings

- The dataset contains structured IPL match information.
- Team-wise win analysis helps identify the most successful teams.
- Score distributions reveal batting performance trends.
- Venue analysis highlights grounds with higher scoring matches.
- Wicket distributions provide insights into bowling effectiveness.
- High-scoring matches showcase competitive performances.
- Player of Match statistics indicate outstanding individual contributions.

---

## ▶️ How to Run

### Step 1: Open Google Colab

Create a new notebook in Google Colab.

### Step 2: Upload Dataset

```python
from google.colab import files
uploaded = files.upload()
```

Upload:

```text
IPL_Matches_Analysis_Dataset.csv
```

### Step 3: Load Dataset

```python
import pandas as pd

df = pd.read_csv("IPL_Matches_Analysis_Dataset.csv")
```

### Step 4: Run All Notebook Cells

Execute all cells sequentially to generate:
- Statistical summaries
- Correlation analysis
- Visualizations
- Final conclusions

---

## 📈 Results

The project successfully analyzed IPL match data and generated insights related to:

- Team performances
- Match-winning trends
- Venue statistics
- Score distributions
- Wicket analysis
- Player achievements

---

## ✅ Conclusion

This project successfully performed Exploratory Data Analysis (EDA) on an IPL Matches Dataset using NumPy and Pandas. The analysis provided valuable insights into team performances, scoring patterns, venue statistics, and player achievements. Various visualizations helped identify winning trends, high-scoring matches, and batting-friendly venues. The project demonstrates how data analytics can be applied to sports datasets to uncover meaningful patterns and support data-driven decision-making.
