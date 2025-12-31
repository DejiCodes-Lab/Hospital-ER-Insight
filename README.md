# 🏥 Hospital ER Operations: Data Analysis & Optimization

## 📌 Project Overview
This project performs an end-to-end data analysis of a Hospital Emergency Room dataset containing **9,216 patient records**. The objective was to identify operational bottlenecks, analyze patient demographics, and understand the factors influencing patient satisfaction and hospital admissions.

---

## 📊 Executive Dashboard
The analysis resulted in a comprehensive dashboard (see `er_dashboard.png`) covering:
- **Patient Volume:** Hourly and weekly arrival patterns.
- **Wait Times:** Distribution across genders and age groups.
- **Satisfaction Analysis:** Correlation between wait times and patient scores.
- **Departmental Flow:** Top referral specialties like General Practice and Orthopedics.

---

## 🔍 Key Insights
After performing Exploratory Data Analysis (EDA), the following findings were uncovered:

1. **The Late-Night Surge:** - While many clinics staff for daytime hours, this ER sees its peak arrival volume at **23:00 (11:00 PM)**.
   - **Monday** is consistently the busiest day of the week.

2. **The Satisfaction Paradox:**
   - The average satisfaction score is **4.99/10**. 

3. **High Acuity Environment:**
   - **50.04%** of all ER visits result in a full hospital admission, indicating a patient population with high-severity needs.

4. **Bottleneck Departments:**
   - **General Practice** and **Orthopedics** account for the majority of specialist referrals, identifying where resource integration is most needed.

---

## 💡 Strategic Solutions

### 1. Operations: "The Swing Shift"
Implement a specialized staffing shift from **8:00 PM to 3:00 AM**. Matching clinical capacity to the 11 PM peak will reduce the physical strain on late-night staff and potentially reduce errors.

### 2. Experience: "Communication over Speed"
Since wait time is not the primary driver of the low 4.99 satisfaction score, focus on **Patient Communication**. Implementing digital status boards or automated SMS updates regarding "Next Steps" can improve the perceived quality of care.

### 3. Flow: "GP Fast-Track"
Create a dedicated "Fast-Track" intake for General Practice referrals. By separating minor GP-related issues from high-acuity trauma cases (the 50% being admitted), the ER can clear the waiting room faster.

---

## 🛠️ Tech Stack & Tools
- **Excel:** Used for initial data cleaning, clinical data auditing, and pivot table exploration.
- **Power BI:** Used to create an interactive dashboard for hospital administrators to filter data by date, gender, and department.

---

## 📂 Project Structure
- `Hospital ER.csv`: The raw dataset.
- `er_dashboard.png`: The final visual report exported from the analysis.
- `README.md`: Project documentation.
