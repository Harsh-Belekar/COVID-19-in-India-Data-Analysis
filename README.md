# 📊 COVID-19 in India – Data Analysis Using Python

## 📌 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of **COVID-19 cases and vaccination trends in India** using Python.

The analysis focuses on understanding confirmed cases, recoveries, deaths, and vaccination progress across different states, time periods, genders, age groups, and dose types.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-red?logo=pandas) ![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange) ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-lightgreen) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![EDA](https://img.shields.io/badge/Type-Exploratory%20Data%20Analysis-green) ![Visualization](https://img.shields.io/badge/Charts-Multiple-orange) ![Dataset](https://img.shields.io/badge/Data-COVID19%20India-red) ![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 🎯 Objective

* Analyze COVID-19 case trends in India
* Examine recovery and mortality patterns
* Study vaccination progress and demographic distribution
* Identify seasonal and state-wise variations
* Analyze vaccination trends across gender, age groups, and dose types
* Generate meaningful insights from COVID-19 and vaccination data
* Demonstrate the use of Python for real-world data analysis and visualization

---

## 🧰 Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 📁 Project Folder Structure

```text
COVID-19-in-India-Data-Analysis/
│
├── README.md
├── requirements.txt
│
├── Data/
│   ├── Raw_data/
│   │   ├── covid_19_india.csv
│   │   └── covid_vaccine_statewise.csv
│   │
│   └── Clean_data/
│       ├── covid_19_india_cleaned.csv
│       └── covid_vaccine_statewise_cleaned.csv
│
├── Docs/
│   └── COVID-19 in India – Data Analysis Report.pdf
│
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   └── 02_Data_Analysis.ipynb
│
└── images/
    ├── 01_COVID-19_Case_Distribution_in_India.png
    ├── 02_Daily_Case_Distribution.png
    ├── 03_Daily_Cured_Case_Distribution.png
    ├── 04_Daily_Deaths_Case_Trend.png
    ├── 05_Year-wise_COVID-19_Cases_in_India.png
    ├── 06_Month-wise_COVID-19_Seasonality_in_India.png
    ├── 07_Month-wise_COVID-19_Deaths_in_India.png
    ├── 08_Month-wise_COVID-19_Cured_in_India.png
    ├── 09_Top_10_States_by_Confirmed_Cases.png
    ├── 10_Top_10_States_by_Cured_Cases.png
    ├── 11_Top_10_States_by_Deaths_Cases.png
    ├── 12_Top_10_States_by_Lowest_Confirmed_Cases.png
    ├── 13_Day-wise_Confirmed_Cases_by_year_&_month.png
    ├── 14_Vaccination_Trend_in_India.png
    ├── 15_Top_10_States_by_Vaccination.png
    ├── 16_Month-wise_Vaccination_Trend.png
    ├── 17_Gender-wise_COVID-19_Vaccination_in_India.png
    ├── 18_Age-Group_wise_COVID-19_Vaccination_in_India.png
    ├── 19_COVID-19_Vaccine_Doses_Distribution_in_India.png
    ├── 20_Doses-wise_COVID-19_Vaccination_in_India.png
    └── 21_Day-wise_Vaccination_by_month.png
```

---

## 🔄 Project Workflow

The project follows a structured data analysis workflow:

### 1. Raw Data Collection

Two datasets containing COVID-19 cases and vaccination information were used as the raw data sources.

### 2. Data Cleaning & Preprocessing

* Handled missing values and duplicate records
* Standardized date formats
* Standardized state and union territory names
* Removed invalid and non-relevant records
* Converted date columns into appropriate datetime formats
* Created additional time-based features:

  * Year
  * Month
  * Month Name
  * Day

### 3. Exploratory Data Analysis

Performed comprehensive analysis to identify:

* COVID-19 case trends
* Recovery and mortality patterns
* State-wise variations
* Seasonal trends
* Vaccination progress
* Gender-wise vaccination distribution
* Age-group-wise vaccination distribution
* Vaccine dose distribution

### 4. Insight Generation

Derived meaningful observations from the visualizations and statistical analysis.

### 5. Final Report

Documented the methodology, visualizations, key insights, recommendations, and conclusions in a comprehensive PDF report.

---

# 📊 Exploratory Data Analysis

## 🦠 COVID-19 Case Distribution in India

![COVID-19 Case Distribution](images/01_COVID-19_Case_Distribution_in_India.png)

This visualization presents the overall distribution of confirmed, cured, and death cases recorded in the dataset.

---

## 📈 Daily COVID-19 Case Trends

![Daily Case Distribution](images/02_Daily_Case_Distribution.png)

![Daily Cured Cases](images/03_Daily_Cured_Case_Distribution.png)

![Daily Deaths Trend](images/04_Daily_Deaths_Case_Trend.png)

These visualizations provide an overview of daily confirmed cases, recoveries, and deaths, helping identify major fluctuations and outbreak periods.

---

## 📆 Time-Based Analysis

![Year-wise COVID-19 Cases](images/05_Year-wise_COVID-19_Cases_in_India.png)

![Month-wise Seasonality](images/06_Month-wise_COVID-19_Seasonality_in_India.png)

The time-based analysis examines yearly case patterns and monthly seasonality to identify periods of increased COVID-19 activity.

---

## 🗺️ State-wise Analysis

![Top 10 States by Confirmed Cases](images/09_Top_10_States_by_Confirmed_Cases.png)

![Top 10 States by Cured Cases](images/10_Top_10_States_by_Cured_Cases.png)

![Top 10 States by Deaths](images/11_Top_10_States_by_Deaths_Cases.png)

The state-wise analysis identifies regions with the highest confirmed cases, recoveries, and deaths, providing insights into geographical variations in the pandemic's impact.

---

## 💉 Vaccination Analysis

![Vaccination Trend in India](images/14_Vaccination_Trend_in_India.png)

![Top 10 States by Vaccination](images/15_Top_10_States_by_Vaccination.png)

![Gender-wise Vaccination](images/17_Gender-wise_COVID-19_Vaccination_in_India.png)

![Age Group-wise Vaccination](images/18_Age-Group_wise_COVID-19_Vaccination_in_India.png)

![Dose-wise Vaccination](images/20_Doses-wise_COVID-19_Vaccination_in_India.png)

The vaccination analysis examines overall vaccination progress, state-wise vaccination levels, gender distribution, age-group coverage, and dose-wise vaccination patterns.

---

## 🔍 Key Insights

* COVID-19 in India exhibited **multiple waves**, with the most severe impact observed during 2021.
* Recovery rates remained high relative to confirmed cases, indicating a strong overall recovery trend.
* Highly populated states accounted for a significant proportion of confirmed cases, recoveries, and deaths.
* COVID-19 cases demonstrated noticeable **monthly and seasonal variations**.
* Vaccination coverage increased significantly following the introduction of the nationwide vaccination program.
* States with larger populations recorded higher overall vaccination numbers.
* Male and female vaccination levels were relatively comparable, while transgender vaccination numbers were considerably lower.
* Age-group analysis reflected differences in vaccination coverage across population groups.
* Vaccine dose analysis demonstrated the progression from primary vaccination to subsequent doses.
* The analysis highlights the importance of continuous monitoring, healthcare preparedness, and data-driven decision-making during large-scale public health events.

---

## 📌 Recommendations

Based on the findings from the analysis, the following recommendations can be considered:

* Implement early-warning systems using continuous monitoring of case trends.
* Strengthen healthcare infrastructure in regions experiencing higher case volumes.
* Use historical seasonal trends to improve outbreak preparedness.
* Improve vaccination outreach among underrepresented demographic groups.
* Use state-wise vaccination data to optimize resource allocation and distribution planning.
* Maintain reliable and standardized public-health data collection systems.
* Use data-driven approaches to support future pandemic preparedness and response planning.

---

## 📄 Final Report

A detailed project report is available in the `Docs/` directory:

📘 **COVID-19 in India – Data Analysis Report.pdf**

The report includes:

* Project Objective
* Executive Summary
* Dataset Description
* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Key Insights
* Recommendations
* Conclusion

---

## ⚙️ How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/Harsh-Belekar/COVID-19-in-India-Data-Analysis
```

### 2. Navigate to the Project Directory

```bash
cd COVID-19-in-India-Data-Analysis
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Notebooks in Order

First run:

```text
notebooks/01_Data_Cleaning.ipynb
```

This notebook performs data cleaning and preprocessing.

Then run:

```text
notebooks/02_Data_Analysis.ipynb
```

This notebook performs exploratory data analysis and generates the visualizations and insights.

---

## 📚 Project Documentation

| Resource                 | Description                                             |
| ------------------------ | ------------------------------------------------------- |
| `Notebooks/01_Data_Cleaning.ipynb` | Data cleaning, preprocessing, and feature engineering   |
| `Notebooks/02_Data_Analysis.ipynb` | Exploratory data analysis, visualizations, and insights |
| `Data/Raw_data/`         | Original datasets used for the project                  |
| `Data/Clean_data/`       | Processed datasets generated after cleaning             |
| `images/`                | Visualizations generated during analysis                |
| `Docs/`                  | Detailed project report                                 |
| `requirements.txt`       | Python dependencies                                     |

---

## 🧑‍💻 Author

**👤 Harsh Belekar**  
📍 Data Analyst | Python Developer | SQL | Power BI | Excel | Data Visualization  
📬 [LinkedIn](https://www.linkedin.com/in/harshbelekar) | 🔗[GitHub](https://github.com/Harsh-Belekar)

📧 [harshbelekar74@gmail.com](mailto:harshbelekar74@gmail.com)

---

⭐ *If you found this project helpful, feel free to star the repo and connect with me for collaboration!*
