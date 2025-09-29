# OCD-Patient-analysis-health-care
This repository analyzes a clinical dataset for 1,500 OCD patients (Obsessive-Compulsive Disorder). It features demographic and clinical data, including Age, Obsession/Compulsion Types, Y-BOCS severity scores, and comorbid diagnoses like Depression/Anxiety. The project aims to understand patient profiles and disease characteristics.
This summary will describe your project, focusing on the tools and methodology used to analyze the OCD Patient Dataset.

***

### 🛠️ Project Summary: Methodology & Tools

| Aspect | Description |
|:---|:---|
| **Tools Used** | **Python**, **pandas** (Data manipulation), **matplotlib/seaborn** (Visualization), and potentially **scikit-learn** or **statistical libraries** (for model/hypothesis testing). |
| **Dataset** | `OCD Patient Dataset_ Demographics & Clinical Data.csv` (1,500 patient records). |
| **Objective** | Analyze patient profiles, assess disease severity, and explore correlations between clinical factors, demographics, and outcomes (e.g., Y-BOCS scores). |

---

### 🔍 Methodology (How it was done)

#### 1. Data Cleaning & Preparation
* **Loading:** The CSV dataset was loaded into a pandas DataFrame.
* **Initial Inspection:** Columns were inspected to check data types, look for missing values (nulls), and understand the scale of numerical scores.
* **Type Conversion:** The `OCD Diagnosis Date` column was converted to a proper datetime format to allow for time-series analysis (e.g., duration from diagnosis to present).

#### 2. Exploratory Data Analysis (EDA)
* **Distribution Analysis:** Used visualizations (bar charts, histograms) to show the distribution of key categorical features (e.g., **Gender**, **Ethnicity**, **Medications**) and numerical data (**Age**, **Duration of Symptoms**).
* **Severity Analysis:** Analyzed the distribution and correlation of **Y-BOCS Scores** (Obsessions and Compulsions) across different patient groups.
* **Categorical Comparisons:** Created grouped bar plots or box plots to compare Y-BOCS scores based on **Obsession Type**, **Compulsion Type**, and **Comorbid Diagnoses** (Depression/Anxiety) to see which factors are associated with higher severity.

#### 3. Correlation & Insights
* **Correlation Matrix:** Calculated and visualized correlations between numerical variables (Age, Duration, Y-BOCS scores) to identify key linear relationships.
* **Hypothesis Testing (Potential Step):** Statistical tests could be performed to determine if the difference in Y-BOCS scores between groups (e.g., those with vs. without Family History of OCD) is statistically significant.

This approach ensures a thorough understanding of the clinical data, allowing for conclusions on patient characteristics and severity factors related to OCD.

<img width="1159" height="682" alt="Screenshot 2025-09-29 232215" src="https://github.com/user-attachments/assets/9cb6f473-d596-442d-a8c7-d6276f83ffde" />

<img width="1171" height="704" alt="Screenshot 2025-09-29 232227" src="https://github.com/user-attachments/assets/e29bb2e7-9beb-4bb6-ac56-d53b180588e5" />

