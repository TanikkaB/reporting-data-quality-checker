# 🧪 Reporting Data Quality Checker

A lightweight tool designed to help impact and programme teams assess whether datasets are clean, consistent, and ready for reporting.

This project is part of the **Impact Analytics Suite**, a portfolio of decision-support tools focused on impact, programme, and data strategy workflows.

---

## 🎯 Overview

Before analysis or reporting can begin, data must be reliable. In many real-world scenarios, datasets contain missing values, inconsistencies, and duplicates that can compromise decision-making.

This tool provides a quick and structured way to assess data quality before it is used.

---

## ✨ Key Features

- Dataset overview (rows, columns, data types)  
- Missing data analysis by column  
- Duplicate detection  
- Category consistency checks (e.g. Yes / yes / YES)  
- Basic outlier detection  
- Reporting readiness score  
- Automated data risk summary  

---

## 🧠 Why I Built It

I built this tool to demonstrate the importance of data quality in impact reporting workflows. Reliable analysis depends on reliable data, and this tool highlights common issues early.

---

## 👥 Example Use Case

- Impact teams validating data before reporting  
- Analysts preparing datasets for dashboards  
- Organisations ensuring consistency across data sources  

---

## 🗂 Expected Data Structure

Flexible — works with most tabular datasets. Example columns:

- participant_id  
- programme  
- region  
- completed  
- pre_score  
- post_score  

---

## 🧪 Demo Mode

Includes a synthetic dataset with:

- Missing values  
- Duplicate rows  
- Inconsistent categories  
- Outliers  

Designed to demonstrate real-world data issues.

---

## 📸 Screenshots

_Add screenshots here_

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/YOUR-USERNAME/reporting-data-quality-checker.git
cd reporting-data-quality-checker
pip install -r requirements.txt
streamlit run app.py
