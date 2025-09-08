# 🏥 Healthcare Dashboards (Doctor & Patient)

## 📹 Demo
![Dashboard Demo](hospital-patientdashboard.gif.gif)  

---
## 📸 Screenshots

### 🩺 Doctor Dashboard
![Doctor Dashboard](https://github.com/prernabanthiya/Healthcare-Dashboards-Doctor-Patient-/blob/main/screenshots%20%26%20demo/doctor_1.png )

![Doctor Dashboard](https://github.com/prernabanthiya/Healthcare-Dashboards-Doctor-Patient-/blob/main/screenshots%20%26%20demo/doctor_2.png)


### 👩‍⚕️ Patient Dashboard
![Patient Dashboard](https://github.com/prernabanthiya/Healthcare-Dashboards-Doctor-Patient-/blob/main/screenshots%20%26%20demo/patient_!.png)

![Patient Dashboard](https://github.com/prernabanthiya/Healthcare-Dashboards-Doctor-Patient-/blob/main/screenshots%20%26%20demo/patient_2.png)


## 📌 Problem Statement
Healthcare data is often stored in multiple disconnected systems such as patients, doctors, appointments, bills, medicines, rooms, surgeries, and satisfaction scores.  
This makes it challenging for both doctors and patients to access clear and consolidated insights.  

- **Doctors** need a unified view of their appointments, patient spends, commissions, and performance KPIs.  
- **Patients** need a simplified overview of their treatments, medicines, charges, and discharge details.  

The goal of this project was to create **two interactive dashboards in Power BI** that address these needs by integrating and modeling hospital data.

---

## 🛠 Approach
The project followed a structured process:

1. **Data Loading**  
   - Imported **16 hospital-related tables** (patients, doctors, appointments, bills, rooms, surgeries, satisfaction scores, suppliers, medicines, stock, and tests).  

2. **Data Cleaning & Merging**  
   - Merged patient data with related tables (beds, bills, satisfaction scores, surgeries, rooms, and departments).  
   - Removed redundant tables and optimized column usage.  
   - Built a **patient–doctor mapping** using the appointment table.  
   - Combined medical stock with suppliers (`supplier_id`) and patient tests with medical tests (`test_id`).  

3. **Data Modeling**  
   - Established relationships between entities using a star-schema approach where possible.  
   - Standardized KPIs such as patient spend, doctor commission, and medicine sales.  

4. **Dashboard Development**  
   - Designed two dashboards (Doctor and Patient) using **DAX measures, bookmarks, slicers, and KPIs**.  
   - Ensured the dashboards were role-specific, intuitive, and interactive.  

---

## ✨ Features
### 🩺 Doctor Dashboard
- Tracks doctor availability and appointments.  
- Provides KPIs such as Patient Spend, Fees, and Commission Earned.  
- Includes an interactive Commission Calculator with slider.  
- Displays patient status and billing summaries.  

### 👩‍⚕️ Patient Dashboard
- Shows patient demographics and treatment information.  
- Tracks admission and discharge details.  
- Monitors daily and monthly medicine usage.  
- Breaks down charges (room, fees, medicine, discounts, surgery).  
- Displays medicine sales by quantity.  

---

## 📂 Results
- Built a **clean and scalable hospital dataset model** from 16 raw tables.  
- Created **two role-specific dashboards** that provide actionable insights for doctors and patients.  
- Demonstrated advanced Power BI features including bookmarks, KPIs, and interactive slicers.  

---


## 🔗 Contact
- LinkedIn: [Prerna Banthiya](https://www.linkedin.com/in/prerna-banthiya/)  
- Email: **prernabanthiya4@gmail.com**  

---
