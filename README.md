# TWO CENTURIES OF UM RACES – Exploratory Data Analysis

**Author:** Havva Açık  
**Role:** Data Analytics Enthusiast  

## 📌 Project Overview
This project focuses on an exploratory data analysis (EDA) of ultra marathon race data from the **Two Centuries of UM Races** dataset.

The analysis specifically examines **50 km and 50 mile races held in the USA during the year 2020**, with the goal of understanding athlete performance patterns based on **race length, gender, and age**.

---

## 📂 Dataset
Dataset: https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running

It contains historical ultra marathon race results, including:
- Event details
- Athlete information
- Performance metrics

---

## 🧹 Data Cleaning & Preparation
The following data preparation steps were performed:

- Filtered races:
  - USA events only
  - 50 km and 50 mile distances
  - Year 2020
- Cleaned event names by removing country tags
- Created a new feature: `athlete_age`
- Cleaned performance time format
- Removed unnecessary columns
- Handled missing values
- Checked for duplicates
- Converted data types for analysis
- Renamed columns for better readability

---

## 📊 Exploratory Data Analysis
Several visualizations were created to explore performance trends:

- Distribution of race distances
- Gender-based comparison of race participation
- Speed distribution for 50-mile races
- Violin plots showing speed differences by race length and gender
- Relationship between athlete age and average speed using regression analysis

---

## 📈 Key Findings
- Male and female athletes show noticeable differences in average speed across both race distances.
- Athlete performance varies with age, with peak average speeds observed in specific age ranges.
- 50-mile races show different speed distributions compared to 50 km races, indicating the impact of race length on performance.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Seaborn
- Jupyter Notebook

---

## 📌 Notes
This project is intended as a **portfolio demonstration of data cleaning, exploration, and visualization skills**.

