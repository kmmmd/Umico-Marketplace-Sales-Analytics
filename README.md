# 📊 Umico Marketplace: Interactive Sales Analytics

This repository contains an interactive sales analysis project developed using **Power BI**. Due to organization privacy policies, the live dashboard link is restricted, but the key insights, data model, and visual architecture are documented below.

---

## 📈 Dashboard Preview
Here is the main view of the interactive dashboard developed for marketplace data:

![Umico Sales Dashboard](dashboard.png)

---

## 🛠️ Key Features & Technical Stack
* **Data Transformation (ETL):** Cleaned and structured raw transactional data using **Power Query**.
* **Data Modeling:** Established relationships between sales, products, and calendar dimensions (Star Schema).
* **Advanced Analytics:** Implemented **DAX (Data Analysis Expressions)** to calculate dynamic business metrics.

---

## 🧮 Core DAX Measures Showcase
To demonstrate the analytical logic behind the visuals, here are some of the key measures used in this project:

```dax
Total Sales = SUM(Sales[Amount])
