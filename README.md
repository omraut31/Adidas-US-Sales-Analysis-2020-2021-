# 🏆 Adidas US Sales Analysis (2020-2021)

![image](https://github.com/user-attachments/assets/52b60816-55a4-4908-ae01-d0d3687738e6)


An end-to-end data analytics project that explores **Adidas’ US sales performance for fiscal years 2020-2021**, turning raw transaction data into interactive insights.  
Built with **Power BI**, **Python (Pandas/NumPy/Matplotlib)**, and **Excel**, the report uncovers trends in revenue, profit, product mix, geography, seasonality, and sales channels.

---


---

📸 Screenshots
Overview Dashboard
![Screenshot 2025-06-25 204857](https://github.com/user-attachments/assets/7871ad77-23e6-4a61-8188-6f6e8ffa79b4)
![Screenshot 2025-06-25 205013](https://github.com/user-attachments/assets/743122d2-6ede-45b8-9eb4-1e01fc305817)

---


## ✨ Project Highlights

| Metric | Value | Description |
|--------|------:|-------------|
| **Total Sales** | **900 M USD** | Gross revenue across all US channels |
| **Total Profit** | **332 M USD** | Net profit after COGS & discounts |
| **Avg. Price / Unit** | **45 USD** | Weighted average across SKUs |
| **Units Sold** | **2 M** | Total pairs/items sold |

* **Top-5 Cities by Profit:** Portland, Miami, New York, Charleston, Charlotte  
* **Top-Selling Product Line:** *Men’s Street Footwear* (593 K units, 209 M USD sales)  
* **Most Profitable Retailer:** West Gear (86 M USD)  
* **Channel Split:** In-store 39.6 % · Online 27.5 % · Outlet 32.8 %  
* **Seasonality:** Peak in **July–September** (Back-to-school & summer campaigns)

---

## 🔍 Workflow

1. **Data Collection**  
   * Imported `Adidas US Sales Datasets.xlsx` (four transactional tables) from Kaggle.
2. **Data Cleaning & Transformation**  
   * Standardised column names, parsed dates, unified currency, removed duplicates.  
   * Derived metrics: *Profit*, *Margin %*, *Price/Unit*, calendar attributes.
3. **Exploratory Data Analysis (Python)**  
   * Sales trend decomposition, channel comparison, regional heat-maps.  
   * Outlier detection using IQR & Z-score.
4. **Visualization (Power BI)**  
   * Crafted dark-theme dashboard with KPI cards, donut & bar charts, funnel, map.  
   * Added interactive filters: Region · State · City · Retailer · Sales Method.
5. **Insight Generation**  
   * Identified under-performing states → informed marketing re-allocation.  
   * Quantified impact of online discounts on margin.
6. **Storytelling & Sharing**  
   * Published `.pbix` on Power BI Service, exported to PDF, and documented here.

---

## 🛠️ Tech Stack

| Layer | Tools / Libraries |
|-------|-------------------|
| Data wrangling | **Python 3.11**, `pandas`, `numpy` |
| Visualization | **Power BI** (desktop & service), Bing Maps |
| Storage | Excel, CSV |
| Version control | Git, GitHub |

---

## 🚀 Getting Started

> **Prerequisites:**  
> * Windows 10/11 with [Power BI Desktop](https://powerbi.microsoft.com/desktop/)  
> * Python 3.8 + (optional for EDA)  
> * `pip install -r requirements.txt` (see `notebooks/`)

1. **Clone repo**

   ```bash
   git clone https://github.com/<omraut31>/adidas-us-sales-analysis.git
   cd adidas-us-sales-analysis

  `
  
   📬 Contact
   Om Raut – www.linkedin.com/in/omraut31 · omsambhajiraut@gmail.com

  Project Link: <https://github.com/omraut31/adidas-us-sales-analysis>


