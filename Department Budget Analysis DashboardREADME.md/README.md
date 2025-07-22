# 🏢 Department Budget Analysis Dashboard – Power BI + SQL

An interactive and visually compelling **Power BI dashboard** designed to monitor **departmental performance**, **project allocation**, and **capital utilization** across core business units: Engineering, Marketing, Sales, HR, and IT. This project integrates multiple datasets using **SQL and DAX**, offering a unified view of employee metrics, project budgets, and financial KPIs for strategic decision-making.

---

## 📌 Key Metrics

| Metric                  | Value      |
|--------------------------|------------|
| **Total Capital**        | $2.43M     |
| **Total Project Budget** | $365K      |
| **Total 2-Year Budget**  | $796K      |
| **Departments Tracked**  | 5          |
| **Projects Analyzed**    | 10         |
| **Employees Tracked**    | 10         |

---

## 🔍 Dashboard Features

### 1. 💡 Capital & Budget KPIs
- **Capital KPI Card**:  
  Custom DAX Formula:  
Capital = 0.5 * Budget - 2 * Salary Cost + Project Cost

yaml
Copy
Edit
Displays **$2.43M** total capital

- **Project Budget KPI Card**:  
Shows **$365K** current project budget

- **2-Year Budget KPI**:  
Calculated as `0.5 * Budget`, totaling **$796K**

---

### 2. 🍩 Donut Charts – Project Distribution
- **Capital by Department**  
- **Project Budget by Department**  
- Color-coded segments aligned with the dashboard theme for easy comparison

---

### 3. 📋 Departmental Summary Table
Aggregated department-wise metrics using `GROUP BY`:
- Project Cost  
- Salary Cost  
- 2-Year Budget  
- Computed Capital  

Includes **interactive filters** (slicers) for:
- Department  
- Project Status

---

### 4. 👤 Employee Profile Section
Personalized detail card showing selected employee’s:
- Headshot  
- Name & Title  
- Department  
- Salary  

Useful for **HR review and individual performance analysis**

---

### 5. 📊 Budget Bar Charts
- **Project Budget by Project**: Horizontal bar chart  
- **Budget by Department**: Stylized with **gold color theme** to highlight comparisons

---

## 🧠 Business Use Cases

- Analyze **financial health** by department  
- Compare **project allocations** and budgets  
- Track **employee assignments and payroll impact**  
- Support **capital planning** and resource optimization  

---

## 🛠️ Tools & Skills Used

- **Tools**: Power BI, SQL  
- **Skills**:
- DAX Calculations & KPIs  
- SQL (CTE, JOINs, UNIONs)  
- Group By Aggregation  
- Data Modeling  
- Performance Monitoring  
- Budget & Capital Analysis  
- Dashboard Design  

---

## 🖼️ Dashboard Preview

<img width="1339" height="765" alt="Image" src="https://github.com/user-attachments/assets/47c09a51-2792-462b-8f53-eb76088395f0" />
