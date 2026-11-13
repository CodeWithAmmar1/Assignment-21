# Boomerang Sales & Cost Analysis Dashboard

## Data Integration & Preparation Workflow
* **Source Merging & Joining:** Consolidated disparate transactional data streams by using a join operation to merge the primary text-based transaction logs (`Merge Sales Data.txt`) with relational sales records (`Merge Sales Data.xlsx`) to establish a unified single source of truth.
* **Data Cleansing & Modeling:** Harmonized date formats, standardized company nomenclature (*Gel Boomerangs*, *Colorado Boomerangs*, *Tri Fly*), and mapped product SKU records to enable accurate multi-dimensional cross-filtering.
* **Metric Engineering:** Calculated core financial and operational metrics, including net revenue, direct costs, invoice volumes, and distinct product counts.

---

## Preview 
<img width="824" height="483" alt="image" src="https://github.com/user-attachments/assets/ae9579e3-1846-4e9f-b017-dd9124a3035b" />

---

## Key Business Insights
* **Revenue Leadership:** *Gel Boomerangs* dominates market share, generating nearly half of total net sales (49%) with robust corresponding cost efficiencies.
* **Top Product Performance:** The *Quad* product significantly outperforms all other inventory lines, single-handedly capturing 77K in sales revenue, followed by *Yanaki* at 41K.
* **Seasonal Sales Momentum:** The monthly trend reveals steady baseline performance with a sharp upward trajectory peaking at 32.9K in the final observation period, indicating strong cyclical demand.
* **Profit Margin Stability:** Total Net Sales stand at **$283.80K** against Total Costs of **$144.73K**, maintaining a healthy gross margin profile across all 700 processed invoices and 12 active unique products.

---

## Dashboard Preview & Visual Breakdown
1. **Executive KPI Summary Cards:**
   * **Total Net Sales:** $283.80K
   * **Total Cost:** $144.73K
   * **Total Invoices:** 700
   * **Unique Products:** 12
2. **Net Sales by Company (Donut Chart):** Visualizes proportional revenue share distributed across Gel Boomerangs (49%), Colorado Boomerangs (30%), and Tri Fly (21%).
3. **Product by Sales (Descending Bar Chart):** Ranks individual product lines from top performers (*Quad* at 77K, *Yanaki* at 41K) down to boutique items (*Mt. Fun* and *Fun Fly* at 5K).
4. **Monthly Net Sales Trend (Line Graph):** Tracks month-over-month revenue evolution, highlighting growth fluctuations from 21.9K up to the peak of 32.9K.
5. **Sales and Cost by Company (Clustered Column Chart):** Side-by-side comparative analysis of Gross Sales versus Direct Costs for each company entity (*Gel Boomerangs*, *Colorado Boomerangs*, *Tri Fly*).
