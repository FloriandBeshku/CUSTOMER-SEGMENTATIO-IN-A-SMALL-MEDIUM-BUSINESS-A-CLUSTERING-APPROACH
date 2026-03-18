# CUSTOMER SEGMENTATION IN A SMALL MEDIUM BUSINESS 
## A CLUSTERING APPROACH / UNSUPERVISED ML TECHNIQUE
### Floriand Beshku | 2026

This project demonstrates how data can be used to develop a structured understanding of customer behavior by replacing informal assumptions with a **data-driven customer segmentation approach**. Instead of treating all customers the same, the analysis identifies distinct behavioral groups and explains the patterns that separate one customer type from another.

By using clustering techniques, the project reveals how differences in visit frequency, spending habits, ordering preferences, and in-store behavior naturally form meaningful customer segments. These insights allow businesses to design more targeted marketing strategies, optimize operations, and improve customer experience.

---

# Business Problem

Many small and medium-sized businesses rely on intuition or staff experience to understand their customers. While helpful, this informal approach often leads to broad assumptions and inconsistent decision-making.

Without clear customer segmentation, businesses face several challenges:

- **Generic Marketing Campaigns:** Promotions are sent to all customers instead of targeted groups.  
- **Inefficient Resource Allocation:** Marketing and operational resources are not directed toward the most valuable segments.  
- **Limited Customer Insight:** Businesses struggle to explain why certain customers behave differently.

This project addresses the key question:

**Can customers be grouped into meaningful behavioral segments that support better marketing and operational decisions?**

---

# Technical Stack

**Language:** Python  
**Environment:** Anaconda / Jupyter Notebook  

**Libraries Used**

- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
- SciPy (clustering)

**Modeling Techniques**

- Hierarchical Clustering  
- K-Means Clustering  
- Principal Component Analysis (PCA)

---

# Dataset

The analysis is based on a dataset containing **500 coffee shop customers**, where each row represents a customer and summarizes their typical purchasing and visit behavior.

### Key Behavioral Variables

- visits_per_month  
- avg_ticket_usd  
- avg_drinks_per_visit  
- avg_food_items_per_visit  
- pct_food_orders  
- avg_dwell_minutes  
- pct_mobile_orders  
- pct_dine_in  
- discount_redemption_rate  
- weekend_share_pct  
- avg_party_size  
- work_session_pct  

These variables capture the behaviors that matter most for business performance: **customer frequency, spending patterns, product mix, time spent in the shop, and ordering channels.**

---

# Methodology & Workflow

The project follows a structured data science workflow:

## 1. Data Preparation
- Reviewed dataset for consistency  
- Selected behavioral variables relevant for segmentation  
- Standardized numerical features to ensure equal contribution in clustering  

## 2. Exploratory Analysis
- Examined behavioral distributions  

## 3. Hierarchical Clustering
- Built a dendrogram to observe how customers naturally group together  
- Evaluated cluster separation  
- Identified an initial segmentation structure  

## 4. K-Means Clustering
- Applied K-Means to generate stable customer groups  
- Compared results with hierarchical clustering  
- Selected **3 clusters** as the most interpretable and actionable segmentation  

## 5. Cluster Validation & Visualization
- Used **PCA** to visualize customer clusters in two dimensions  
- Compared centroid profiles to interpret customer behaviors  

---

# Key Results & Customer Segments

The clustering analysis revealed **three clear behavioral customer segments**:

### Segment 1 — Frequent Grab-and-Go Customers
Customers who visit frequently, spend less per visit, and typically place quick orders with short dwell times.

### Segment 2 — Long-Stay Dine-In Customers
Customers who spend more time in the coffee shop, often using it as a place to work, study, or socialize.

### Segment 3 — Food-Focused Occasional Customers
Customers who visit less frequently but tend to spend more per visit and often purchase food items.

---

# Business Applications

The segmentation results translate directly into actionable business strategies:

- **Targeted Promotions:** Tailor offers to specific customer segments instead of broad campaigns.
- **Operational Optimization:** Align staffing, preparation, and service flow with customer behavior patterns.
- **Revenue Growth Opportunities:** Increase basket size and customer retention through segment-specific strategies.
