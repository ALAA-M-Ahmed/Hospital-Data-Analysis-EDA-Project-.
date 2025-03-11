# 🏥 Hospital Data Analysis

## 📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of a hospital dataset. The goal is to uncover actionable insights related to patient admissions, disease patterns, hospital performance, doctor efficiency, insurance billing, and average length of stay. The findings aim to support hospital management in optimizing operations, resource planning, and strategic decisions.

---

## 🔍 Objectives

- Detect seasonal patterns in disease admissions.
- Identify the most and least efficient hospital branches.
- Analyze the average length of patient stay based on diagnosis.
- Determine which doctors are handling critical or long-duration cases.
- Compare insurance providers in terms of billing amounts.

---

## 🧪 Methodology

### 1. **Data Cleaning**
- Removed missing values and duplicates.
- Converted date columns to datetime format.
- Fixed data type inconsistencies and standardized categorical fields.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized disease trends over time.
- Grouped hospital branches by number and types of admissions.
- Calculated average length of stay per diagnosis and hospital.
- Analyzed doctors based on frequency of long-stay and critical patients.
- Explored differences in total charges by insurance provider.

---

## 📊 Tools & Libraries Used

- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 📁 Dataset Summary

- **Rows**: 10,000+
- **Columns**: 15
- Contains information on patients, diseases, doctors, hospitals, insurance providers, dates, billing amounts, and stay durations.

---

## 💡 Key Insights (Business-Driven)

1. **Seasonal Patterns**:  
   - Some diseases (e.g., respiratory infections) showed spikes in winter months.
   - This can help in seasonal staffing and resource allocation.

2. **Hospital Performance**:  
   - Branch X consistently handled the highest number of cases, especially emergency cases.
   - Branch Y had low admissions, suggesting potential underutilization.

3. **Length of Stay Analysis**:  
   - Patients diagnosed with Disease A stayed an average of 6 days, higher than the dataset average.
   - Disease B had the shortest average stay (1–2 days), likely outpatient cases.

4. **Doctor Efficiency**:  
   - Dr. Ahmed and Dr. Rana handled the most critical cases (stays > 7 days).
   - Dr. Sara specialized in short-stay, high-volume cases.

5. **Insurance Billing Differences**:  
   - Insurance Provider A had the highest average billing amount per case.
   - Provider C had more frequent small-value claims, indicating coverage of basic cases.

---

## ✅ Conclusion

The analysis uncovered meaningful patterns that can guide hospital administrators in:
- Planning for seasonal demand.
- Improving doctor allocation based on case complexity.
- Negotiating with insurance providers.
- Evaluating branch-level performance.

These insights lay the foundation for future steps such as predictive modeling and operational optimization.
