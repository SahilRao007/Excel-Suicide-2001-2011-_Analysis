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

## 🔑 Key Insights

* Gender disparities are visible, with \[fill after observations].
* Certain age groups (e.g., \[fill]) show higher vulnerability.
* Economic distress and family-related issues are recurring causes.
* “Other causes” remain a significant portion (\~16–18%), suggesting underreporting / classification gaps.


## 📸 Dashboard Preview

*<img width="1867" height="699" alt="image" src="https://github.com/user-attachments/assets/408c6096-6032-4652-8024-0098b9ab2a8c" />
*


---


---

## 🙌 Acknowledgments

* Dataset: *Suicides in India (2001–2012)* (Government of India data).
* Tools: Microsoft Excel (Pivot Tables, Slicers, Charts).

