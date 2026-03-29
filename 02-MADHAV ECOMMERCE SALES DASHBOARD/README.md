# 🛒 Madhav Ecommerce Sales Dashboard

An interactive sales analytics dashboard built in **Power BI** to visualize and analyze ecommerce performance data for Madhav Store across India.

![Dashboard Preview](<img width="1437" height="807" alt="preview2" src="https://github.com/user-attachments/assets/a0428551-fa0f-49ac-9f8e-1212efc94968" />
)

---

## 📊 Overview

This dashboard provides a comprehensive view of sales, profit, quantity, and customer trends. It enables business stakeholders to make data-driven decisions through visual insights across categories, states, payment modes, and time periods.

---

## ✨ Features

- 📅 **Quarter Filters** — Toggle between Q1, Q2, Q3, Q4 or view all at once
- 💰 **KPI Cards** — At-a-glance metrics: Total Amount, Profit, Quantity & AOV
- 📈 **Profit by Month** — Identifies seasonal trends and loss months
- 🗺️ **Sales by State** — Top-performing states (Maharashtra, Madhya Pradesh, Uttar Pradesh)
- 🛍️ **Quantity by Category** — Clothing (63%), Electronics (21%), Furniture (17%)
- 💳 **Payment Mode Breakdown** — COD, UPI, Debit Card, Credit Card, EMI
- 👤 **Top Customers** — Revenue contribution by customer name
- 📦 **Profit by Sub-Category** — Printers, Bookcases, Saree, Accessories

---

## 📁 Dataset

The project uses two CSV files:

### `Orders.csv`
| Column | Description |
|--------|-------------|
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| CustomerName | Name of the customer |
| State | Indian state where order was placed |
| City | City of the order |

### `Details.csv`
| Column | Description |
|--------|-------------|
| Order ID | Links to Orders.csv |
| Amount | Revenue generated |
| Profit | Net profit from the order |
| Quantity | Number of items ordered |
| Category | Product category |
| Sub-Category | Product sub-category |
| PaymentMode | Mode of payment used |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development & visualization
- **Microsoft Excel / CSV** — Raw data source
- **DAX** — Calculated measures and KPIs

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/KrishnaveniMitukula/madhav-ecommerce-dashboard.git
   cd madhav-ecommerce-dashboard
   ```

2. **Open the dashboard**
   - Open `MadhavDashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

3. **Load the data**
   - Ensure `Orders.csv` and `Details.csv` are in the same directory
   - Refresh the data source if prompted

---

## 📌 Key Insights

- 📦 **Clothing** dominates quantity sold at **63%** of total orders
- 📍 **Maharashtra** is the highest revenue-generating state
- 💸 **COD** is the most preferred payment mode at **44%**
- 📉 Profit dips significantly in **June, July, and August** — possible seasonal effect
- 🖨️ **Printers** are the most profitable sub-category

---

## 📷 Dashboard Preview

![Madhav Ecommerce Sales Dashboard](<img width="1437" height="807" alt="preview2" src="https://github.com/user-attachments/assets/0b35cab0-5d02-435f-860e-b385fabf6514" />
)

---

## 🙌 Acknowledgements

- Dataset inspired by a retail ecommerce use case for learning purposes
- Built as a Power BI portfolio project

---

## 📬 Contact

Feel free to connect or raise an issue if you have suggestions!

> ⭐ If you found this project useful, give it a star on GitHub!

