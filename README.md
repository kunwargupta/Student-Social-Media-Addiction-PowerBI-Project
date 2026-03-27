# Student Social Media Usage & Wellbeing Analysis (Power BI Project)

## Project Overview

This project analyzes how students’ social media usage impacts their mental health, sleep patterns, academic performance, and relationships. The objective was to design an interactive Power BI dashboard that not only visualizes data but also communicates meaningful insights.

---

## Objectives

* Analyze the relationship between social media usage and student wellbeing
* Identify patterns in addiction, sleep, and academic performance
* Build an interactive dashboard with drill-through and bookmarks
* Present insights in a clear and actionable format

---

## Dataset Description

The dataset consists of two primary tables:

* **Student Details**: demographic information, academic level, sleep hours, mental health score, addiction score
* **Platform Details**: social media usage patterns, platform preference, and academic impact

These tables are connected using **Student_ID**.

---

## Steps Performed

### 1. Data Loading & Cleaning

* Imported Excel data into Power BI
* Validated data types and consistency
* Established relationships between tables

### 2. Data Modeling

* Created relationship using `Student_ID`
* Structured data for efficient analysis
* Added a Date Table for scalability

### 3. Data Transformation

**Calculated Columns:**

* Health Band (Good / Average / Poor)
* Conflict Level (Low / Medium / High)

**Measures:**

* Average Usage Hours
* Average Sleep Hours
* Percentage Affected Academically
* Addicted Student Count

---

## Dashboard Pages

### 1. Executive Overview

* KPI cards (Total Students, Avg Usage, Sleep, Academic Impact)
* Addiction vs Academic Level
* Gender Distribution
* Usage Trend by Age

### 2. Mental Health & Lifestyle

* Addiction vs Mental Health (scatter plot)
* Sleep pattern by age
* Mental health segmentation

### 3. Academic Impact

* Usage comparison across academic levels
* Platform-wise academic impact analysis

### 4. Relationships & Conflicts

* Relationship status distribution
* Conflict levels across relationship types
* Student-level addiction table

### 5. Interactive Story View

* Bookmark-based toggle (Gender vs Academic Level)
* Dynamic switching visuals

### 6. Drill-through Page

* Student-level detailed analysis using Student_ID

### 7. Insights Page

* Consolidated summary of findings

---

## Advanced Features Implemented

* Bookmark navigation
* Toggle buttons (Gender vs Academic Level)
* Drill-through functionality
* Dynamic insight switching using bookmarks
* Consistent UI/UX design across pages

---

## Challenges Faced & Solutions

**1. SWITCH(TRUE()) understanding**

* Initially unclear usage
* Learned it simplifies multiple conditional logic

**2. Bookmark visibility issues**

* Elements appearing across all views
* Resolved using Selection Pane and controlling Display settings

**3. Buttons getting removed unintentionally**

* Caused due to grouping behavior
* Fixed by managing elements individually

**4. Scatter plot not displaying data**

* Issue with raw values instead of aggregation
* Resolved using appropriate measures (Average)

**5. Bookmark affecting full page state**

* Learned difference between Display and Data options
* Disabled Data where required

---

## Key Insights

* Higher social media usage is associated with reduced sleep duration
* Approximately 64% of students report negative academic impact
* Younger students exhibit higher addiction levels
* Increased addiction correlates with lower mental health scores
* Social media usage contributes to relationship conflicts

---

## Conclusion

The analysis indicates that excessive social media usage negatively affects multiple aspects of student wellbeing, including sleep, mental health, academic performance, and relationships. Younger students appear more vulnerable, highlighting the importance of balanced digital habits.

---

## Tools Used

* Power BI
* Excel
* DAX

---

This project demonstrates the ability to transform raw data into meaningful insights using interactive dashboards and practical data analysis techniques.
