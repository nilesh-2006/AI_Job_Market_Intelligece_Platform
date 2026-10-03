<div align="center">

# 🤖 AI Job Market Intelligence

**An end-to-end data analytics project on the AI job market — from raw data to an interactive Power BI dashboard.**

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Analysis-4479A1?logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Purpose](https://img.shields.io/badge/Purpose-Portfolio-blueviolet)

![AI Job Market Intelligence Dashboard](powerbi/dashboard_screenshot.png)

</div>

---

## 📑 Table of Contents

- [About This Project](#-about-this-project)
- [Project at a Glance](#-project-at-a-glance)
- [Key Insights](#-key-insights)
- [Workflow](#-workflow)
- [Analysis Performed](#-analysis-performed)
- [SQL Business Analysis](#-sql-business-analysis)
- [Power BI Dashboard](#-power-bi-dashboard)
- [Technology Stack](#-technology-stack)
- [Getting Started](#-getting-started)
- [Repository Structure](#-repository-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Improvements](#-future-improvements)
- [Author](#-author)
- [Disclaimer](#-disclaimer)

---

## 📌 About This Project

This project analyzes AI job postings to understand **job demand, salary patterns, experience requirements, job categories, countries, remote work, technical skills, and LLM/GenAI-related roles**.

It follows a complete analytics workflow:

```text
Data Understanding → Data Quality → Data Cleaning → Feature Engineering
        → EDA → SQL Analysis → Business Insights → Power BI Dashboard
```

The work combines **Python** (cleaning & EDA), **MySQL** (business analysis) and **Power BI + DAX** (interactive reporting), demonstrating proficiency across the full data analyst toolkit.

---

## 🎯 Project at a Glance

| Area | Focus | Tool |
|---|---|---|
| 🧹 Data Preparation | Quality checks, cleaning, feature engineering | Python, Pandas |
| 📊 Exploratory Analysis | Salary, roles, countries, skills, trends | Matplotlib, Seaborn |
| 🗄 Business Analysis | 11 structured business questions | MySQL, SQLAlchemy |
| 📈 Dashboard | KPIs, charts and interactive filters | Power BI, DAX |

### Results Snapshot

| Metric | Result |
|---|---|
| Total job postings analyzed | ~2K |
| Average annual salary | $194.57K |
| Median annual salary | $180.00K |
| Average experience required | 6 years |
| LLM / GenAI jobs | 279 |
| Remote jobs | 340 |
| Top country by postings | USA (528) |
| Most in-demand skill | Python (942) |
| Most common work arrangement | Hybrid (46%) |
| LLM vs non-LLM average salary | $208.1K vs $190.1K |

---

## 💡 Key Insights

| # | Insight |
|:---:|---|
| 1 | **Salary rises with experience.** Expert-level roles average $225K, compared with $176K for entry level. Senior ($196K) and mid-level ($192K) salaries are close to each other. |
| 2 | **Average salary ($194.57K) is higher than median ($180K),** which suggests a right-skewed distribution pulled up by a few high-paying roles. |
| 3 | **LLM / GenAI roles pay a premium.** They average $208.1K against $190.1K for non-LLM roles, about $18K (~9.5%) more. |
| 4 | **The USA dominates the market** with 528 postings, far ahead of the UK (89), Japan (79) and the Netherlands (78). |
| 5 | **AI Engineer is the largest job category,** at 63.28% of postings, followed by Data Science at 16.63%. |
| 6 | **Python is the most required skill** (942 postings), followed by SQL (422), Deep Learning (91) and Generative AI (58). |
| 7 | **Hybrid work is the most common arrangement** (46%), followed by fully remote (30%) and on-site (24%). |
| 8 | **Job postings grew sharply in early 2026.** Volume stayed relatively flat through 2025, then rose steeply from around Dec 2025 to Mar 2026. |
| 9 | **Newer roles are in demand.** Prompt Engineer (67), Multimodal AI (61), NLP Engineer (55) and RAG Engineer (49) all appear among the top roles. |

---

## 🔄 Workflow

| Step | Stage | Notebook |
|:---:|---|---|
| 1 | Data Understanding | `01_Data_Understanding.ipynb` |
| 2 | Data Quality Analysis | `02_Data_Quality_Analysis.ipynb` |
| 3 | Data Cleaning | `03_Data_Cleaning.ipynb` |
| 4 | Feature Engineering | `04_Feature_Engineering.ipynb` |
| 5 | Exploratory Data Analysis | `05_Exploratory_Data_Analysis.ipynb` |
| 6 | SQL Business Analysis | `06_SQL_Business_Analysis.ipynb` |
| 7 | Business Insights | `07_Business_Insights.ipynb` |
| 8 | Power BI Data Preparation | `08_PowerBI_Data_Preparation.ipynb` |

### Data Preparation Highlights

- Missing value analysis and duplicate detection
- Data type validation and invalid value detection
- Category consistency checks and salary cleaning
- Experience grouping and salary range calculation
- Skill flag preparation (Python, SQL, ML, DL, GenAI)

---

## 📊 Analysis Performed

### 1. Market Overview
- Total AI job postings
- Average and median annual salary
- Average years of experience
- Salary distribution

### 2. Job Roles & Categories
- Top AI job roles by number of postings
- Job category distribution
- Average salary by role and category

### 3. Experience & Salary
- Average salary across experience groups
- Experience requirements
- Relationship between experience and salary

### 4. Geographic Analysis
- Top countries by AI job postings
- Average salary by country
- Country-wise job distribution

### 5. Remote Work
- Fully remote, hybrid and on-site jobs
- Salary across work arrangements

### 6. Technical Skills
Demand analysis of **Python · SQL · Machine Learning · Deep Learning · Generative AI**

### 7. LLM / GenAI
- LLM / GenAI-related vs non-LLM jobs
- Average salary comparison

### 8. Job Posting Trends
- Posting volume over time (Jan 2025 – Mar 2026) to understand market changes

---

## 🗄 SQL Business Analysis

MySQL is used for structured business analysis. Example questions answered:

| # | Question |
|:---:|---|
| 1 | How many AI job postings are present? |
| 2 | What is the average annual salary? |
| 3 | What is the median annual salary? |
| 4 | Which job roles have the most postings? |
| 5 | Which categories have the most jobs? |
| 6 | How does salary vary by experience? |
| 7 | Which countries have the most AI jobs? |
| 8 | Which technical skills are most frequently required? |
| 9 | How many jobs require Python, SQL, ML, DL and GenAI? |
| 10 | How do LLM and non-LLM salaries compare? |
| 11 | How do AI job postings change over time? |

---

## 📈 Power BI Dashboard

The **AI Job Market Intelligence Platform** is an interactive dashboard with a dark theme, KPI cards and a filter panel.

![AI Job Market Intelligence Dashboard](powerbi/dashboard_screenshot.png)

### KPI Cards

| KPI | Value |
|---|---|
| Total Jobs | ~2K |
| Average Salary | 194.57K |
| Median Salary | 180.00K |
| Avg Experience | 6 |
| LLM Jobs | 279 |
| Remote Jobs | 340 |

### Visuals

| Visual | What it shows |
|---|---|
| Avg Salary by Experience Level | Expert, Senior, Mid and Entry level salary comparison |
| Remote Work Breakdown | Hybrid, Fully Remote and On-Site split (donut chart) |
| AI Job Categories | Category distribution (donut chart) |
| Top 10 Country Job Postings | Countries with the most AI jobs |
| Top 10 Job Roles | Most frequently posted roles |
| Top Required AI Skills | Python, SQL, Deep Learning, Generative AI |
| Job Postings Trend | Monthly posting volume, Jan 2025 – Mar 2026 |
| Avg Salary: LLM vs Non-LLM | Salary comparison between role types |

### Interactive Filters

`Job Category` · `Country` · `Experience Group` · `Remote Work` · `Posting Year`

A **Clear Filters** button resets all dashboard selections.

### DAX Measures

```dax
Total Job Postings = DISTINCTCOUNT(ai_jobs[job_id])

Average Salary = AVERAGE(ai_jobs[annual_salary_usd])

Median Salary = MEDIAN(ai_jobs[annual_salary_usd])

Average Experience = AVERAGE(ai_jobs[years_of_experience])
```

---

## 🛠 Technology Stack

### Languages & Core Tools

| Tool | Purpose |
|---|---|
| **Python 3.8+** | Data cleaning, preprocessing and analysis |
| **MySQL** | Database and business analysis |
| **Power BI + DAX** | Interactive dashboard and KPIs |
| **Jupyter Notebook** | Analysis workflow |
| **Git & GitHub** | Version control |

### Python Libraries

| Library | Purpose |
|---|---|
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| SQLAlchemy | Python–MySQL connection |
| PyMySQL | MySQL database driver |
| OpenPyXL | Excel file support |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- MySQL Server
- Jupyter Notebook or JupyterLab
- Power BI Desktop (to open the `.pbix` file)

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/AI_Job_Market_Intelligence.git
cd AI_Job_Market_Intelligence

# Create a virtual environment
python -m venv venv

# Activate it
venv\Scripts\activate          # Windows
source venv/bin/activate       # macOS / Linux

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook
```

Run the notebooks in order, from `01_Data_Understanding` to `08_PowerBI_Data_Preparation`.

### MySQL Setup

```sql
CREATE DATABASE ai_job_market;
USE ai_job_market;
```

All setup and analysis scripts are in the `sql/` folder.

> ⚠️ **Never commit database passwords, API keys or other credentials to GitHub.**

---

## 📂 Repository Structure

```text
AI_Job_Market_Intelligence/
├── README.md                              # This file
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/                               # Original dataset
│   └── processed/                         # Cleaned & engineered data
│
├── notebooks/                             # 📓 Python analysis
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Quality_Analysis.ipynb
│   ├── 03_Data_Cleaning.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Exploratory_Data_Analysis.ipynb
│   ├── 06_SQL_Business_Analysis.ipynb
│   ├── 07_Business_Insights.ipynb
│   └── 08_PowerBI_Data_Preparation.ipynb
│
├── sql/                                   # 🗄 MySQL scripts
│   ├── 01_database_setup.sql
│   ├── 02_table_creation.sql
│   ├── 03_basic_analysis.sql
│   ├── 04_salary_analysis.sql
│   ├── 05_skill_analysis.sql
│   ├── 06_demand_analysis.sql
│   └── 07_llm_analysis.sql
│
├── powerbi/                               # 📈 Dashboard
│   ├── AI_Job_Market_Intelligence.pbix
│   └── dashboard_screenshot.png
│
├── reports/
├── images/
├── docs/
└── output/
```

---

## 💡 Skills Demonstrated

| Category | Skills |
|---|---|
| **Programming** | Python, Pandas, NumPy |
| **Database** | SQL, MySQL, SQLAlchemy |
| **Analytics** | Data Cleaning, Feature Engineering, EDA, Data Visualization |
| **BI & Reporting** | Power BI, DAX, Dashboard Development |
| **Business** | Business Analysis, Business Insight Generation |
| **Tools** | Git & GitHub |

---

## 🔮 Future Improvements

- [ ] Add more recent AI job market data
- [ ] Add company-level analysis
- [ ] Add job-description NLP analysis
- [ ] Build an AI-powered job recommendation system
- [ ] Add salary prediction using Machine Learning
- [ ] Add skill recommendations for specific AI roles
- [ ] Deploy an interactive Streamlit application
- [ ] Build an automated data pipeline

---

## 👤 Author

**Nilesh Pardhi**
B.Tech – Artificial Intelligence and Machine Learning

**Skills:** Python | SQL | Power BI | Excel | Data Analysis | Machine Learning

- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- LinkedIn: [your-linkedin-id](https://linkedin.com/in/your-linkedin-id)

---

## ⚠️ Disclaimer

This project is created for educational and portfolio purposes. The analysis and insights depend on the dataset used in the project.

<div align="center">

*Built with ❤️ and a lot of ☕*

</div>