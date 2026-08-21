# AI & SCREEN TIME IMPACT ON STUDENT'S PERFORMANCE
Analyzed a dataset of 7,200 students to understand the relationship between AI usage, screen time, study habits, sleep, physical activity, wellbeing, and academic performance.
# Student AI Usage & Academic Performance Analysis

## 📌 Project Overview

This project analyzes **7,200 student records** to understand how Artificial Intelligence (AI) usage, screen time, social media usage, study habits, sleep, physical activity, and wellbeing relate to academic performance.

The project uses **Excel, SQL, Python, and Power BI** to perform data cleaning, analysis, visualization, and dashboard development.

---

## 🎯 Project Objectives

* Analyze student demographics and academic performance.
* Understand students' AI usage patterns.
* Identify the most commonly used AI tools.
* Analyze the purposes for which students use AI.
* Examine screen time and social media usage.
* Analyze the relationship between AI usage and GPA.
* Analyze the relationship between screen time and GPA.
* Study the relationship between study hours, sleep, focus, and GPA.
* Analyze student wellbeing indicators such as anxiety and attention.
* Build an interactive Power BI dashboard for reporting and decision-making.

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                                 |
| ------------------- | --------------------------------------- |
| **Microsoft Excel** | Data cleaning and preparation           |
| **SQL**             | Data querying and analysis              |
| **Python**          | Data cleaning and exploratory analysis  |
| **Pandas**          | Data manipulation                       |
| **Power BI**        | Interactive dashboard and visualization |
| **DAX**             | Measures and KPI calculations           |

---

## 📊 Dataset

The dataset contains **7,200 student records** and includes information related to:

* Student ID
* Age
* Age Group
* Gender
* City
* AI Usage
* AI Usage Level
* Primary AI Tool
* AI Purpose
* Screen Time
* Screen Time Level
* Social Media Usage
* Study Hours
* Study Level
* Sleep Hours
* Sleep Level
* Physical Activity
* Physical Activity Level
* Attention Level
* Focus Level
* GPA
* GPA Level
* Anxiety Score
* Anxiety Level
* Parental Control

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Excel Data Cleaning
     ↓
Python Data Cleaning & Analysis
     ↓
SQL Data Analysis
     ↓
Power BI Data Modeling
     ↓
DAX Measures
     ↓
Interactive Dashboard
     ↓
Insights & Reporting
```

---

## 📈 Power BI Dashboard

The Power BI report contains multiple pages.

### 1. Student Overview

Key Performance Indicators:

* Total Students
* Average GPA
* Average AI Usage
* Average Study Hours
* Average Sleep Hours
* Average Anxiety

Visualizations:

* Students by City
* Students by Gender
* Students by Age Group
* AI Usage Level
* GPA Level

### 2. AI & Digital Usage

Visualizations:

* AI Usage by AI Tool
* AI Usage by Purpose
* Screen Time by Level
* Social Media Hours
* AI Usage vs GPA
* Screen Time vs GPA

### 3. Academic Performance

Visualizations:

* GPA by Study Level
* GPA by Sleep Level
* GPA by Focus Level
* Study Hours vs GPA
* AI Usage vs GPA
* Screen Time vs GPA

### 4. Student Wellbeing

Visualizations:

* Anxiety Level
* Attention Level
* Physical Activity Level
* Parental Control
* GPA by Sleep Level
* GPA by Focus Level

---

## 🧮 Key DAX Measures

### Total Students

```DAX
Total Students = DISTINCTCOUNT(Sheet1[Student_ID])
```

### Average GPA

```DAX
Average GPA = AVERAGE(Sheet1[GPA_10])
```

### Average AI Usage

```DAX
Average AI Usage = AVERAGE(Sheet1[Daily_AI_Usage_Hrs])
```

### Average Study Hours

```DAX
Average Study Hours = AVERAGE(Sheet1[Daily_Study_Hrs])
```

### Average Sleep Hours

```DAX
Average Sleep Hours = AVERAGE(Sheet1[Daily_Sleep_Hrs])
```

### Average Anxiety

```DAX
Average Anxiety = AVERAGE(Sheet1[Anxiety_Score_1_10])
```

---

## 🔍 Key Analysis Areas

### AI Usage

Analyze which AI tools students use and why they use them.

### Academic Performance

Compare GPA across different study, sleep, and focus levels.

### Digital Usage

Analyze screen time and social media usage patterns.

### Wellbeing

Explore anxiety, attention, physical activity, and parental control levels.

### Relationship Analysis

Use scatter charts to investigate:

* AI Usage vs GPA
* Screen Time vs GPA
* Study Hours vs GPA

> **Note:** Relationships observed in the dashboard should be interpreted as associations, not proof that one factor directly causes another.

---

## 📁 Recommended GitHub Repository Structure

```text
student-ai-academic-analysis/
│
├── README.md
│
├── data/
│   └── student_dataset.xlsx
│
├── python/
│   └── data_analysis.py
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── student_dashboard.pbix
│
├── screenshots/
│   ├── dashboard_overview.png
│   ├── ai_analysis.png
│   ├── academic_performance.png
│   └── wellbeing.png
│
└── documentation/
    └── project_description.md
```

---

## 💡 Project Highlights

* Worked with a dataset containing **7,200 student records**.
* Performed data cleaning and preparation.
* Used Python Pandas for data analysis.
* Used SQL for analytical queries.
* Created DAX measures in Power BI.
* Designed an interactive multi-page dashboard.
* Used KPI cards, bar charts, column charts, donut charts, and scatter plots.
* Analyzed relationships between digital behavior and academic performance.

---

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Open the dataset from the `data` folder.
3. Run the Python analysis scripts.
4. Execute the SQL queries using your SQL environment.
5. Open the `.pbix` file using Power BI Desktop.
6. Explore the dashboard using the available filters and slicers.

---

## 👩‍💻 Skills Demonstrated

**Data Analysis | Data Cleaning | Excel | SQL | Python | Pandas | Power BI | DAX | Data Visualization | Dashboard Development | Exploratory Data Analysis**

---

## 📌 Conclusion

This project demonstrates an end-to-end **Data Analyst workflow**, starting from data cleaning and preparation and progressing through SQL and Python analysis to interactive Power BI reporting.

The dashboard provides a clear view of student AI usage, digital behavior, academic performance, and wellbeing, helping users explore patterns and relationships within the dataset.# -AI-SCREEN-TIME-IMPACT-ON-STUDENT-S-PERFORMANCE
This project analyzes how AI usage and screen time affect students’ academic performance. It explores relationships between AI usage, screen time, study habits, GPA, and overall student well-being to identify key factors influencing academic success.
