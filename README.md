# ShadowFox Data Analyst Internship - Intermediate Level Task

## Project Overview
This project fulfills the intermediate-level requirements for the ShadowFox Data Analyst Internship. The objective is to analyze a realistic e-commerce dataset to uncover customer purchasing behaviors, evaluate segment-level performance, and provide structured, insight-driven business recommendations.

## Data Cleaning & Preparation
* **Dataset Selection:** Generated a custom e-commerce dataset featuring 150 transactions with variables including `Order_ID`, `Customer_ID`, `Purchase_Date`, `Product_Category`, `Customer_Segment` (New, Returning, VIP), and `Region`.
* **Standardization:** Validated date formats to `YYYY-MM-DD` and ensured currency values in `Order_Value_USD` were standardized to two decimal places.
* **Integrity Checks:** Verified there were no duplicate `Order_ID`s and that all categorical variables mapped correctly to their predefined lists.

## Exploratory Data Analysis & Key Insights

**1. Overall Revenue Health**
* Total Revenue Generated: **$29,172.50**
* Average Order Value (AOV): **$194.48**
* The business is maintaining a healthy AOV, driven significantly by premium electronics purchases. 

**2. Customer Segment Performance (The Pareto Principle in Action)**
* While VIP customers only make up approximately 20% of the customer base, they accounted for **39.7% of total revenue** ($11,582.50).
* **Insight:** VIPs have a substantially higher AOV due to a 2.5x spending multiplier compared to New and Returning customers. Customer retention and upgrading users to VIP status is the most effective lever for revenue growth.

**3. Product Category Breakdown**
* **Electronics:** $12,254.00 (42% of revenue) - The absolute leader in revenue generation.
* **Sports:** $6,040.50
* **Home & Garden:** $5,818.00
* **Apparel:** $5,060.00
* **Insight:** Electronics carry the highest base price and are disproportionately favored by VIP and Returning customers. Apparel yields the lowest revenue, suggesting a need for bundle-pricing strategies.

## Actionable Business Recommendations
Based on the data interpretation, the business should implement the following strategies:
1. **Launch a VIP Loyalty Initiative:** Since VIPs drive nearly 40% of revenue, create a specific nurturing sequence for "Returning" customers to bridge them into VIP status. Offer exclusive early access to high-ticket Electronics to secure their loyalty.
2. **Category Bundling for Apparel:** To increase the low revenue share of Apparel, bundle clothing items with popular Sports equipment (e.g., selling activewear alongside home gym gear) to artificially raise the AOV for those transactions.
3. **Retention over Acquisition:** Allocate marketing budget away from acquiring "New" customers and funnel it into remarketing campaigns targeting recent one-time buyers, as the data proves repeat/VIP purchasing behavior is the primary revenue engine.
4. 
