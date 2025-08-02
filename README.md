# 🏦 Bank Loan Case Study – Risk Pattern Analysis using Excel By Ashiq Paul

## 📌 Project Overview

This project explores patterns in loan application data to understand why some customers default, especially those with limited credit history. The goal is to help a finance company approve the right applicants and minimize financial losses by using simple yet powerful Excel-based data analysis.

---

## 🧭 Objectives

- Identify customer and loan attributes that correlate with loan default
- Handle missing data and outliers in a structured way
- Perform univariate, segmented, and bivariate analysis
- Understand key indicators for customer risk
- Share insights in a clear report and dashboard

---

## 🛠️ Tech Stack

| Tool              | Purpose                                   |
|-------------------|-------------------------------------------|
| **Microsoft Excel 2025** | Data cleaning, analysis, visualizations        |
| **Word / Canva / PowerPoint** | For documentation and presentations       |

---

## 🔍 Key Steps

1. **Data Cleaning**
   - Used `COUNTBLANK`, `AVERAGEIFS`, `MEDIAN`, and conditional formatting
   - Handled invalid values like `"XNA"` in gender
   - Dropped or imputed missing values based on thresholds

2. **Outlier Detection**
   - Applied IQR method with `QUARTILE.EXC` to flag unrealistic values
   - Highlighted extreme values like 117M income or 1000 years of employment

3. **Class Imbalance Check**
   - Found that ~92% of customers had no default vs 8% who did
   - Important for risk modeling and fair evaluation

4. **Univariate & Segmented Analysis**
   - Explored gender, income, employment length, age, etc.
   - Most applicants were aged 30–39, female, with no children

5. **Bivariate & Correlation Analysis**
   - Used `CORREL` to find top features influencing default
   - Built a heatmap using conditional formatting

---

## 📈 Result

The analysis showed that:
- Short job history, lower income, and loans for consumer goods increase risk
- Certain patterns in education, region, and housing were also linked to default
- The company can reduce risk by adjusting filters and flagging risky profiles

---

## 📁 Files

| File/Folder | Description |
|-------------|-------------|
| [Raw Data](https://drive.google.com/drive/folders/1w32shC4dyunH2An-XcVAHr9NMci7SZOj?usp=sharing) | The raw data used for the case study |
| [Excel File](https://docs.google.com/spreadsheets/d/1nE-GiNwZo47OF-ZM38DWNUjzQS4CtUf6/edit?usp=sharing&ouid=110084775411420359517&rtpof=true&sd=true) (106MB) | The complete EDA workbook in Excel |
| `Bank Loan Case Study - Ashiq Paul.pdf` | PDF report with written insights |
| `Bank Loan Case Study - Ashiq Paul.pptx` | Slide deck used for presentation |
| `README.md` | This project overview file |

---

## 🎥 Video Presentation
> *[Loom Video Presentation](https://www.loom.com/share/1083c3158c22431693d7dbdd0017e3ff?sid=5059acab-b36f-4ab7-9992-14ee82ac7438)*

---

## 📬 Contact

Feel free to reach out if you have questions or suggestions.

**Ashiq Paul**   
LinkedIn: [Ashiq Paul](https://linkedin.com/in/ashiqpaul)

---
