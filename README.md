# 💊 PharmaDash — Pharma Company Sales Dashboard

**An interactive Excel-based sales analytics dashboard for tracking pharmaceutical product performance, regional KPIs, and profitability insights — all in one place.**


---

## 📸 Dashboard Preview

> 🖼️ *Screenshots of the dashboard are shown below. Upload your images to a folder called `/images` in this repository and update the paths accordingly.*


### 📊 KPI Summary Sheet
![KPI Sheet](images/kpi-sheet.png)

### 🗺️ Regional Performance
![Regional Performance](https://github.com/akashsheet10/Pharma_company_Analysis/blob/main/Screenshot%202026-04-21%20212145.png?raw=true)

### 💰 Profit Analysis
![Profit Analysis](https://github.com/akashsheet10/Pharma_company_Analysis/blob/main/Screenshot%202026-04-21%20212208.png?raw=true)

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Key Metrics at a Glance](#-key-metrics-at-a-glance)
- [Data Structure](#-data-structure)
- [Product Portfolio](#-product-portfolio)
- [Regional Breakdown](#-regional-breakdown)
- [KPI Insights](#-kpi-insights)
- [File Structure](#-file-structure)
- [How to Use](#-how-to-use)
- [Contributing](#-contributing)

---

## 🧬 About the Project

**PharmaDash** is a comprehensive Excel dashboard designed for pharma business analysts, sales managers, and operations teams to monitor and evaluate:

- 📦 Product-wise sales performance (OTC & Prescription)
- 🌍 Region-wise revenue and profit distribution
- 👨‍💼 Sales representative performance tracking
- 📅 Monthly profit trends over time
- 💹 Profitability ratios by product category

The dashboard consolidates raw transactional data into clean **KPI summaries**, **pivot-based analytics**, and **visual charts** — helping decision-makers act on insights faster.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---|
| 💰 **Total Profit** | ₹1,43,500 |
| 📦 **Total Units Sold** | 2,396 units |
| 🗓️ **Months Tracked** | Jan – May |
| 🏷️ **Products Tracked** | 10 unique products |
| 🌍 **Regions Covered** | North, South, East, West |
| 🧪 **Product Categories** | OTC (10 entries) & Prescription (10 entries) |

---

## 🗃️ Data Structure

The workbook contains the following sheets:

| Sheet Name | Description |
|---|---|
| `raw data` | Core transactional data — all sales records with product, region, rep, units, revenue, cost & profit |
| `KPi` | Pivot-table driven KPI summary — profit by month, region, category, and product |
| `Region` | Region-specific performance breakdowns |
| `Profit` | Deep-dive profit analysis by product |

### 📋 Raw Data Columns

```
### 📋 Raw Data Columns

| Column | Description |
|---|---|
| `Product ID` | Unique identifier for each product |
| `Product Name` | Name of the pharmaceutical product |
| `Category` | OTC or Prescription |
| `Region` | Sales region — North, South, East, West |
| `Sales Rep` | Name of the assigned sales representative |
| `Units Sold` | Number of units sold in that entry |
| `Revenue ($)` | Total revenue generated |
| `Cost ($)` | Total cost incurred |
| `Profit ($)` | Net profit (Revenue minus Cost) |
| `Month` | Month of the transaction |
```

---

## 💊 Product Portfolio

The dashboard tracks **10 pharmaceutical products** across two categories:

### 🟢 OTC (Over-The-Counter)
| Product | Total Units Sold |
|---|---|
| RespiraAid | 410 |
| Dermacare | 350 |
| ImmunoBoost | 310 |
| VisionPro | 290 |
| PainRelief Plus | 250 |

### 🔵 Prescription
| Product | Total Units Sold | Profit % Share |
|---|---|---|
| NeuroMax | 125 | **14.98%** ⬆️ Highest |
| HepaGuard | 185 | 12.89% |
| GlucoBalance | 173 | 12.06% |
| CardioCare | 150 | 11.15% |
| OsteoFlex | 153 | 10.66% |

> 💡 **Prescription products generate 61.7% of total profit** despite equal product count with OTC.

---

## 🗺️ Regional Breakdown

| Region | Total Profit | Units Sold |
|---|---|---|
| 🟠 East | ₹45,800 | 398 |
| 🔵 West | ₹42,800 | 388 |
| 🟢 South | ₹27,500 | 810 |
| 🔴 North | ₹27,400 | 800 |

> 📌 **East & West** lead in profitability. **South & North** lead in volume — suggesting higher OTC activity in those regions.

---

## 📈 KPI Insights

### Monthly Profit Trend

```
Jan  ██████████████████  ₹29,000
Feb  █████████████████   ₹28,500
Mar  ███████████████     ₹24,500  ← Dip
Apr  █████████████████████ ₹33,900  ← Peak
May  █████████████████   ₹27,600
```

> 📆 **April** recorded the highest profit at ₹33,900. **March** saw the lowest at ₹24,500 — flagging a potential area to investigate for seasonal factors or rep performance.

### Profit by Category
| Category | Total Profit | Share |
|---|---|---|
| Prescription | ₹88,600 | **61.7%** |
| OTC | ₹54,900 | 38.3% |

---

## 📁 File Structure

```
## 📁 File Structure

| File / Folder | Description |
|---|---|
| `pharma_company_dash.xlsx` | 📊 Main Excel dashboard file |
| `README.md` | 📄 Project documentation (this file) |
| `images/dashboard-overview.png` | 🖼️ Screenshot of the main dashboard |
| `images/kpi-sheet.png` | 🖼️ Screenshot of the KPI summary sheet |
```

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/pharma-dashboard.git
   ```

2. **Open the Excel file**
   ```
   Open pharma_company_dash.xlsx in Microsoft Excel (2016 or later recommended)
   ```

3. **Navigate the sheets**
   - Start with the **`KPi`** sheet for a quick executive summary
   - Drill into **`raw data`** to explore or update individual records
   - Check **`Region`** and **`Profit`** for targeted analysis

4. **Update data**
   - Add new rows to the `raw data` sheet following the existing format
   - Refresh all **Pivot Tables** (`Data → Refresh All`) to update KPIs automatically

---

## 📬 Contact

> Made with ❤️ for pharma analytics enthusiasts.
> Feel free to connect or raise an issue if you have questions!

---


⭐ **If you found this dashboard useful, consider giving it a star!** ⭐
