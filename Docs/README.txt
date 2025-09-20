╔════════════════════════════════════════════════════════════════╗
║             	Online Retail Customer Segmentation     		 ║
╚════════════════════════════════════════════════════════════════╝

Tagline: From raw transaction logs → to actionable RFM insights.

────────────────────────────────────────────────────────────────────────
OVERVIEW
────────────────────────────────────────────────────────────────────────
This project performs **RFM (Recency, Frequency, Monetary) analysis** on the
famous *Online Retail Dataset*.  
The goal is to clean, transform, and analyze e-commerce transaction data in 
order to segment customers and uncover patterns in purchasing behavior.

Dataset & Context: Online Retail dataset (UCI ML Repository, 2011 transactions).  
Main Technique: RFM analysis (widely used in marketing & CRM).  

────────────────────────────────────────────────────────────────────────
DELIVERABLES
────────────────────────────────────────────────────────────────────────
I.   Data cleaning (handling nulls, duplicates, invalid entries).  
II.  Feature engineering (TotalPrice, Recency, Frequency, Monetary).  
III. RFM scoring using quantiles.  
IV.  Customer segmentation logic (Loyal, Churned, Big Spenders, etc.).  
V.   Visualizations (bar charts, scatter plots, heatmaps).  

────────────────────────────────────────────────────────────────────────
RFM METRICS
────────────────────────────────────────────────────────────────────────
**Recency (R)** — Days since the last purchase.  
**Frequency (F)** — Number of unique purchase orders.  
**Monetary (M)** — Total money spent by the customer.  

────────────────────────────────────────────────────────────────────────
CLASSIFICATIONS
────────────────────────────────────────────────────────────────────────
✔ Loyal Customers — Low Recency, High Frequency, High Monetary.  
✔ Churned Customers — High Recency, Low Frequency, Low Monetary.  
✔ Big Spenders — Customers with very high Monetary value.  
✔ Active / Regular Buyers — Identified with custom thresholds.  

────────────────────────────────────────────────────────────────────────
VISUALIZATIONS
────────────────────────────────────────────────────────────────────────
1. Bar chart: Customer classification distribution.  
2. Heatmap: Customers by Recency & Frequency scores.  
3. Scatter plot: Frequency vs. Monetary (colored by Recency).  
4. Segment comparisons using RFM scores.  

────────────────────────────────────────────────────────────────────────
HIGHLIGHTS
────────────────────────────────────────────────────────────────────────
• Applied **lambda functions** in groupby aggregations.  
• Implemented **quantile-based scoring** with tie-breaking using rank.  
• Built **classification logic** with flexible thresholds.  
• Combined business rules + visual analytics for insights.  

────────────────────────────────────────────────────────────────────────
NOTES
────────────────────────────────────────────────────────────────────────
• Code written in Python (Pandas, Matplotlib, Seaborn).  
• Interactive exploration possible in Jupyter Notebook.  
• Dataset publicly available from UCI ML Repository.  

────────────────────────────────────────────────────────────────────────
LICENSE & CREDITS
────────────────────────────────────────────────────────────────────────
Author: Andrew Wageh  
Institute: Elevoo, Egypt  
Track: Data Analytics — Internship Task 3 (EDA)  

════════════════════════════════════════════════════════════════════════



