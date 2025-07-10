This repository contains Task 04 of the Data Science Internship at SkillCraft Technology.

## 📌 Objective
Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.

## 📁 Dataset
**Source:** [US Accidents (2016–2023) – Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
**License:** CC-BY-NC-SA-4.0

Due to resource constraints, a representative sample of 100,000 rows was used from the full dataset (1.2M+ rows).

## 🛠 Tools & Technologies
- Python
- Pandas
- Seaborn
- Matplotlib
- Folium

## ✅ What I Did
- Cleaned the dataset and dropped irrelevant columns
- Extracted time-based features (hour and weekday) from the accident timestamp
- Analyzed accident frequency across:
  - Hour of the day
  - Day of the week
  - Weather conditions
  - Visibility and severity
- Visualized:
  - Top 10 weather conditions
  - Accident patterns by time
  - Boxplot of severity vs visibility
  - Interactive accident hotspot heatmap using Folium

## 📊 Key Insights
- Accidents are more frequent during morning and evening rush hours (7–9 AM, 4–6 PM)
- Fridays showed the highest accident volume among all days
- Rain, fog, and low visibility conditions are correlated with higher severity
- Urban regions show concentrated accident hotspots (e.g., California, Texas, Florida)


