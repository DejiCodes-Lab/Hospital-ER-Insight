# 🏥 Hospital ER Operations: Data-Driven Optimization

## 📌 Project Overview
This project presents a comprehensive analysis of Emergency Room operations using a dataset of **9,216 patient records**. By integrating **Excel** for data auditing, and **Power BI** for interactive visualization, I identified critical staffing gaps, a unique "Satisfaction Paradox," and specific departmental bottlenecks.

The goal was to move beyond simple reporting and provide **actionable healthcare solutions** to reduce wait times and improve patient outcomes.

---

## 📊 Interactive Dashboard
*Below is a preview of the interactive dashboard developed in Power BI to track clinical KPIs and patient flow.*
[Dashboard Screenshot](images/Er-dashboard.png)


---

## 🔍 Deep-Dive Insights

### 1. The 11:00 PM Arrival Peak
Contrary to standard office hours, the ER experiences its highest volume of patient arrivals at **23:00 (11:00 PM)**. Additionally, **Mondays** are the highest-pressure days, showing a clear weekly cycle of demand that stresses current staffing models.

### 2. The Satisfaction Paradox
While the average patient satisfaction is low (**4.99/10**), statistical analysis revealed a **near-zero correlation (-0.02)** between wait times and satisfaction scores. 
* **Finding:** Improving speed alone will not fix patient happiness; the issue likely lies in communication quality and the clinical environment during the stay.

### 3. High-Acuity Environment
With an admission rate of **50.04%**, this facility functions as a high-intensity clinical environment rather than a typical walk-in urgent care center, requiring high resource availability per patient.

### 4. Referral Bottlenecks
Nearly **75% of all specialist referrals** are directed to just two departments, creating a massive queue for specific consultants:
* **General Practice:** 48%
* **Orthopedics:** 26%

---

## 💡 Strategic Solutions

| Category | Finding | Proposed Action |
| :--- | :--- | :--- |
| **Staffing** | 11 PM Peak & Monday Surge | Implement a **"Swing Shift" (8 PM – 3 AM)** and increase nursing staff specifically on Mondays. |
| **Experience** | Low Satisfaction (4.99/10) | Deploy **Digital Status Boards** and automated SMS updates to improve transparency regarding "Next Steps." |
| **Flow** | 48% GP Referrals | Create a **GP Fast-Track Lane** to separate minor cases from high-acuity trauma cases. |
| **Clinical** | 26% Ortho Referrals | Station an **Orthopedic Technician** within the ER during peak hours to accelerate treatment for bone injuries. |

---

## 🛠️ Tech Stack & Workflow

1.  **Microsoft Excel:** Performed initial data cleaning, clinical data auditing, and verified data integrity using Pivot Tables.
2.  **Power BI:** Developed the final interactive dashboard utilizing **DAX measures** to calculate real-time KPIs like Admission Rate and Average Wait Time.

---

## 📂 Project Structure
* `Hospital ER.csv`: Raw clinical dataset.
* `ER_Operations_Report.pbix`: Interactive Power BI source file.
* `Dashboard_Preview.png`: Screenshot of the final analytical interface.

---
