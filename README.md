# 🚦 Traffic Slowness Data Analysis

This project explores and visualizes road traffic data in Brazil, focusing on how different incidents—like rain, accidents, and road works—affect traffic flow. The goal is to identify patterns and understand which conditions contribute most to traffic slowness.

## 📁 Dataset Overview

The dataset includes traffic condition records coded by hour and day of the week. Key attributes include:

* **Slowness in Traffic (%)**
* **Incident types** such as rain, fog, vehicle breakdown, and accidents
* **Hour (Coded)** for time-wise distribution

## 🔧 Data Cleaning

* Converted percentage strings to float values for numerical analysis.
* Removed unnecessary or non-relevant columns.
* Checked for null values and ensured consistent datatypes.

## 📊 Exploratory Data Analysis (EDA)

* Visualized the **distribution** of traffic slowness.
* Identified the **frequency** of different traffic incidents.
* Used bar and histogram charts to analyze incidents and traffic patterns.

## 🔍 Correlation Analysis

* Calculated correlations between each incident type and slowness in traffic.
* Found which incidents contribute most significantly to traffic delays.

## 📆 Weekday Pattern Insights

* Data was split by weekdays (Monday to Friday).
* Plotted slowness trends per hour for each day.
* Helped identify time-of-day patterns for peak congestion.

## 📌 Insights & Observations

* 🚗 **Accidents and rain** were among the top contributors to traffic slowness.
* 📈 **Morning hours** generally experienced higher slowness percentages.
* 📊 **Tuesday and Thursday** had more consistent slowness patterns across all time slots.

