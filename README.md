# 📞 E-Commerce Call Center & Sales Performance Dashboard

This project presents a full Power BI analysis of call center performance, product orders, employee activity, and client behavior for an e-commerce business.

---

## 🎯 Objective

To help the business:
- Improve call center responsiveness
- Understand customer behavior by product, city, and time
- Increase order approval rates
- Support better decision-making through actionable insights

---

## 📊 Key KPIs Visualized

- ✅ Total Orders: **1,369**
- 🧑‍🤝‍🧑 Total Customers: **471**
- 📍 Cities: **78**
- 📦 Orders Under Review: **705**
- ❌ Rejected Orders: **270**
- 💰 Avg. Product Price: **167 EGP**
- 🏆 Top Store: **Ibn Al-Bitar 1**
- 🛍️ Best-Selling Product: **BeeFirm**
- 🚫 Most Rejected Product: **BeeFirm Marhaba**

---

## 🔍 Main Dashboard Sections

### 1. **Sales Insights**
- Best and worst selling products
- Most rejected products
- Approval/rejection rates

### 2. **City-Based Analysis**
- Order distribution by customer city
- Approval rate per city

### 3. **Call Center Agent Performance**
- Number of orders handled per agent
- Call response rate per hour
- Avg. number of contact attempts

### 4. **Time-Based Patterns**
- Hourly performance chart
- Employee effectiveness by time of day

---

## 🛠️ Recommendations for Improvement

### ✅ 1. Data Accuracy & Tracking
- Many **unclassified city values** skew the analysis → ensure data validation.
- Retain **all contact attempts**, not just the last one, to better measure effort.
- Raise **data awareness** within the team: accurate inputs = smarter decisions.

### ✅ 2. Add Analytical Columns
- `Response Time` = Time of answer - Time of call  
- `# of Contact Attempts`  
- `Rejection Reason` (if collected)  
- `Targeted Product` for personalized marketing

### ✅ 3. Team Development
- Track top-performing agents
- Offer **training** based on proven techniques

### ✅ 4. Time-Based Strategy
- Since data is from a single day, analyze **by hour**
- Identify hot hours for approvals

### ✅ 5. Visual Strategy by City/Product
- Use **stacked column charts**:
  - X-axis: City
  - Legend: Product Name
  - Value: Number of Approvals
- 🧠 Insight: "Product X sells more in Benghazi, Y in Sabratha → stock accordingly."

### ✅ 6. Standardize Status Mapping

| Raw Status               | Final Classification |
|--------------------------|----------------------|
| استلم / رد ويستلم         | ✅ Approved          |
| رفض الاستلام / مغلق / ألغى / مش طالب | ❌ Rejected |
| لم يرد                    | 📞 No Answer         |
| أجل الاستلام             | ⏳ Delayed           |
| Other                    | Uncategorized        |

---

## ✅ Additional Key Recommendations (from Real Case Review)

1. **Log All Contact Attempts**
   - Keep a full history of contact attempts, not just the latest one.
   - This allows a more accurate understanding of how many follow-ups were needed and improves analysis of agent effort.

2. **Add Analytical Columns to Enhance Insights**
   - `Response Duration` = Response Time – Call Time  
   - `Number of Contact Attempts`  
   - `Rejection Reason` (if available)  
   - `Targeted Product` – helps align offers to customer interests and optimize marketing.

3. **Handle Unclassified City Data**
   - A large number of "Unclassified" cities reduces the reliability of geographic insights and creates outliers.
   - Input validation and standardized entry are strongly recommended.

4. **Support Underperforming Employees**
   - Monitor top-performing agents, learn from their communication style, and offer practical training to those with lower approval rates.

5. **Time-Based Analysis for a Single Day**
   - Since the dataset covers one day, break down performance by hour to discover high-response time slots.

6. **Organize the Dashboard into Separate Views**
   - Create separate sheets or dashboards for:
     - Sales overview  
     - Employee performance  
     - Order status analysis  
   - This improves clarity and helps focus analysis.

7. **Raise Team Awareness about Data Quality**
   - Emphasize that accurate data entry isn't just a routine task — it directly impacts decision-making and overall team performance.

---

## 📎 File Structure

```plaintext
📁 Dataset (if public)
📄 ilovepdf_merged.pdf → Power BI Dashboard Screenshots
📄 Presentation.pdf → Summary of insights and visuals
📄 README.md → This file
💡 Developed by: Hasnaa Ahmed – Data Analyst
