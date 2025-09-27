# 📊 Suicides in India (2001–2012) – Excel Dashboard

## 📌 Project Overview

This project analyzes suicide trends in India between **2001–2012** using an official dataset. The goal was to explore demographic and cause-based patterns, identify key risk factors, and create an **interactive Excel dashboard** for insights.

The analysis involved **data cleaning, transformation, aggregation, and visualization**, with KPIs designed to answer critical questions about gender, age, states, causes, and trends over time.

---

## 🛠️ Data Cleaning & Transformation

* **Removed noisy/incorrect records** (e.g., age group `0-100+`, \~5% of dataset).
* **Fixed inconsistent categories** by merging duplicates:

  * *Bankruptcy or Sudden change in Economic* → *Bankruptcy / Economic Status*
  * *Unemployed* & *Unemployment* → *Unemployment*
  * *Not having Children (Barrenness/Impotency)* → *Not having Children*
* **Integrated “Other causes”** categories (e.g., “Other causes (please specify)” & “By other means (please specify)”) into a single group for data integrity (\~18% of dataset).
* **Removed duplicates** where found.
* **Created derived fields**:

  * CAGR (Compound Annual Growth Rate).
  * Gender ratio (Male vs. Female).
  * Region classification (North, South, East, West, Central, UTs).
* **Handled formatting**: Kept `Year` as general format instead of `date` to avoid 1/1/yyyy issues.

---

## 📊 Dashboard Features

The Excel dashboard contains the following elements:

* **Slicers / Filters**:

  * Year (Timeline)
  * Gender
  * Age Group
  * Region
  * Cause of Suicide

* **Key Metrics & Charts**:

  * Total suicides by year (trend analysis).
  * Gender-wise suicide ratio.
  * Age group distribution.
  * Regional comparisons.
  * Top 5 causes of suicide.
  * CAGR over the study period.

---

## 📸 Dashboard Preview

<img width="1867" height="699" alt="image" src="https://github.com/user-attachments/assets/408c6096-6032-4652-8024-0098b9ab2a8c" />



---
## ❓ Questions & Answers

* **Which year had the highest number of suicides?**
  → 2011 recorded the highest suicides within 2001–2011.

* **What is the Compound Annual Growth Rate (CAGR) of suicides over the years?**
  → The CAGR was **1.22%**, indicating a slow but steady increase.

* **Who is more affected by suicides, men or women?**
  → **Men (64%)** are more prone compared to **women (36%)**.

* **Which age groups are most vulnerable?**
  → **15–29 years** and **30–44 years** are the highest risk groups.

  * Among women: **15–29 years** (45% of female suicides).
  * Among men: **30–44 years** (36% of male suicides).

* **Which region has the highest and lowest suicides?**
  → **South India** (40.21%) has the highest share, while **Union Territories** have the lowest (3.43%).

* **What are the leading causes of suicide?**
  →

  1. **Unspecified / Others (44%)**
  2. **Hanging (19%)**
  3. **Family Problems (14%)**

---

## 🔍 Insights

### 📅 Yearly Trends

* 2011 had the highest number of suicides.
* CAGR of suicides = **1.22%** (2001–2011).

### 👥 Gender Distribution

* **Men (64%)** vs **Women (36%)**.
* Gender ratio varies by region:

  * Highest male ratio → **North-East**
  * Highest female ratio → **East**

### 👶 Age Group Analysis

* **15–29** and **30–44** age groups most vulnerable.
* Women: **15–29** years (45% of female suicides).
* Men: **30–44** years (36% of male suicides).

### 🌍 Regional Distribution

* **South India** → 40.21% of total suicides.
* **Union Territories** → 3.43% (lowest).
* In **Pondicherry (UT)**, suicides are disproportionately high (64% within UTs).

### ⚠️ Causes of Suicide

* Top national causes:

  1. Unspecified/Others (44%)
  2. Hanging (19%)
  3. Family Problems (14%)
* In **Union Territories**, *Hanging* is the dominant cause.

---

## 📝 Conclusion

The analysis of suicides in India (2001–2011) highlights critical demographic and regional disparities. Suicides have shown a slow but steady increase, peaking in 2011. Men are disproportionately more affected, particularly in the **30–44 age group**, while women are most vulnerable in the **15–29 age group**. The **South region** contributes the highest share, whereas the **Union Territories** contribute the least.

The leading causes—**unspecified/others, hanging, and family problems**—reflect both gaps in data classification and real socio-economic pressures. These findings stress the urgent need for **targeted mental health policies, awareness programs, and preventive interventions** focused on vulnerable age groups and high-risk regions.

## 🙌 Acknowledgments

* Dataset: *Suicides in India (2001–2012)* (Government of India data).
* Tools: Microsoft Excel (Pivot Tables, Slicers, Charts).

