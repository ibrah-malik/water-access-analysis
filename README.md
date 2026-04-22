# water-access-analysis
Global drinking water access analysis using WHO/UNICEF JMP data (2000–2020) | Google Sheets | UN SDG 6
# 💧 Access to Drinking Water — Data Analysis Project

> Investigating global inequalities in water service levels across countries, 
> regions, and income groups using WHO/UNICEF JMP data (2000–2020).

---

## 📋 Project Overview

This project is part of the ExploreAI Academy Integrated Project series, 
aligned with **UN Sustainable Development Goal 6 (Clean Water & Sanitation)**.

Using the WHO/UNICEF Joint Monitoring Programme (JMP) dataset, I analysed 
access to drinking water across 213 countries, uncovering inequalities by 
income group, region, and area type (national, urban, rural).

---

## 🛠️ Tools & Skills Used

| Skill | Details |
|-------|---------|
| **Tool** | Google Sheets |
| **Data Cleaning** | Fixed mixed separators, handled NaN values, corrected erroneous entries |
| **Feature Engineering** | Created 12+ derived columns (ARC, pop_u_val, rounded columns, full-access flags) |
| **Statistical Analysis** | Mean, median, IQR, std dev, percentage difference, ARC formula |
| **Visualisation** | Line charts, 100% stacked columns, box-whisker plots, histograms, pivot tables |
| **Conditional Logic** | IF/AND/IFERROR nested formulas for row-level calculations |

---

## 📊 Key Findings

- 🌍 The dataset covers **99.6% of the world population** (7.79 billion people)
- 🏙️ Urban populations have **12.4% higher** basic water access than rural (92.5% vs 80.1%)
- 📈 **160 of 231 countries** showed a positive Annual Rate of Change in access
- 💰 High-income countries average **97%+ basic access** vs **59%** in low-income countries
- ⚠️ Sub-Saharan Africa, despite the highest improvement rate, is projected to reach 
  universal access only by **~2080** at the current rate

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `Water_Access_Portfolio_Report.pdf` | Full analysis report with charts and insights |
| `Estimates-on-the-use-of-water-2020.csv` | 2020 snapshot dataset (213 countries) |
| `Estimates_of_the_use_of_water_2000-2020.csv` | Full time-series dataset |
| `Regions.csv` | Country-to-region mapping |

---

## 📌 Dataset Source

**WHO/UNICEF Joint Monitoring Programme (JMP)**  
for Water Supply, Sanitation and Hygiene  
[washdata.org](https://washdata.org)

---

## 🎯 Part of

ExploreAI Academy — Data Analytics Programme
