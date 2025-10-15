# 🧠 Impact of Screen Time on Mental Health
---

## 📋 Overview
This project investigates the **impact of digital screen time on mental health** by analyzing relationships between device usage patterns and self-reported mental well-being.  
The dataset captures daily screen time across multiple devices (phones, laptops, tablets, TVs) and key psychological indicators such as **stress levels**, **mood**, and **mental health scores**.

The goal is to understand how digital lifestyles influence mental wellness and to visualize these insights through an interactive Excel dashboard.

---

## 🎯 Objectives
- Measure **average screen time by device type** (Phone, Laptop, Tablet, TV)  
- Assess **average stress levels** and **mental well-being scores**  
- Explore **correlations** between screen time and mental health  
- Build an **Excel dashboard** summarizing key insights and visuals  

---


---

## ⚙️ Methodology

### 1. Data Preparation
- Imported and cleaned dataset in Excel  
- Standardized columns:
  - `Daily_Screen_Time_Hours`
  - `Device_Type`
  - `Stress_Level`
  - `Mental_Health_Score`
- Removed missing or inconsistent values  

### 2. Exploratory Analysis
- Calculated descriptive statistics (mean, median, standard deviation)  
- Visualized **screen time distribution per device**  
- Created a **correlation matrix** to measure relationships between screen time and mental health indicators  

### 3. Regression Analysis
- Conducted multiple linear regression using Excel’s Data Analysis Toolpak:
  \[
  Mental\_Health\_Score = β₀ + β₁(Screen\_Time) + β₂(Stress\_Level) + ε
  \]
- Evaluated:
  - R² and Adjusted R²
  - Significance (p-values)
  - ANOVA results  

### 4. Dashboard Design
- **Sheet 1:** Average screen time by device (bar chart)  
- **Sheet 2:** Stress and well-being summary (trendlines, gauges)  
- **Sheet 3:** Correlation insights (scatter plots or sparklines)  
- **Sheet 4:** Filters for demographic categories (interactive slicers)  

---

## 📊 Key Insights
- **Mobile devices** had the highest daily screen time (≈6 hours/day)  
- **Stress levels** increased with total screen exposure  
- **Mental well-being** scores showed a mild negative correlation with screen time  
- Regression model indicates **screen time alone has limited predictive power**; stress levels and lifestyle factors significantly moderate mental health outcomes  

---

## 🧰 Tools & Technologies
- **Microsoft Excel / Excel 365**  
- **Power Query** – data cleaning & transformation  
- **Data Analysis Toolpak** – regression & correlation  
- **PivotTables and Charts** – summary visualization  
- **Dynamic Arrays (Excel 365)** – advanced dashboard automation  
