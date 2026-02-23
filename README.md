# 😰 Panic Attack Data Analysis Dashboard (Snowflake + Power BI)

![](Front%20Page.png)

Turning raw health/lifestyle data into an interactive dashboard in **Power BI**.  
In this project, I connected data from **Snowflake**, cleaned and transformed it using **Power Query**, created **DAX measures**, and built a dashboard to analyze **panic attack symptoms, trigger reasons, and lifestyle factors**—to understand patterns like how **sleep**, **caffeine**, and other habits may relate to **panic score** and **panic attack frequency**.



## 📌 Project Overview
**Goal:** Explore panic attack–related data and present insights in a clear, filterable dashboard.  
**Key idea:** Data cleaning + modeling + DAX measures → turns raw tables into decision-friendly visuals.



## 🧩 Dashboard Pages
This report contains multiple analysis pages with interactive slicers such as:
- **Panic Score** (High / Medium / Low)
- **Gender**
- **Trigger Reason** (Caffeine, Phobia, PTSD, Social Anxiety)
- **Medical History** (Anxiety, Depression, PTSD, None)

### 1) Symptoms Overview
Key insights covered:
- Count/distribution of common symptoms like **Dizziness, Trembling, Sweating**
- **Shortness of Breath** and **Chest Pain**
- Overall symptom patterns by slicers (panic score, trigger, gender, history)

![](Number%20Of%20PatientBySym.png)

### 2) Lifestyle & Attack Patterns

Key visuals included:
- Patients by Sleep Hours
- Patients by Panic Attack Duration (minutes)
- Patients by Drinks per Week

  ![](Other%20Requirements.png)

This page helps explore how lifestyle habits vary across panic score levels and different triggers.

### 3) Age Group Comparison

- Average Sleep Hours
- Average Panic Score
- Average Panic Attack Frequency

  ![](Age%20Group%20Analysis.png)

This page compares averages by Age Group (e.g., Adolescent vs Adult) across trigger reasons:

## 🌐 Data Source

- **Snowflake (connected as the primary data source)** 

**What made it interesting (real-world feel):**

- Data needed cleanup + standardization before visualization
- Metrics required DAX measures for meaningful comparisons
- Designing slicers was important to make insights easy to explore

## 🔧 Workflow (What I Did)
1. Connected **Snowflake** to **Power BI**
2. Cleaned & transformed the dataset in **Power Query**
   - Fixed data types
   - Handled blanks / inconsistent values
   - Prepared analysis-ready columns
3. Built a **data model** for slicing & comparisons
4. Created measures in **DAX**
   - KPIs like panic score averages, frequency averages, symptom counts, and distributions
5. Designed an **interactive dashboard**
   - Clear layout + slicers to explore patterns quickly


## 🧠 Skills Used
- Snowflake (data connection)
- Power BI (data modeling + dashboard design)
- Power Query (data cleaning + transformation)
- DAX (measures / KPIs)
- Data storytelling & insight-driven visualization
