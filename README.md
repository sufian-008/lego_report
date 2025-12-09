# 📊 Lego Sales Report – Power BI

This repository contains a Power BI report analyzing Lego sales data, including product performance, category insights, and sales trends. 

<img width="1257" height="718" alt="image" src="https://github.com/user-attachments/assets/bd80c65e-2b12-4487-a85e-01172ff77571" />

---

## 🧱 Project Overview

The purpose of this report is to visually explore Lego sales performance. It includes insights such as:

* Best‑selling Lego categories
* Top revenue‑generating products
* Sales by region and customer group
* Trends over months and years

---

## 🗂️ Dataset Information

| Feature    | Description                         |
| ---------- | ----------------------------------- |
| Product ID | Unique identifier for Lego products |
| Category   | Lego product family/category        |
| Sales      | Sales amount per product            |
| Quantity   | Number of units sold                |
| Date       | Transaction date                    |
| Region     | Sales distribution across locations |

> Note: Dataset was cleaned and transformed using Power Query in Power BI.

---

## 📈 Dashboard Features

The dashboard includes the following visuals:

* **Bar chart** – Top 10 products by sales
* **Pie/Donut chart** – Sales by category
* **Line chart** – Sales trends over time
* **Cards/KPIs** – Total sales, units sold, top category
* **Interactive slicers** – Filter by year, region, category

---

## 🛠️ Tools Used

| Tool             | Purpose                       |
| ---------------- | ----------------------------- |
| Power BI Desktop | Data modeling & visualization |
| DAX              | Measures and KPIs             |
| Power Query      | Data transformation           |

---

## 🚀 How to Open the File

1. Install **Power BI Desktop**
2. Download the `.pbix` report file
3. Open the file in Power BI Desktop

---

## 🧮 Data Model Overview

The report is built using a clean and simple data model consisting of:

### Tables

* **lego_sets** – Main dataset containing product information such as:

  * Name, category, theme, year
  * Pieces, price, and age recommendation
  * Image URL for product visuals
* **Measure Table** – A separate table to store all calculated measures for easier maintenance and performance

### Key Measures Used

| Measure Name | Meaning                                |
| ------------ | -------------------------------------- |
| Avg.Age      | Average recommended age for Lego sets  |
| Avg.pieces   | Average number of pieces per set       |
| Avg.price    | Average price across all Lego sets     |
| Total Groups | Count of theme groups                  |
| Total Sets   | Total number of Lego sets in the model |


