# 🏥 Hospital ER Operations: Data-Driven Optimization

## 📌 Project Overview
This project presents a comprehensive analysis of Emergency Room operations using a dataset of **9,216 patient records**. By integrating **Excel** for data auditing, and **Power BI** for interactive visualization, I identified critical staffing gaps, a unique "Satisfaction Paradox," and specific departmental bottlenecks.

The goal was to move beyond simple reporting and provide **actionable healthcare solutions** to reduce wait times and improve patient outcomes.

---

## 📂 How to Access the Dashboard
1. **Static View:** See the [Dashboard Screenshot](images/Er-dashboard.png) above for a quick preview.
2. **Interactive View:** Download the `Hospital ER Dashboard.pbix` file from the `/reports` folder. 
   *(Requires Power BI Desktop to open)*.


---

## 🔍 Deep-Dive Insights

### 1. The 11:00 PM Arrival Peak
Contrary to standard office hours, the ER experiences its highest volume of patient arrivals at **23:00 (11:00 PM)**. Additionally, **Mondays** are the highest-pressure days, showing a clear weekly cycle of demand that stresses current staffing models.

### 2. High-Acuity Environment
With an admission rate of **50.04%**, this facility functions as a high-intensity clinical environment rather than a typical walk-in urgent care center, requiring high resource availability per patient.

### 3. Referral Bottlenecks
Nearly **75% of all specialist referrals** are directed to just two departments, creating a massive queue for specific consultants:
* **General Practice:** 48%
* **Orthopedics:** 26%

---

## 💡 Strategic Solutions

| Category | Finding | Proposed Action |
| :--- | :--- | :--- |
| **Staffing** | 11 PM Peak & Monday Surge | Implement a **"Swing Shift" (8 PM – 3 AM)** and increase nursing staff specifically on Mondays. |
| **Flow** | 48% GP Referrals | Create a **GP Fast-Track Lane** to separate minor cases from high-acuity trauma cases. |
| **Clinical** | 26% Ortho Referrals | Station an **Orthopedic Technician** within the ER during peak hours to accelerate treatment for bone injuries. |

---

## 🛠️ Tech Stack & Workflow

1.  **Microsoft Excel:** Performed initial data cleaning, clinical data auditing, and verified data integrity using Pivot Tables.
2.  **Power BI:** Developed the final interactive dashboard

---

## 📂 Project Structure
* `Hospital ER.csv`: Raw clinical dataset.
* `ER_Operations_Report.pbix`: Interactive Power BI source file.
* `Dashboard_Preview.png`: Screenshot of the final analytical interface.

---
