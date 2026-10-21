<div align="center">

# 🏥 Healthcare Data Cleaning & Analysis

### A Power BI Data Analytics Project

*Turning raw healthcare data into meaningful insights.*

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Cleaning](https://img.shields.io/badge/Focus-Data%20Cleaning-2E8B57?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Portfolio%20Project-5B6CFF?style=for-the-badge)

</div>

---

## 📌 About the Project

This project explores a healthcare dataset using **Microsoft Power BI**, with a focus on preparing data for analysis and making healthcare information easier to understand.

The workflow uses a CSV dataset as the source and a Power BI report (`.pbix`) for data preparation, modeling, and visualization. The project is designed to demonstrate practical data analytics skills, especially data inspection, cleaning workflow, and reporting.

## 🎯 Project Objectives

- Inspect the healthcare dataset and understand its structure.
- Prepare columns and data types for analysis.
- Check data quality, including missing values, duplicates, and inconsistent values.
- Explore patient, admission, billing, medication, and test-result information.
- Present useful findings through Power BI visuals.

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Power BI** | Data modeling and report visuals |
| **Power Query** | Data inspection and transformation |
| **CSV** | Source dataset |

## 📂 Project Files

```text
Healthcare-Data-Analysis/
├── hcpbi(2).pbix
├── healthcare_dataset - healthcare_dataset(2).csv
└── README.md
```

- `hcpbi(2).pbix` — Power BI report file.
- `healthcare_dataset - healthcare_dataset(2).csv` — healthcare source dataset.

- <img width="962" height="551" alt="Screenshot 2026-10-19 185107" src="https://github.com/user-attachments/assets/ddef3d5f-7e03-43b4-94e0-c853bd10bb2f" />


## 📊 Dataset Overview

The dataset contains **55,500 records and 15 columns**.

| Column | Description |
|---|---|
| `Name` | Patient name |
| `Age` | Patient age |
| `Gender` | Patient gender |
| `Blood Type` | Blood type |
| `Medical Condition` | Recorded medical condition |
| `Date of Admission` | Patient admission date |
| `Doctor` | Doctor associated with the record |
| `Hospital` | Hospital name |
| `Insurance Provider` | Insurance provider |
| `Billing Amount` | Recorded billing amount |
| `Room Number` | Room number |
| `Admission Type` | Admission category |
| `Discharge Date` | Patient discharge date |
| `Medication` | Medication recorded |
| `Test Results` | Recorded test-result category |

## 🧹 Data Cleaning & Preparation

Data preparation is an important part of this project. The cleaning workflow can include:

- Reviewing column names and data types.
- Converting admission and discharge columns to date types.
- Checking missing or null values.
- Checking for duplicate records.
- Standardizing text values where necessary.
- Verifying numeric columns such as age and billing amount.
- Preparing the data for analysis in Power BI.

> **Data-quality note:** The supplied CSV has no blank/null values in its 15 columns. This alone does not confirm that there are no duplicates or other quality issues. List a transformation as completed only if it is present in your Power BI workflow.

## 🔎 Analysis Areas

The dataset can be explored to understand:

- Patient distribution by age and gender.
- Records across medical conditions.
- Admission types and hospital patterns.
- Billing amounts by hospital, condition, or insurance provider.
- Medication and test-result distributions.
- Admission and discharge dates.

*The exact KPIs and visuals depend on the report pages included in the `.pbix` file.*

## 🚀 How to Open the Project

1. Download the Power BI file and CSV dataset.
2. Keep both files in the same folder.
3. Open `hcpbi(2).pbix` in **Power BI Desktop**.
4. If prompted, update the source path to the supplied CSV file.
5. Refresh the data and explore the report pages.

## 💡 Skills Demonstrated

- Data inspection and preparation
- Power Query workflow
- Data type validation
- Healthcare dataset exploration
- Power BI reporting and visualization
- Communicating data through a dashboard

