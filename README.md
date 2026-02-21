# Claims-Policyholder-Risk-Analysis-Dashboard
📊 Purpose: Identify high-risk policyholders, track claims trends, and analyze policy adjustments.

🔹 Key Metrics:

Total Claims (SUM(Claims_Frequency))
Average Claims per Policyholder (AVERAGE(Claims_Frequency))
Claim Severity Distribution (Low/Medium/High)
Claims Adjustment Impact (SUM(Claims_Adjustment))
📈 Visuals:

Bar Chart: Claims Frequency by Age Group or Region
Heatmap: Claim Severity by Region
KPI Cards: Total Claims, Average Claim Amount
Average Claim Amount = DIVIDE(SUM(‘synthetic_insurance_data'[Claims_Adjustment]), SUM(‘synthetic_insurance_data'[Claims_Frequency]), 0)

Scatter Plot: Premium Amount vs. Claims Frequency
🎯 Filters: Policy Type, Region, Age Group, Marital Status

2. Premium vs. Claims Profitability Dashboard

📊 Purpose: Evaluate whether policyholders are profitable based on claims paid vs. premiums collected.

🔹 Key Metrics:

Total Premiums Collected (SUM(Premium_Amount))
Total Claims Adjustments (SUM(Claims_Adjustment))
Loss Ratio (SUM(Claims_Adjustment) / SUM(Premium_Amount))
Average Premium per Policyholder
📈 Visuals:

Bar Chart: Premiums vs. Claims per Policy Type
Treemap: Contribution of each Region to Total Premiums
Line Chart: Loss Ratio Trends Over Time
Scatter Plot: Credit Score vs. Premium Adjustment
🎯 Filters: Region, Policy Type, Age Group

3. Customer Behavior & Retention Dashboard

📊 Purpose: Analyze policyholder engagement, lead sources, and conversion rates.

🔹 Key Metrics:

Conversion Rate (SUM(Conversion_Status) / COUNT(Premium_Amount))
Average Website Visits before Purchase
Quotes Requested per Converted Customer
Retention Rate (Policy Renewals vs. New Policies)
📈 Visuals:

Funnel Chart: Leads → Quotes → Conversions
Bar Chart: Source of Lead vs. Conversion Rate
Line Chart: Retention Trends Over Time
Card KPI: Churn Rate, Average Time to Conversion
🎯 Filters: Lead Source, Time to Conversion, Region

4. Discounts & Incentives Impact Dashboard

📊 Purpose: Understand how different discounts affect claims and retention.

🔹 Key Metrics:

Total Discounts Given (SUM(Total_Discounts))
Claims Frequency of Discounted vs. Non-Discounted Customers
Premium Adjustments Impact on Customer Retention
📈 Visuals:

Box Plot: Claims Frequency by Discount Type
Stacked Bar Chart: Premium Adjustments per Policy Type
Line Chart: Customer Retention Rate vs. Discount Offered
🎯 Filters: Discount Type, Policy Type, Region

Dataset is available here : https://www.kaggle.com/datasets/samialyasin/insurance-data-personal-auto-line-of-business/data\
