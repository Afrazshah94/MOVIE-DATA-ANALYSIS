# 🎬 Movie Box Office Analysis 🎬

Welcome to the **Movie Box Office Analysis** project! This project analyzes the box office performance of 508 movies released between 2012 and 2016. The goal is to uncover trends, identify underperforming movies, and present actionable insights using **Google Sheets** and **Python**.

---

## 📊 **Project Overview**
This project focuses on analyzing a dataset containing movie titles, release dates, genres, directors, cast, budgets, and box office revenues. The analysis was performed using **Google Sheets** for quick insights and **Python** for advanced data processing and visualization.

### **Key Questions Explored:**
1. How did total and average box office revenue change over the years?
2. How many movies were released each year?
3. What percentage of movies underperformed (revenue < $10M)?
4. What are the trends in box office performance over time?

---

## 🛠️ **Tools and Technologies Used**
- **Google Sheets:** For data exploration, pivot tables, and basic visualizations.
- **Python Libraries:**
  - **Pandas:** For data cleaning and analysis.
  - **Matplotlib & Seaborn:** For creating professional visualizations.
  - **Jupyter Notebook:** For interactive coding and documentation.

---

## 📂 **Repository Structure**
Here’s an overview of the files and folders in this repository:
Movie-Box-Office-Analysis/
├── data/
│   └── Movie-Data.csv
├── notebooks/
│   └── Movie-Data-Results.ipynb
├── visualizations/
│   ├── Total_Revenue_by_Year.png
│   ├── Average_Revenue_by_Year.png
│   ├── Movie_Count_by_Year.png
│   ├── Low_Revenue_Count_by_Year.png
│   ├── Percent_Low_Revenue_by_Year.png
│   └── Revenue_Trends_by_Year.png
├── README.md
└── requirements.txt

---

## 📈 **Key Insights**
Here are some of the key insights uncovered during the analysis:

### **1. Total Revenue by Year**
- **2014 was the most profitable year**, with total revenue of **$20.01 billion**.
- **2016 had the lowest total revenue** at **$11.92 billion**, despite having a high average revenue per movie.

### **2. Average Revenue per Movie**
- The average revenue per movie was highest in **2012 ($170.55 million)** and lowest in **2015 ($109.04 million)**.

### **3. Number of Movies Released**
- The number of movies released increased from **106 in 2012** to **124 in 2015**, but dropped to **74 in 2016**.

### **4. Underperforming Movies**
- **2015 had the highest percentage of underperforming movies (16.13%)**, indicating a higher risk of low revenue that year.
- Movies with revenue below **$10 million** accounted for **11.22%** of all movies in the dataset.

---

## 🚀 **How to Use This Repository**
### **1. Google Sheets Analysis**
- Open the (https://docs.google.com/spreadsheets/d/1Zc9kbgqMUnHEAzbeet29ePGrOaldCEuKckdhx34am44/edit?usp=sharing) to explore the dataset, pivot tables, and interactive charts.
- Key metrics calculated: Total revenue, average revenue, movie count, and percentage of underperforming movies.

### **2. Python Analysis**
1. Clone this repository:
   ```bash
   git clone https://github.com/Afrazshah94/Movie-Box-Office-Analysis.git
