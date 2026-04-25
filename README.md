# 🌍 United Nation Global Terrorism Analysis — Exploratory Data Analysis (EDA)
![EDA](https://github.com/satyamlokhande25-maker/United-Nation-Global-Terrorism-Analysis-using-EDA/blob/24b0bbf278b5528121c5d02e132a77a9f98c4705/1_NS1paZK2eZQyOaU8q0oC3Q%20(1).png
)

## 📌 Project Overview

The United Nations Global Terrorism Analysis (UNGTA) project focuses on performing an in-depth Exploratory Data Analysis (EDA) on global terrorist incidents recorded between 1970 and 2017. Terrorism is a critical global issue that impacts national security, economic stability, and public safety. This project analyzes historical terrorism data to uncover patterns, trends, and meaningful insights that help understand the evolving nature of terrorist activities worldwide.

The dataset contains more than 180,000 records of terrorist attacks with multiple attributes such as year, country, region, attack type, terrorist group, and casualty information. Data preprocessing was performed to handle missing values, select relevant columns, and standardize inconsistent entries. Missing casualty values were replaced with zeros, and unknown group names were standardized for consistency.

---

# 🎯 Problem Statement

The objective of this project is to analyze global terrorism data to identify patterns, trends, and key insights. The project focuses on understanding which regions and countries are most affected, how terrorist activities have evolved over time, and analyzing casualties and attack patterns.

---

# 💼 Business Objective

The United Nations Global Terrorism dataset provides a detailed record of terrorist incidents worldwide. This analysis helps governments, policymakers, and security agencies understand terrorism patterns, identify high-risk regions, and make informed decisions to improve security and counter-terrorism strategies.

---

# 📂 Dataset Information

The Global Terrorism Dataset includes the following key variables:

* iyear – Year of incident
* country_txt – Country where attack occurred
* region_txt – Region of the world
* attacktype1_txt – Type of attack
* gname – Terrorist group name
* nkill – Number of people killed
* nwound – Number of people wounded
* total_casualties – Total impact (killed + wounded)

---

# 🧹 Data Preprocessing

The dataset was cleaned and prepared using the following steps:

* Selected relevant columns for analysis
* Handled missing values in nkill and nwound
* Standardized unknown terrorist group names
* Created new feature total_casualties
* Aggregated data by year, country, and region

---

# 🔍 Exploratory Data Analysis

EDA was performed to understand terrorism patterns and global trends.

### Analysis Performed

* Terrorist attacks per year
* Country wise attack analysis
* Region wise distribution
* Attack type analysis
* Terrorist group analysis
* Casualty distribution
* Total casualties over time
* Region wise casualties
* Country wise casualties

---

# 📊 Visualizations Included

The project includes multiple meaningful charts:

* Attacks per year line chart
* Top 10 countries with most attacks
* Attacks by region
* Attack type distribution
* Word cloud of terrorist groups
* Total casualties over years
* Top regions by casualties
* Top countries by casualties

---

# 📈 Key Insights

* Terrorist attacks increased significantly after 2000
* Middle East & North Africa region has highest attacks
* Terrorism is concentrated in specific countries
* Bombing and armed assault are most common attack types
* Few terrorist groups dominate attack frequency
* Casualties fluctuate with peaks in certain years
* Some countries experience significantly higher casualties
* High severity incidents are limited but impactful

---

# 📊 Example Charts

## Attacks per Year

Shows trend of terrorist incidents over time.

## Top Countries with Most Attacks

Identifies countries most affected by terrorism.

## Attacks by Region

Highlights regional distribution of terrorist activities.

## Attack Type Distribution

Shows most common attack methods.

## Terrorist Group WordCloud

Displays most active terrorist groups.

## Total Casualties Over Time

Shows severity trend across years.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* WordCloud
* Google Colab

---

# 📌 Solution to Business Objective

The analysis provides insights into terrorism patterns, helping stakeholders identify high-risk regions, understand attack trends, and focus on major terrorist groups. These findings support better decision-making in security planning and risk management.

---

# 📌 Conclusion

The exploratory data analysis successfully identified global terrorism trends, regional concentration, and dominant terrorist groups. The insights gained from the dataset help understand terrorism patterns and support improved counter-terrorism strategies and global security planning.

---
