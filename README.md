# 🚴 Cyclistic Bike-Share Analysis

## Google Data Analytics Capstone Project

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Google%20Colab](https://img.shields.io/badge/Google-Colab-yellow)

---

# 📌 Project Overview

This project is based on the **Google Data Analytics Professional Certificate Capstone Case Study**.

The objective is to analyze Cyclistic bike-share data and understand how **annual members** and **casual riders** use the service differently. Based on these insights, data-driven recommendations are provided to help Cyclistic increase annual memberships.

---

# 🎯 Business Problem

Cyclistic's marketing team believes that annual members are more profitable than casual riders.

The goal of this analysis is to identify behavioral differences between these two customer groups and recommend strategies to convert casual riders into annual members.

---

# ❓ Business Question

> **How do annual members and casual riders use Cyclistic bikes differently?**

---

# 📊 Dataset

### Source

Google Data Analytics Capstone – Divvy Bike Share Dataset

### Download Dataset

The original dataset is too large to be included in this repository.

You can download the official dataset from:

**https://divvy-tripdata.s3.amazonaws.com/index.html**

After downloading, place the CSV files inside the following directory:

```
data/raw/
```

> **Note:** This project uses the publicly available Divvy Bike Share dataset provided for the Google Data Analytics Capstone. Please refer to the data provider's terms of use before redistributing the data.

---

# 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- SciPy
- Google Drive

---

# 📋 Project Workflow

```
Business Understanding
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Statistical Analysis
        │
        ▼
Business Insights
        │
        ▼
Recommendations
```

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Converted datetime columns
- Removed duplicate records
- Removed invalid ride durations
- Created ride duration feature
- Checked missing values
- Verified data quality
- Saved cleaned dataset

---

# ⚙️ Feature Engineering

Additional variables were created to improve the analysis:

- Ride Duration (Minutes)
- Ride Duration (Hours)
- Year
- Month
- Quarter
- Week Number
- Day Name
- Hour
- Weekend Indicator
- Time of Day
- Season
- Rush Hour

---

# 📈 Exploratory Data Analysis

The analysis explored:

- Rider Type Distribution
- Bike Type Usage
- Average Ride Duration
- Monthly Trends
- Weekly Trends
- Hourly Ride Patterns
- Weekend vs Weekday Usage
- Ride Duration Distribution
- Top Start Stations
- Top End Stations

---

# 📊 Statistical Analysis

The following statistical techniques were applied:

- Independent Samples t-test
- Chi-Square Test of Independence
- Cohen's d (Effect Size)
- 95% Confidence Intervals

---

# 🔍 Key Findings

- Annual members generated more rides than casual riders.
- Casual riders had longer average ride durations.
- Members primarily rode during weekdays.
- Casual riders showed increased activity on weekends.
- Ride demand increased during warmer months.
- Bike preferences differed between customer groups.

---

# 💡 Business Recommendations

1. Offer weekend membership promotions targeting casual riders.
2. Launch seasonal marketing campaigns during high-demand months.
3. Advertise memberships at the busiest bike stations.
4. Introduce discounted trial memberships.
5. Reward frequent casual riders through loyalty programs.

---

# 📂 Repository Structure

```
cyclistic-bike-share-analysis/
│
├── Cyclistic_Bike_Share_Analysis.ipynb
│
├── Cyclistic_Conversion_Strategy.pdf
│
|── requirements.txt
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🚀 Future Improvements

- Interactive Power BI Dashboard
- Geographic Ride Analysis
- Customer Segmentation
- Time Series Forecasting
- Predictive Analytics

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Business Storytelling
- Business Recommendations

---
## 🎓 Certification

This project was completed as the capstone case study for the **Google Data Analytics Professional Certificate** (Coursera).

- 📜 [Verify Certificate](https://coursera.org/verify/professional-cert/UMYBL7872HSX)
- 🏅 [View Digital Badge (Credly)](https://www.credly.com/earner/earned/badge/16b1b9bd-0de7-4b9b-9b8e-68cd8a160f33)

---
# 👨‍💻 Author

**Sameer Sunil Thite**

MBA (Business Analytics)

Google Advanced Data Analytics Professional Certificate

Google Business Intelligence Professional Certificate

Google Data Analytics Professional Certificate

---

If you found this project useful, consider giving it a ⭐ on GitHub.
