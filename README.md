🧠 Business Intelligence Project – Retail Store Expansion Strategy

📌 Project Overview

The main objective was to perform a **data-driven analysis** using the Sample Superstore dataset to recommend the most profitable **five states in the U.S.** for opening new retail stores and identify **top-performing product categories** to stock.

---

📊 Dataset

- **Source**: Sample Superstore dataset (Tableau)
- **Scope**: Transactional sales data including:
  - Sales, Profit, Discounts
  - Product Categories/Subcategories
  - Geographical Information (State)
  - Customer Segments (Corporate, Consumer, Home Office)
  - Order and Ship Dates

---

🧹 Data Preparation

Performed in **Excel** and **Tableau**:

- Removed missing values and duplicates
- Filtered only U.S.-based transactions
- Standardized categorical fields
- Aggregated data by state and product subcategory
- Created calculated fields:
  - `Profit Margin = Profit / Sales`
  - `Avg Sales per Order = SUM(Sales) / COUNTD(Order ID)`
  - `Rank by Profit`, `Rank by Sales`
  - `Shipping Time = DATEDIFF(Order Date, Ship Date)`

---

🔍 Analysis Approach

### 1. **State-Level Profitability**
Identified top 5 profitable states using aggregated profit data:
- **California**
- **New York**
- **Washington**
- **Virginia**
- **Michigan**

### 2. **Product Category Analysis**
Focused on **Office Supplies**, especially:
- **Paper**
- **Art**
- **Labels**
- **Envelopes**

These subcategories showed consistent profitability and high demand.

### 3. **Customer Segmentation**
- **Corporate** customers dominated Office Supplies demand.
- **Home Office** and **Consumer** segments also showed specific trends.

### 4. **Seasonal Trends**
- Demand spikes before school (Paper, Art)
- Holiday season (November–December)

### 5. **Discount Impact**
- Moderate discounts helped in boosting sales
- High discounts reduced profit, especially in Furniture

---

🛠 Tools Used

| Tool     | Purpose                        |
|----------|--------------------------------|
| **Excel**  | Data cleaning & aggregation   |
| **Tableau** | Visualization & dashboarding |

Visualizations included:
- Bar & Line Charts
- Profitability Maps
- Customer Segmentation Insights
- Time-based sales trends

---

✅ Recommendations

📍 Store Locations
Open new stores in:
- California
- New York
- Washington
- Virginia
- Michigan

📦 Product Strategy
Focus inventory on:
- Paper
- Art supplies
- Labels
- Envelopes

🧠Operational Strategy
- Use dashboards to monitor performance
- Align inventory with seasonal demand
- Segment marketing campaigns (e.g., B2B focus)
