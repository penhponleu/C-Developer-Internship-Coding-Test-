# C# Intern Testing

# Product Sales Reporting Tool (WinForms + DevExpress)

This project is a **C# WinForms application** built for a **Developer Internship Coding Test**. It connects to a **SQL Server** database, fetches product sales data, and displays it using **DevExpress XtraReport** with filtering, grouping, and exporting features.

---

## 🧩 Features

- Connects to SQL Server using **ADO.NET**
- Allows filtering sales data by:
  - ✅ Date Range (`Start Date` to `End Date`)
  - ✅ Partial Product Name
- Displays a formatted report using **DevExpress XtraReport**
  - Groups by `ProductCode`
  - Shows detailed product rows
  - Calculates:
    - Group totals (quantity and revenue)
    - Grand totals
  - Displays header information: report title, selected date range, filter name
- Supports exporting the report to **PDF**

---

## 🛠️ Technologies Used

- C# (.NET Framework)
- WinForms
- SQL Server (local or remote)
- DevExpress Reports (`XtraReport`)
- ADO.NET

---

## 📁 Project Structure

