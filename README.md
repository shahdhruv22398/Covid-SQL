# COVID-19 Data Analysis Project

## **Overview**

This project focuses on analyzing **global COVID-19 data** using **SQL**
and Excel datasets. It combines pandemic-related statistics such as
**cases, deaths, testing, and vaccinations** to derive meaningful
insights, trends, and patterns about the spread and control of COVID-19
worldwide.

------------------------------------------------------------------------

## **Datasets**

### **1. CovidDeaths.xlsx**

Contains country-level and continent-level COVID-19 statistics.

**Key Columns:** - `iso_code`, `continent`, `location`, `date` -
`population`, `total_cases`, `new_cases` - `total_deaths`,
`new_deaths` - `icu_patients`, `hospitalizations`,
`weekly_icu_admissions`

**Insights Derived:** - Daily and cumulative case trends - Death rates
and recovery patterns - Hospitalization and ICU capacity

------------------------------------------------------------------------

### **2. CovidVaccinations.xlsx**

Provides vaccination and testing-related data across countries.

**Key Columns:** - `total_tests`, `new_tests` - `total_vaccinations`,
`people_vaccinated`, `people_fully_vaccinated` -
`hospital_beds_per_thousand`, `gdp_per_capita`, `life_expectancy`

**Insights Derived:** - Testing and vaccination rollout progress -
Correlation between vaccination rates and case reductions -
Socioeconomic factors affecting vaccination rates

------------------------------------------------------------------------

### **3. Covid Project.sql**

SQL script used to query, clean, and analyze the datasets.

**Includes:** - Data extraction and transformation - Joins between
deaths and vaccination data - Calculation of **mortality rates**,
**vaccination percentages**, and **population coverage** - Aggregations
and trend analysis using **window functions** and **CTEs**

------------------------------------------------------------------------

## **Key Objectives**

-   Analyze the **global impact** of COVID-19 by location and date.
-   Calculate **mortality rates**, **vaccination rates**, and **test
    positivity rates**.
-   Compare **vaccination progress** with infection and fatality trends.
-   Provide data-driven insights using **SQL analytics**.

------------------------------------------------------------------------

## **How to Use**

### **1. Prerequisites**

-   [Python 3.8+](https://www.python.org/)
-   [Pandas](https://pandas.pydata.org/)
-   \[SQL Server / MySQL / PostgreSQL\] (depending on the database used)
-   Excel file reader (`openpyxl` or similar)

``` bash
pip install pandas openpyxl
```

### **2. Steps to Run**

1.  Clone this repository:
    `bash     git clone https://github.com/<your-username>/<repo-name>.git`
2.  Open the `Covid Project.sql` file in your SQL environment.
3.  Import `CovidDeaths.xlsx` and `CovidVaccinations.xlsx` into your
    database or analytics tool.
4.  Run the queries step by step to generate insights.

------------------------------------------------------------------------

## **Project Structure**

``` bash
├── Covid Project.sql             # SQL script for analysis
├── CovidDeaths.xlsx             # Dataset containing COVID deaths & cases
├── CovidVaccinations.xlsx       # Dataset containing vaccination & testing info
└── README.md                    # Project documentation
```

------------------------------------------------------------------------

## **Insights & Visualizations**

-   Daily and cumulative COVID-19 cases by country
-   Vaccination rates vs mortality rates
-   Top 10 vaccinated countries
-   Testing trends and healthcare capacity analysis

------------------------------------------------------------------------

## **Future Enhancements**

-   Create an interactive **dashboard** using Tableau or Power BI.
-   Automate dataset updates using Python ETL scripts.
-   Deploy findings via a **Streamlit web app**.

------------------------------------------------------------------------

## **Author**

**Dhruv Shah**\
📧 Email: \[your-email@example.com\]\
🔗 LinkedIn: \[Your LinkedIn Profile\]\
💻 GitHub: \[Your GitHub Profile\]

------------------------------------------------------------------------

## **License**

This project is licensed under the MIT License.
