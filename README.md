# 🗃️ MySQL Layoffs Data Cleaning & Exploratory Analysis

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![SQL](https://img.shields.io/badge/SQL-Queries-blue?style=for-the-badge)](https://github.com/)
[![Cleaning](https://img.shields.io/badge/Data_Cleaning-Complete-green?style=for-the-badge)](https://github.com/)
[![EDA](https://img.shields.io/badge/EDA-Insights_Generated-orange?style=for-the-badge)](https://github.com/)

This is an end-to-end data project performed entirely in **MySQL**. It covers the full workflow from cleaning a raw, messy layoffs dataset to performing a comprehensive exploratory data analysis (EDA) to uncover significant trends and insights.


## 📋 Table of Contents
* [About The Project](#-about-the-project)
* [Tech Stack](#-tech-stack)
* [Project Workflow](#-project-workflow)
* [Part 1: Data Cleaning](#-part-1-data-cleaning)
* [Part 2: Exploratory Data Analysis (EDA)](#-part-2-exploratory-data-analysis-eda)
* [Key Findings & Insights](#-key-findings--insights)
* [How to Reproduce](#-how-to-reproduce)
* [Conclusion & Learnings](#-conclusion--learnings)
* [Connect with Me](#-connect-with-me)

---

## <a name="-about-the-project"></a> 📝 About The Project

This project handles a real-world layoffs dataset (`layoffs.csv`) and takes it through two critical phases using SQL:

1.  **Data Cleaning:** The initial raw data is meticulously cleaned and preprocessed to create a reliable and accurate dataset (`layoffs_cleaned.csv`).
2.  **Exploratory Data Analysis:** The cleaned dataset is then analyzed to identify patterns, trends, and key insights related to layoffs across various dimensions like industry, geography, and time.

---

## <a name="-tech-stack"></a> 🛠️ Tech Stack

-   **MySQL Workbench:** The integrated development environment for executing SQL queries.
-   **SQL:** The core language used for all data manipulation, cleaning, and analysis tasks.

---

## <a name="-project-workflow"></a> ⚙️ Project Workflow

The project was executed in two distinct phases:

### Phase 1: Data Cleaning
-   **Objective:** To transform the raw, inconsistent `layoffs.csv` file into a structured, clean dataset ready for analysis.
-   **Process:** A series of SQL queries were run to handle duplicates, nulls, and inconsistencies.
-   **Outcome:** A new, clean table/CSV named `layoffs_cleaned`.

### Phase 2: Exploratory Data Analysis (EDA)
-   **Objective:** To query the `layoffs_cleaned` data to uncover trends and answer key business questions.
-   **Process:** SQL queries were used to aggregate, group, and analyze the data across different dimensions.
-   **Outcome:** A set of actionable insights about the global layoff landscape between 2020 and 2023.

---

## <a name="-part-1-data-cleaning"></a> 🧹 Part 1: Data Cleaning

### Steps Performed:
-   ✅ **Remove Duplicates:** Identified and deleted duplicate rows based on key columns to ensure data integrity.
-   ✅ **Standardize Data:** Trimmed whitespace and standardized categorical data (e.g., industry names) for consistency.
-   ✅ **Handle Null/Blank Values:** Addressed `NULL` or empty values in critical columns, populating them where possible or flagging them for analysis.
-   ✅ **Remove Unnecessary Columns/Rows:** Dropped columns and rows that were not relevant to the analysis to streamline the dataset.

---

## <a name="-part-2-exploratory-data-analysis-eda"></a> 🔎 Part 2: Exploratory Data Analysis (EDA)

### Key Questions Addressed:
-   Which industries and companies were most affected by layoffs?
-   What were the time-based patterns (yearly, monthly) of layoffs?
-   What was the geographical impact of these layoffs?
-   How did the funding stage of a company correlate with the number of layoffs?

---

## <a name="-key-findings--insights"></a> 💡 Key Findings & Insights

-   **Time Frame:** The analysis covers layoffs from **March 2020 to March 2023**.
-   **Industry Impact:** **Consumer** and **Retail** industries were hit the hardest, with over **44,782** and **43,613** layoffs respectively.
-   **Geographical Hotspots:** The **United States** saw the highest number of layoffs (**256,559**), followed by India and the Netherlands.
-   **Yearly Trends:** **2022** was the year with the most recorded layoffs (**160,661**), though early 2023 showed an alarming spike.
-   **Monthly Patterns:** A massive surge in layoffs occurred in early 2023, with **January 2023** alone accounting for over **84,000** job cuts.
-   **Funding Stage Insights:** **Post-IPO** companies had the highest number of layoffs (**204,132**), indicating major workforce reductions after going public.
-   **Top Companies:** Tech giants **Google (12,000)**, **Meta**, and **Amazon** led the charts for the largest single layoff events.

---

## <a name="-how-to-reproduce"></a> 🚀 How to Reproduce

The SQL scripts for both phases of the project are available. To reproduce the results:

1.  Load the raw `layoffs.csv` into a MySQL database.
2.  Run the queries from the **Data Cleaning** script to create the clean dataset.
3.  Run the queries from the **Data Analysis** script on the cleaned dataset to derive the insights.

-   **[SQL Queries for Data Cleaning](https://github.com/meet-afk/MySQL-Layoffs-Data-Cleaning-Exploratory-Analysis/blob/main/Data_cleaning-Queries.pdf)**
-   **[SQL Queries for Data Analysis](https://github.com/meet-afk/MySQL-Layoffs-Data-Cleaning-Exploratory-Analysis/blob/main/EDA-Queries.pdf)**

---

## <a name="-conclusion--learnings"></a> 🎓 Conclusion & Learnings

This project was an excellent practical exercise in using **SQL for real-world data analysis**. By systematically cleaning and then exploring the dataset, I was able to extract meaningful insights about layoff trends. The process reinforced my SQL skills and highlighted the importance of a clean data foundation for any analysis. Future work could involve visualizing these SQL-driven insights in a BI tool to create a more compelling narrative.

---

## <a name="-connect-with-me"></a> 📬 Connect with Me

Have feedback or suggestions? I'd love to hear from you!

-   **My Portfolio:** [My Portfolio](https://meet-afk.github.io/)

Check out my other projects! ➜ **[My GitHub Profile](https://github.com/meet-afk)**
