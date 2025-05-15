# 🏋️ HinergoGym – Business Case & Demo Dataset

![Visitors](https://visitor-badge.glitch.me/badge?page_id=DavidIT2022.HinergoGym)
![License](https://img.shields.io/badge/license-Custom-blue)

**A complete fictional dataset and business case for data modeling, DAX training, and Power BI storytelling.**

---

## 📘 Description

HinergoGym is a demo scenario centered around a mid-sized Italian company that designs, produces, and distributes modular gym and fitness equipment.  
The dataset includes full sales, marketing, HR, and company structure data for realistic training in Power BI.

---

## 🗂️ Data model structure

### 🔸 Fact Tables
- `FactSales`: line-level sales
- `FactOrderSatisfaction`: satisfaction rating per order
- `FactAttendance`: daily attendance and absences
- `FactLeaveBalance`: vacation accrual and use
- `FactPayrollActual`: actual payroll cost
- `FactPayrollBudget`: budgeted payroll

### 🔹 Dimension Tables
- `DimDate`, `DimCustomer`, `DimProduct`, `DimOrder`
- `DimCategory`, `DimSubcategory`, `DimChannel`, `DimLocation`
- `DimCompany`, `DimCampaign`, `DimCurrencyRate`
- `DimEmployee`, `DimFunction`, `DimJobGrade`, `DimCostCenter`, `DimCostItem`, `DimEventType`

---

## 📦 Download

➡️ [Download full package HinergoGym_v1.1.zip](https://github.com/DavidIT2022/HinergoGym/releases/download/v1.1/HinergoGym_v1.1.zip)

All materials in one ZIP (data, documentation, README, etc.)

---

## 👥 HR Dataset (2024–2025)

As of version 1.1, the project includes a **complete HR module**, fully integrated into the main data model.

🧾 Documentation: `Business Case/StorytellingHR.docx` (bilingual IT/EN)

📁 HR tables included in `/Data/`:
- `DimEmployee`, `DimFunction`, `DimJobGrade`
- `DimCostCenter`, `DimCostItem`, `DimEventType`
- `FactAttendance`, `FactLeaveBalance`, `FactPayrollActual`, `FactPayrollBudget`

💡 You can:
- Track daily attendance and paid/unpaid time
- Compare payroll budget vs actual by employee or cost center
- Monitor vacation accrual and usage
- Simulate cost impact of absenteeism and replacements

---

## 🎓 Use cases

- Data modeling and star schema design
- DAX training: from basic measures to complex business logic
- Storytelling on revenue, margin, HR cost, satisfaction, and marketing
- Multicurrency management (with EUR as base)
- KPI tracking and decile-based segmentation

---

## 📁 Folder structure

