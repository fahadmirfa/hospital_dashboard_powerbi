# 🏥 Hospital Dashboard – Power BI

![Hospital Dashboard Preview](https://github.com/fahadmirfa/hospital_dashboard_powerbi/blob/main/hospital_dashboard_powerbi.png)

---

## 📘 Overview
The **Hospital Dashboard** is an interactive **Power BI** solution designed to monitor and analyze hospital performance metrics.  
It enables administrators, doctors, and analysts to make data-driven decisions by providing insights into **patient volume**, **wait times**, **satisfaction levels**, and **department efficiency** — all within a visually rich and user-friendly interface.

---

## 🎯 Key Metrics & KPIs

| Metric | Description |
|:--------|:------------|
| **🧍 Total Patients** | Displays the total number of patients served in the selected time frame |
| **⏱ Average Wait Time** | Shows the average waiting time before consultation or admission |
| **😊 Average Satisfied Patients** | Percentage of patients expressing satisfaction based on feedback data |
| **🏢 Total Departments** | Total number of active hospital departments |
| **👨‍⚕️ Total Case Managers** | Count of all active case managers handling patient cases |
| **📊 Total Patients by Department** | Distribution of patients across all hospital departments |
| **⚧ Total Patients by Gender** | Gender-wise segmentation of total patients |
| **📅 Total Patients (Month-Wise)** | Monthly trend analysis of total patient inflow |
| **🩺 Patient Satisfaction (Department-Wise)** | Department-specific satisfaction comparison |
| **📋 Patient Details Table** | A detailed table containing patient demographics and treatment data |

---

## 📊 Visuals Used

| Visualization | Purpose |
|:---------------|:--------|
| **Card Visuals** | Display KPIs such as total patients, wait time, satisfaction, and case managers |
| **Slicer Bar** | Filter data dynamically by department, month, gender, or case manager |
| **Stacked Bar Chart** | Compare total patients by department and gender |
| **Stacked Column Chart** | Analyze patient trends month-wise |
| **Donut Chart** | Visualize patient satisfaction and gender distribution |
| **Table** | Present a detailed patient-level dataset with all key fields |

---

## 🧩 Data Model & Architecture

- **Data Sources:** Patient management system, department records, case manager database, and satisfaction surveys  
- **Data Preparation:**  
  - Cleaned and transformed using **Power Query**  
  - Calculated metrics created via **DAX** formulas (e.g., Avg. Wait Time, Satisfaction %)  
- **Model Structure:**  
  - **Fact Tables:** Patients, Appointments, Satisfaction  
  - **Dimension Tables:** Department, Gender, Date, Case Manager  

---

## ⚙️ How to Use

1. **Open the Report**  
   - Download the `.pbix` file and open it in **Power BI Desktop**

2. **Connect Data Sources**  
   - Link your hospital data or use the sample dataset provided

3. **Refresh the Dashboard**  
   - Click **Refresh** to load the most recent data

4. **Interact with Visuals**  
   - Use slicers to filter results by department, gender, or time period  
   - Hover over charts for detailed tooltips  
   - Drill down into departments or months for deeper insights

5. **Publish (Optional)**  
   - Publish to **Power BI Service** for sharing and scheduling data refreshes

---

## 💡 Insights Delivered

- Identify departments with **highest patient volume**  
- Monitor **average wait times** and reduce patient delays  
- Track **satisfaction levels** by department  
- Understand **gender and monthly trends** for strategic staffing  
- Evaluate **case manager performance** and workload balance  

---

## 📂 Project Structure

hospital_dashboard_powerbi/
├── hospital_dashboard_powerbi.pbix # Power BI dashboard file
├── hospital_dashboard_powerbi.png # Dashboard preview image
├── README.md # Project documentation
└── data/ # (Optional) Sample data files


---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data visualization & reporting  
- **Power Query** – Data extraction, transformation, and cleaning  
- **DAX** – Custom measures and calculated columns  
- **Excel / CSV** – Source data formats  

---

## 🖼️ Dashboard Preview

![Dashboard Preview](https://github.com/fahadmirfa/hospital_dashboard_powerbi/blob/main/hospital_dashboard_powerbi.png)

---

## 🚀 Future Enhancements

- Add predictive analytics for patient admission forecasting  
- Integrate real-time data using API connectors  
- Implement role-based row-level security (RLS)  
- Include hospital resource utilization metrics (beds, equipment, staff shifts)  

---

## 📄 License
This project is licensed under the **MIT License** — you may use, modify, and distribute it with attribution.

---

## 👨‍💻 Author

**Fahad Mirfa**  
📧 [GitHub Profile](https://github.com/fahadmirfa)

---

⭐ *If you find this project helpful, please consider giving it a star to support future improvements!*
