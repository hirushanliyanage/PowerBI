<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=F7931E&height=200&section=header&text=Furniture%20Sales%20Dashboard&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Power%20BI%20%7C%20Data%20Analytics%20%7C%20OLAP%20Operations&descAlignY=56&descColor=ffffff" width="100%"/>

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)
[![CSV](https://img.shields.io/badge/CSV%20Data-4CAF50?style=for-the-badge&logo=files&logoColor=white)]()

</div>

---

## 📌 Project Overview

**Furniture Sales Dashboard** is an end-to-end business intelligence project built with **Microsoft Power BI**. It analyses 2,500 furniture sales records to uncover revenue trends, profit performance, seasonal patterns, and inventory insights — across multiple store types, locations, and product categories.

The project also demonstrates **OLAP (Online Analytical Processing)** operations including Slice, Dice, Roll-Up, Drill-Down, and Pivot on multi-dimensional sales data.

---

## 📁 Project Structure

```
PowerBI-main/
├── 📊 Furniture_Dashboard.pbix     # Main Power BI dashboard file
├── 📋 furniture_sales.xlsx         # Sales transactions dataset (2,500 records)
├── 🗂️ furniture_product.csv        # Product catalogue (categories, brands, materials)
└── 🧮 Olap operations.xlsx         # OLAP operations workbook
    ├── Slice & Roll Up
    ├── Dice
    ├── Pivot
    └── Drill Down
```

---

## 📊 Dataset Details

### `furniture_sales.xlsx` — Sales Transactions (2,500 rows)

| Column | Description |
|---|---|
| `price` | Selling price per unit ($50 – $500) |
| `cost` | Cost of goods sold |
| `sales` | Units sold per transaction |
| `profit_margin` | Profit margin % (10% – 50%) |
| `inventory` | Stock level at time of sale |
| `discount_percentage` | Discount applied (0% – 30%) |
| `delivery_days` | Days taken for delivery (1 – 9) |
| `location` | Rural / Suburban / Urban |
| `season` | Spring / Summer / Fall / Winter |
| `store_type` | Online / Retail |
| `revenue` | Total revenue generated |

### `furniture_product.csv` — Product Catalogue (2,500 rows)

| Column | Values |
|---|---|
| `category` | Bed, Chair, Table, Sofa, Desk |
| `material` | Wood, Metal, Plastic, Glass, Fabric |
| `color` | Red, Blue, Black, Green, Brown, White |
| `brand` | BrandA, BrandB, BrandC, BrandD |

---

## 🔍 OLAP Operations

This project demonstrates four core OLAP operations on the sales data:

| Operation | Description |
|---|---|
| **Slice** | Filter data by a single dimension (e.g., Summer season only) |
| **Roll Up** | Aggregate data to a higher level (e.g., monthly → seasonal totals) |
| **Dice** | Filter across multiple dimensions simultaneously (e.g., Summer + Urban) |
| **Drill Down** | Break down aggregated data into finer granularity (e.g., season → month → week) |
| **Pivot** | Rotate data dimensions to view from a different perspective |

---

## 📈 Dashboard Insights

The Power BI dashboard covers the following analytical views:

- 💰 **Revenue Analysis** — Total revenue breakdown by season, location, and store type
- 📦 **Product Performance** — Category and brand-wise sales comparison
- 🏷️ **Pricing & Discounts** — Impact of discount percentage on profit margin and revenue
- 🗺️ **Location Insights** — Urban vs Suburban vs Rural performance comparison
- 🛒 **Store Type Analysis** — Online vs Retail revenue and sales volume
- 📅 **Seasonal Trends** — Quarterly and seasonal revenue patterns
- 🚚 **Delivery Analysis** — Delivery time distribution and its impact on sales
- 📉 **Inventory Management** — Stock levels vs sales velocity

---

## 🚀 Getting Started

### Prerequisites

- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)
- Microsoft Excel (for viewing OLAP operations workbook)

### Steps to Open

```bash
# 1. Clone this repository
git clone https://github.com/Hirushan-Liyanage/PowerBI-Furniture-Dashboard.git

# 2. Open Power BI Desktop

# 3. Open the dashboard file
File → Open → Furniture_Dashboard.pbix

# 4. Refresh data if prompted
Home → Refresh
```

> **Note:** If data source paths prompt an error, go to `Home → Transform Data → Data Source Settings` and update the paths to where `furniture_sales.xlsx` and `furniture_product.csv` are stored on your machine.

---

## 🧠 Key Metrics

| Metric | Value |
|---|---|
| Total Records | 2,500 |
| Avg Revenue per Transaction | ~$5,927 |
| Max Revenue | $32,922 |
| Price Range | $50 – $500 |
| Avg Profit Margin | ~30% |
| Avg Delivery Time | ~5 days |
| Product Categories | 5 |
| Brands | 4 |
| Locations | 3 (Rural / Suburban / Urban) |
| Seasons | 4 (Spring / Summer / Fall / Winter) |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard creation and data visualisation |
| **Microsoft Excel** | OLAP operations and data exploration |
| **CSV / XLSX** | Data source formats |
| **DAX** | Calculated measures and KPIs in Power BI |
| **Power Query** | Data transformation and cleaning |

---

## 📂 How to View OLAP Operations

1. Open `Olap operations.xlsx` in Microsoft Excel
2. Navigate through the four sheets: **Slice & Roll Up**, **Dice**, **Pivot**, **Drill Down**
3. Each sheet demonstrates a different multi-dimensional analysis technique applied to the furniture sales data

---

## 👨‍💻 Author

**Hirushan Liyanage**
> BSc (Hons) Information Technology — Data Science | SLIIT

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/Hirushan-Liyanage)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kaveeshaliyanage08@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Hirushan-Liyanage)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=217346&height=100&section=footer" width="100%"/>
</div>
