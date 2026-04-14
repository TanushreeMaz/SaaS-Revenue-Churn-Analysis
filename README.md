# 📊SaaS Revenue & Churn Analysis Dashboard

## 🚀 Overview

This project analyzes customer behavior, revenue trends, and churn drivers for a B2B SaaS company (**CloudTask Pro**). The goal is to provide actionable insights to support leadership decisions and improve customer retention.

An interactive Excel dashboard was built using advanced analytics techniques to visualize key business metrics such as churn rate, MRR, customer engagement, and risk segmentation.



## 🎯 Objectives

- Analyze overall and segment-wise churn rates  
- Identify high-risk customer segments  
- Evaluate revenue growth trends over time  
- Compare Customer Lifetime Value (CLV) with Customer Acquisition Cost (CAC)  
- Understand how feature usage and NPS impact churn  


## 🧰 Tools & Technologies

- **Excel (Advanced)**
  - Power Pivot  
  - DAX Measures  
  - Pivot Tables  
  - Data Validation  
- Data Visualization & Dashboard Design  


## 📂 Dataset

The project uses two datasets:

1. **Subscription Data (600 customers)**
   - Customer ID  
   - Plan Type (Starter, Professional, Business, Enterprise)  
   - Billing Cycle (Monthly / Annual)  
   - Churn Status  
   - Feature Usage %  
   - NPS Score  
   - Industry & Company Size  

2. **Monthly Revenue Data (2022–2025)**
   - Monthly MRR  
   - Average Revenue per Customer  


## 📊 Dashboard Features

- 📌 Customer Engagement Funnel  
- 📊 Active vs Churned Customers by Plan  
- 🎯 Feature Usage Gap (Active vs Churned by Industry)  
- 📈 Revenue Trend (Dynamic by Month Selection)  
- 🌍 Revenue Distribution by Region and Plan  
- 🍩 Acquisition Channel Distribution  
- 📉 Customer Sentiment by Company Size  
- 📊 Dynamic KPI Comparison (Billing, Risk, Usage, Upgrade)  


## 🔑 Key Insights


### 🔴 High Churn Rate
- Overall churn rate: **~52%**
- Indicates significant retention challenges



### 📉 Churn Concentration
- Higher churn observed in:
  - Lower-tier plans  
  - Smaller company sizes  



### 💳 Billing Cycle Impact
- Annual subscriptions show better retention  
- Monthly customers are more likely to churn  



### 📊 Usage Drives Retention
- Low feature usage strongly correlates with churn  
- High usage customers are more stable  


### 📈 Revenue Growth vs Risk
- MRR shows steady growth  
- However, high churn threatens long-term sustainability



## ⚠️ At-Risk Customer Definition

Customers are classified as **High Risk** if:

- Feature usage < 30%  
- OR NPS score ≤ 6  



## 💡 Business Recommendations

### 🔧 Improve Onboarding & Feature Adoption
- Implement guided onboarding flows  
- Encourage early feature usage (activation events)  
- Track low-usage users and trigger engagement actions  



### 💳 Promote Annual Plans
- Offer incentives for annual subscriptions  
- Reduce churn by improving long-term commitment


### 🎯 Target High-Risk Segments
- Focus on:
  - Low usage customers  
  - Low NPS segments  
- Use proactive retention strategies


### 📊 Segment-Based Strategy
- Customize experience by:
  - Company size  
  - Industry  
  - Plan type
 


## 📸 Dashboard Preview

<img width="1905" height="821" alt="image" src="https://github.com/user-attachments/assets/b071cb1d-c62d-44d4-acf2-1b384df65fd2" />


## 📁 Project Structure

📦 SaaS-Revenue-Churn-Analysis
┣ 📊 Dashboard.xlsx
┣ 📄 README.md
┣ 📂 SQL
┃ ┗ churn_analysis.sql
┣ 📂 Data
┃ ┣ subscription_data.csv
┃ ┗ monthly_revenue.csv
┣ 📸 dashboard.png


## 🧠 What I Learned

- Building dynamic dashboards using Power Pivot and DAX  
- Translating business problems into data-driven insights  
- Designing clean and interactive dashboards  
- Understanding SaaS metrics like churn, MRR, CLV, and CAC  


## 📌 Conclusion

While the company shows strong revenue growth, high churn remains a major concern. Improving customer onboarding, increasing feature adoption, and targeting high-risk segments can significantly enhance retention and long-term growth.


## ⭐ If you like this project

Feel free to ⭐ the repository or connect with me!

























