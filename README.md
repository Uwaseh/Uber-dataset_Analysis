#  Uber Fares Dataset Analysis – Power BI Project

##  Course Information

- *Course Title*: Introduction to Big Data Analytics (INSY 8413)  
- *Instructor*: Eric Maniraguha  
- *Institution*: Adventist University of Central Africa (AUCA)  
- *Project Type*: Analytical Data Visualization using Power BI  
- *Dataset Source*: [Kaggle – Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)  
- *Submission Date*: 25 July 2025  

---

##  Introduction

This project focuses on analyzing the Uber Fares Dataset to extract insights into pricing patterns, rider behavior, and time-based trends. By using Python for data preparation and Power BI for visualization, the project demonstrates key concepts of data wrangling, exploratory data analysis (EDA), feature engineering, and interactive dashboard design.

---

##  Objectives

- Understand and clean a real-world transportation dataset  
- Explore fare and trip-related patterns using Python and Power BI  
- Create new features for temporal analysis  
- Build an interactive, professional dashboard with insights  
- Provide data-driven business recommendations

---

## 🧪 Methodology

### 1. Data Acquisition
- Downloaded dataset from Kaggle
- Imported into Python using Pandas for inspection and preprocessing

### 2. Data Cleaning
- Removed missing and erroneous entries  
- Converted date-time fields to proper formats  
- Saved cleaned data as uber_cleaned.csv

### 3. Feature Engineering
- Extracted hour, day, month, and weekday from timestamps  
- Created peak/off-peak hour indicator  
- Calculated approximate ride durations (if data allows)  
- Final dataset saved as uber_enhanced.csv

### 4. Exploratory Data Analysis (Python)
- Generated statistics: mean, median, standard deviation  
- Visualized:
  - Fare amount distribution
  - Fare vs distance
  - Rides by time of day and weekday

### 5. Power BI Dashboard
- Imported enhanced dataset into Power BI Desktop  
- Built:
  - Histogram of fare amounts  
  - Scatter plot: fare vs distance  
  - Line charts: hourly & daily ride trends  
  - Map visualizations (if coordinates available)  
- Applied slicers, filters, and interactive drilldowns

---

## Tools and Technologies

- *Python* (Pandas, Seaborn, Matplotlib) – for data preparation and EDA  
- *Power BI Desktop* – for data visualization and interactive dashboard  
- *GitHub* – for version control and submission  
- *Kaggle* – for open-source dataset access

---
##  Screenshots (Upload Required)

>  *Upload your screenshots to the screenshots/ folder in your GitHub repo.*  
> Format: .png or .jpg. Use descriptive names like fare_distribution.png.

###  Power BI Dashboard Overview

![Dashboard Overview](screenshot/dashboard.PNG)

###  Fare Distribution Histogram

![Fare Distribution](screenshots/fare_distribution.png)

###  Fare vs Distance Scatter Plot

![Fare vs Distance](screenshot/distance.PNG)

###  Hourly Ride Trends

![Time Analysis](screenshot/hours.PNG)
