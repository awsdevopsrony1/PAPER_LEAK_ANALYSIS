# 📊 India Exam Paper Leak Analysis (2014–2024)

### End-to-End Data Analytics Project | Python • Power Query • Power BI

An end-to-end data analysis project examining exam paper leak incidents across India — from raw, unstructured data to a fully interactive Power BI dashboard. This project uncovers patterns in leak frequency, conducting body accountability, state-wise vulnerability, and the actions taken in response to these incidents.

---

## 🎯 Project Objective

Exam paper leaks have become a recurring issue affecting millions of students across India. This project aims to:

- Consolidate scattered incident data (2014–2024) into a single, clean dataset
- Identify trends in leak frequency over time
- Analyze which states and conducting bodies (Central / State / Private) are most affected
- Evaluate how authorities respond — exam cancellations, legal action, chargesheets, etc.
- Present findings through an interactive, filterable Power BI dashboard

---

## 🧭 Project Workflow

The project follows a 5-stage end-to-end analytics pipeline:

| Stage | Description | Tools Used |
|---|---|---|
| **1. Data Collection** | Gathered incident data from news articles, government reports, and other public sources (2014–2024) | Excel / CSV |
| **2. Data Cleaning** | Handled missing values, removed duplicates, standardized text, fixed date formats | Python (Pandas) |
| **3. Data Transformation** | Loaded cleaned data, merged & reshaped tables, created relationships, fixed data types | Power Query |
| **4. Data Visualization** | Built KPIs, charts, maps, and a one-page interactive dashboard with slicers | Power BI |
| **5. Insights & Reporting** | Derived trend analysis, state-wise insights, and key recommendations | Power BI / Report |

<p align="center">
  <img src="Project%20Workflow.png" alt="Project Workflow" width="800"/>
</p>

---

## 🗂️ Dataset Overview

- **Time period covered:** 2014 – 2024
- **Total incidents recorded:** 66
- **States/UTs affected:** 24
- **Fields include:** Year, State, Conducting Body Type (State/Central/Private), Exam Name, Leak Confirmation Status (Confirmed/Accused), Action Taken After Leak

> *Note: Data was compiled from publicly available news reports and government disclosures. It may not represent an exhaustive record of all incidents.*

---

## 📈 Dashboard Highlights

**Key Metrics (KPIs):**
- **Total Incidents:** 66
- **Confirmed Leak Rate:** 73%
- **States Affected:** 24
- **Current Year Incidents:** 13

**Visuals included:**
- 📅 Leaks by Year (2014–2024) — trend line
- 🥧 Total Incidents by Conducting Body Type (State vs Central vs Private)
- 🍩 Leak Confirmation Status (Confirmed vs Accused)
- 📊 Action Taken After Leak (Exam Cancelled, Legal Action, Chargesheet, etc.)
- 🏆 Top 5 States by Leak Incidents
- 🔍 Interactive slicers for Year and Conducting Body Type

---

## 🔑 Key Insights

- Uttar Pradesh recorded the highest number of leak incidents (11), followed by cases spanning multiple states (7) and Maharashtra (6).
- **75.76%** of incidents involved **State-conducted exams**, highlighting a governance gap at the state level.
- Leak incidents have shown a **sharp rise since 2020**, peaking at 15 incidents in 2023.
- **Exam cancellation** (30 cases) was the most common response, followed by **legal action** (19 cases).
- Nearly **1 in 4** reported cases remain in "accused" status without confirmation, pointing to slow investigative closure.

---

## 🛠️ Tools & Technologies

- **Python (Pandas)** — Data cleaning and preprocessing
- **Power Query** — Data transformation and modeling
- **Power BI** — Dashboard design and visualization
- **Excel/CSV** — Raw data storage

---

## 📁 Repository Structure

```
PAPER_LEAK_ANALYSIS/
│
├── Paper_leaks_India.csv          # Raw dataset
├── Paper_Leaks_Clean.csv          # Cleaned dataset (post Python processing)
├── paper_leak.ipynb               # Python data cleaning notebook
├── POWER_BI_DASHBOARAD.pbix       # Power BI dashboard file
├── Project Workflow.png           # Workflow diagram
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/awsdevopsrony1/PAPER_LEAK_ANALYSIS.git
   ```
2. Open `paper_leak.ipynb` to review the data cleaning process
3. Open `POWER_BI_DASHBOARAD.pbix` in **Power BI Desktop** to explore the interactive dashboard
4. Use the **Year** and **Conducting Body Type** filters to drill into specific insights

---

## 🔮 Future Scope

- Expand dataset with more granular data (exam-level, subject-level)
- Add predictive modeling to flag high-risk states/exams
- Automate data collection via web scraping for real-time updates
- Publish dashboard to Power BI Service for public access

---

## 👤 Author

**[Your Name]**
📧 [your.email@example.com]
🔗 [LinkedIn](#) | [Portfolio](#)

---

⭐ If you found this project useful, consider giving it a star on GitHub!
