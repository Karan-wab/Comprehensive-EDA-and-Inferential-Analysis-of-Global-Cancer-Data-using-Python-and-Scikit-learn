# Comprehensive-EDA-and-Inferential-Analysis-of-Global-Cancer-Data-using-Python-and-Scikit-learn
# Data Jobs Market Analysis Dashboard

## 1. Project Goal
The primary objective of this project is to analyze a large and disorganized dataset of over 700,000 data job postings. The goal is to clean, structure, and visualize this data to uncover key trends in the job market, such as in-demand skills, top job fields, and hiring patterns, ultimately providing actionable insights for a recruitment firm.

---

## 2. Problem Statement
Our client, a recruitment firm, acquired a massive dataset of job postings from various sources. The data was highly disorganized, presenting several critical challenges:
* **Data Inconsistency**: The database was filled with missing values and inconsistent formatting.
* **Unstructured Information**: Critical details like job type were embedded within long, unstructured paragraphs.
* **Fragmented Data**: The dataset consisted of multiple, disconnected tables with no clear relationships, creating data silos.
* **Large Scale**: The sheer size of the data (700,000+ rows) made it challenging to process and optimize for performance in a BI tool.

---

## 3. The Solution
A multi-stage solution was implemented to transform the raw data into a strategic tool:

### A. Data Preparation (Python)
* Initial data cleaning, merging of separate tables (`job_postings`, `job_skills`, `skills_dim`), and preliminary structuring were performed using **Python** with the **Pandas** library.

### B. Data Transformation (Power BI & M Language)
* The structured data was loaded into **Power BI**.
* Advanced cleaning and feature engineering were performed using **Power Query (M language)**. This included creating conditional columns to standardize messy job titles into clean, high-level categories (e.g., "Data Analyst," "Data Scientist," "Cloud Engineer").

### C. Interactive Dashboard (Power BI)
* A comprehensive, interactive dashboard was built to visualize the cleaned data and provide answers to key business questions from the client.

---

## 4. Tech Stack & Tools
* **Data Cleaning & Preparation**: Python, Pandas, Jupyter Notebook
* **Data Transformation & Dashboarding**: Microsoft Power BI, Power Query (M Language)

---

## 5. File Descriptions
* `Data.zip`: Contains the raw, fragmented data files (`job_postings1.csv`, `job_skills1.csv`, `skills_dim2.csv`).
* `Python Coding.ipynb` / `Project 2 (1).ipynb`: Jupyter Notebooks with the Python scripts for the initial data merging and preparation.
* `m language code project 2.docx`: A document containing the Power Query (M language) code used for advanced data transformation within Power BI.
* `PROJECT 2.docx`: The project brief outlining the client's problem statement and the key business questions to be answered.
* `Data Jobs Analysis.pbix`: The final, interactive Power BI dashboard file.

---

## 6. How to Use

### A. Data Preparation
1.  Run the `Python Coding.ipynb` notebook to see the initial data merging and cleaning process.

### B. Viewing the Dashboard
1.  You must have **Microsoft Power BI Desktop** installed.
2.  Open the `Data Jobs Analysis.pbix` file.
3.  The dashboard will load with all the data and visuals, ready for interactive analysis. You can use the slicers and filters to explore trends by year, country, or job title.

---

## 7. Dashboard Features & Insights
The dashboard provides a 360-degree view of the data job market, focusing on:

* **Top In-Demand Skills**: A word cloud and bar charts highlighting the most frequently requested skills in job postings.
* **Top Hiring Companies**: Identification of the companies with the most job openings.
* **Hiring Trends Over Time**: Analysis of the average number of companies hiring each month to gauge market stability.
* **Top Job Fields by Year**: A breakdown of the top 3 most in-demand job sectors for each year.
* **Interactive Slicers**: Filters for Country, Job Title, and Year, allowing for granular, customized analysis.

