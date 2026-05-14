# Depaul-University-Admission
DePaul Admissions Intelligence is a data analytics project focused on exploring graduate recruitment and outreach data from 2022–2026. Using Python, Pandas, Matplotlib, and ReportLab, the project identifies data quality issues, recruitment trends, counsellor workload imbalances, and admissions pipeline risks while generating actionable insights.

# 🎓 DePaul University Admissions Intelligence — Global Graduate Recruitment & Outreach Analytics (2022–2026)

## 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and data quality assessment on the DePaul University graduate admissions outreach dataset covering the years 2022–2026.

The objective of this analysis was to uncover recruitment trends, identify data quality issues, analyze counsellor workload distribution, and generate actionable insights that can improve student recruitment strategy and operational efficiency.

---

# 📊 Dataset Information

- **Dataset Name:** `DePaul_Data.csv`
- **Total Records:** 7,541
- **Unique Students:** 4,998
- **Countries Represented:** 95
- **Programmes Analyzed:** 45
- **Time Period:** 2022–2026

Each row in the dataset represents a student outreach interaction or admissions touchpoint rather than a unique student.

---

# 🛠️ Tools & Technologies Used

## Programming & Analysis
- Python
- Pandas
- NumPy

## Data Visualization
- Matplotlib

## Reporting
- ReportLab (PDF generation)

## Development Tools
- Jupyter Notebook
- Git & GitHub

---

# 📂 Project Structure

```bash
DePaul-Admissions-Intelligence/
│
├── data/
│   └── DePaul_Data.csv
│
├── notebooks/
│   └── admissions_eda.ipynb
│
├── reports/
│   └── Week1_Itumeleng_Shabangu_DataExplorationReport.pdf
│
├── visuals/
│   ├── country_distribution.png
│   ├── counsellor_workload.png
│   ├── intake_distribution.png
│   └── programme_analysis.png
│
├── README.md
└── requirements.txt
🔍 Step-by-Step Analysis Process
1️⃣ Dataset Familiarisation

The first phase involved understanding:

Dataset structure
Number of rows and columns
Data types
Missing values
Duplicate records
Key business entities
Key Findings
7,541 total records
4,998 unique students
33.7% duplicate rows due to event-based logging
India accounted for 61% of all records
2️⃣ Data Cleaning & Quality Assessment
Tasks Performed
Checked null values across all columns
Identified duplicate records
Reviewed inconsistent field names
Investigated schema issues
Flagged incomplete analytical fields
Critical Issues Identified
Major → 100% null
Status → 100% null
Degree_Type → 100% null
Counsler column misspelled and fully null
Recieved_At column misspelled
Recommendation

Use Caller_Name instead of Counsler for workload analysis.

3️⃣ Exploratory Data Analysis (EDA)
Analysis Conducted
📍 Geographic Distribution
Analyzed student distribution by country
Identified heavy dependency on India
📍 Programme Demand Analysis
Identified top-performing academic programmes
STEM and Business Analytics dominated applications
📍 Counsellor Workload Analysis
Compared outreach volumes across counsellors
Found severe workload imbalance
📍 Intake Semester Analysis
Evaluated intake distribution across Fall, Spring, Winter, and Summer
📍 Outreach Outcome Analysis
Analyzed pipeline outcomes and unresolved applications
📈 Visualizations Created

The following visualizations were developed using Matplotlib:

Top Countries by Applications
Counsellor Workload Distribution
Intake Semester Distribution
Programme Demand Analysis
Application Source Comparison
Outreach Outcome Frequency
💡 Key Insights
Geographic Concentration Risk

India represented 61% of all applications, creating a major dependency risk.

STEM Programme Dominance

Most applications targeted STEM and analytics-related programmes.

Fall Intake Pressure

66% of applications were concentrated in the Fall semester.

Pipeline Leakage

Large volumes of records remained in “Follow Up” or “Missing Transcript” status.

Counsellor Capacity Imbalance

One counsellor handled almost half of all outreach interactions.

Data Infrastructure Gaps

Several business-critical fields were entirely missing.

📊 Technologies Demonstrated

This project demonstrates practical skills in:

Data Cleaning
Exploratory Data Analysis
Business Intelligence
Data Visualization
Python Programming
Dashboard Thinking
Analytical Reporting
Insight Generation
🚀 Future Improvements

Planned future enhancements include:

Predictive admissions modeling
Conversion rate analysis
Student segmentation
Automated dashboard development
Power BI integration
Recruitment ROI analysis
📷 Sample Outputs
Counsellor Workload Example
Jagdeep → 2,083 contacts
Rohit → 1,200 contacts
Priya → 870 contacts
Lavnaya → 195 contacts
📚 Key Python Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from reportlab.platypus import *
⚙️ How to Run the Project
1. Clone Repository
git clone https://github.com/tumishabangu12-cell/depual-admissions-intelligence.git
2. Navigate into Project Folder
cd depual-admissions-intelligence
3. Install Dependencies
pip install -r requirements.txt
4. Run Jupyter Notebook
jupyter notebook
📌 Project Outcome

This project successfully identified:

Major data quality problems
Recruitment concentration risks
Operational bottlenecks
Counsellor workload imbalance
Admissions pipeline inefficiencies

The analysis provides a strong foundation for predictive analytics and business intelligence development in future project phases.

👨‍💻 Author
ITUMELENG SHABANGU

Data Analyst | AI & Automation Specialist

📍 Soweto, Gauteng
📧 tumishabangu12@gmail.com

🔗 GitHub: https://github.com/tumishabangu12-cell

🔗 LinkedIn: https://www.linkedin.com/in/itumeleng-gloria-a8267b349

⭐ If you found this project useful

Please consider:

Starring the repository
Following my GitHub profile
Connecting with me on LinkedIn
