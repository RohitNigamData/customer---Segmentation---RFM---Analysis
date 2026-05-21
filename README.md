
<img width="1307" height="731" alt="Screenshot 2026-05-21 202145" src="https://github.com/user-attachments/assets/469b74ad-25da-45a2-8ebb-e9b681baadb5" />

## 📌 Project Overview & Objective
This end-to-end data analytics project is performed on transactional datasets to identify high-value customer cohorts, at-risk segments, and new growth opportunities. By implementing a statistical *RFM (Recency, Frequency, Monetary)* model, this pipeline translates raw transaction logs into actionable business strategies. The final multi-page interactive Power BI dashboard is designed to drive personalized marketing strategies, reduce Customer Acquisition Costs (CAC), and maximize Customer Lifetime Value (CLV).

## 🛠️ Tech Stack & Architecture
* *Data Engineering & Analytics:* Python (Pandas, NumPy)
* *Development Environment:* Jupyter Notebook
* *Data Visualization & Modeling:* Power BI Desktop
* *Statistical Approach:* Quantile-based Bucketing (pd.qcut) for dynamic behavioral scoring.

## 📊 Key Business Insights & Data Storytelling
Based on the final pipeline analysis, 5 critical customer segments were isolated to drive data-backed strategic decisions:

1. *VIP / Champions (High Recency, High Frequency, High Monetary):* * Insight: These customers represent the highest revenue concentration despite lower volume.
   * Action: Shift budget away from margin-diluting discounts toward exclusive loyalty perks and early-access rewards.

2. *At-Risk / High-Value Churn (Low Recency, High Frequency, High Monetary) 🚩:*
   * Insight: Critical danger zone. These are high-ticket buyers who haven't transacted recently, indicating potential competitor poaching.
   * Action: Deploy immediate automated "Win-Back" email campaigns with premium target offers to capture revenue before complete attrition.

3. *High-Ticket Occasional (Low Frequency, High Monetary):*
   * Insight: Customers who buy rarely but spend heavily when they do (e.g., seasonal or event-based buyers).
   * Action: Avoid daily spamming; target strictly during major product launches or festive campaigns.

4. *Recent New Onboards (High Recency, Low Frequency):*
   * Insight: First-time or second-time buyers with a fresh onboarding footprint.
   * Action: Trigger welcome rewards and tutorial-driven retention paths to convert them into repeat buyers.

5. *Regular / Average (Mid-tier Footprint):*
   * Insight: Represents the volume backbone of the day-to-day transactions.
   * Action: Maintain steady engagement via personalized recommendations and standard dynamic pricing.
* *Dynamic Cross-Filtering:* Integrated custom RFM Cell Slicers allowing stakeholders to explore individual behavioral cohorts instantly.
* *Executive KPIs:* Clean layout featuring core metric indicators for Total Active Customers, Total Value, and Average Purchase Frequency.
* *Visual Hierarchy:* Consistent color themes to isolate immediate business pain points (like Churn risk vs. Value drivers).
