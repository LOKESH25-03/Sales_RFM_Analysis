# Sales Segmentation - RFM Analysis

## Overview

This project implements RFM (Recency, Frequency, Monetary) analysis to segment customers based on their purchasing behavior and drive targeted marketing strategies. By analyzing customer transaction data using Power BI, the project identifies high-value customers, at-risk segments, and growth opportunities. The interactive dashboard provides actionable insights into customer lifetime value, sales trends, and segment-specific performance metrics to optimize customer retention and revenue growth.

## Business Problem

Understanding customer behavior is critical for effective marketing and sales strategies. This project aims to:
- Segment customers based on RFM metrics to identify Champions, Loyal Customers, At Risk, and Lost segments
- Analyze sales performance across different time periods and categories
- Identify customer purchasing patterns to enable personalized marketing campaigns
- Optimize resource allocation by focusing on high-value customer segments

## What is RFM Analysis?

**RFM Analysis** is a data-driven customer segmentation technique that evaluates customers based on three key metrics:

- **Recency (R)**: How recently a customer made a purchase (days since last purchase)
- **Frequency (F)**: How often a customer makes purchases (number of transactions)
- **Monetary (M)**: How much money a customer spends (total purchase value)

By scoring customers on these dimensions, businesses can identify their most valuable customers and tailor marketing strategies accordingly.

## Dataset

The dataset contains transactional sales data with customer purchase history:

**Key Features:**
- Customer ID and customer names
- Transaction dates and order details
- Purchase amounts (monetary value)
- Product categories (Office Supplies, Furniture, Technology)
- Geographic information (cities)
- RFM calculated metrics:
  - Recency: Days since last purchase
  - Frequency: Total number of purchases
  - Monetary: Total spending amount

**Customer Segments Identified:**
- **Champions**: High recency, frequency, and monetary values
- **Loyal Customers**: Frequent buyers with good monetary value
- **At Risk**: Previously valuable customers showing declining engagement
- **Big Spenders**: High monetary value customers
- **Lost**: Customers who haven't purchased recently
- **Others**: Remaining customer segments

**Data Volume:** 100+ customers with complete transaction history

## Tools & Technologies

- **Power BI Desktop**: Interactive dashboard development and data visualization
  - DAX calculations for RFM metrics
  - Custom measures and KPIs
  - Advanced filtering and drill-through capabilities
- **Power Query**: Data transformation and cleaning
- **Microsoft Word**: Detailed analytical report
- **Gamma**: Professional presentation creation
- **Excel/CSV**: Source data format

## Project Workflow

### 1. Data Loading & Preparation
- Imported sales transaction data into Power BI
- Validated data quality and completeness
- Examined data structure and relationships
- Identified key columns for RFM calculation

### 2. Data Transformation & Feature Engineering

**Power Query Transformations:**
- Standardized date formats for accurate recency calculations
- Removed duplicate transactions
- Handled missing values in customer and product data
- Created customer master table with unique identifiers

**RFM Metrics Calculation:**
- **Recency**: Calculated days between last purchase date and current date
- **Frequency**: Counted total number of transactions per customer
- **Monetary**: Summed total purchase value per customer
- **Customer Segmentation**: Applied RFM scoring logic to categorize customers into segments

### 3. DAX Measures & Calculations

** i) Core KPIs**
** ii) Year-over-Year Comparison**

** iii) Segment Analysis:**

### 4. Dashboard Development

Built a comprehensive single-page dashboard featuring:
- Sales performance metrics with trend indicators
- Monthly sales overview with dual-axis chart (sales + customers)
- Customer segmentation analysis
- Category-wise sales distribution
- Detailed customer table with RFM metrics
- Interactive filters for city and year selection

### 5. Reporting & Presentation
- Compiled analytical findings in Word document
- Created executive presentation using Gamma
- Documented insights, trends, and recommendations

### Key Performance Indicators (KPIs)

**Sales Metric:**
- **Total Sales**: $613K
- **YoY Growth**: ▲ 29.9% | LY $472K
- Clear upward trend indicator

**Avg Recency:**
- **Current**: 167 days
- **YoY Change**: ▼ (16.9%) | LY 201 days
- *Lower recency is better - indicates recent purchases*

**Avg Frequency:**
- **Current**: 6 purchases per customer
- **YoY Change**: ▼ (1.1%) | LY 6 purchases
- Slight decline needs attention

**Avg Monetary:**
- **Current**: $2,658 per customer
- **YoY Change**: ▼ (2.1%) | LY $2.72K
- Minor decrease in average spending

## Key Insights & Results

### Sales Performance
1. **Strong Growth**: 29.9% YoY sales increase to $613K demonstrates healthy business growth
2. **Customer Expansion**: Total customer base showing upward trend
3. **Seasonal Patterns**: November shows peak performance with $95K in sales
4. **Consistent Momentum**: Steady month-over-month growth from January ($27K) to November ($95K)

### Customer Segmentation Insights
1. **Champions Segment**: 126 high-value customers - target for VIP programs and exclusive offers
2. **At Risk Customers**: 99 customers showing declining engagement - immediate re-engagement campaigns needed
3. **Lost Customers**: Only 11 customers completely lost - manageable churn rate
4. **Loyal Base**: 119 loyal customers provide stable revenue foundation

### RFM Metrics Analysis
1. **Improved Recency**: Average decreased by 16.9% to 167 days (customers buying more recently)
2. **Frequency Challenge**: Slight 1.1% decrease suggests need for repeat purchase incentives
3. **Monetary Stability**: Only 2.1% decrease in average spending - relatively stable
4. **Product Preferences**: Office Supplies dominate with 544 customers, indicating primary market focus

### Category Performance
1. **Office Supplies Leadership**: Highest customer count (544) - core business strength
2. **Furniture Opportunity**: 453 customers - solid secondary category
3. **Technology Niche**: 232 customers - potential growth area with higher margins

## Business Recommendations

### Customer Retention Strategies
1. **Champions Program**: Create loyalty rewards for top 126 Champions to maintain engagement
2. **Win-Back Campaign**: Target 99 At Risk customers with personalized offers and re-engagement emails
3. **Lost Customer Recovery**: Analyze 11 Lost customers to understand churn reasons and prevent future losses

### Revenue Growth Initiatives
1. **Cross-Selling**: Encourage Office Supplies customers to explore Furniture and Technology categories
2. **Frequency Boosters**: Implement subscription models or bulk purchase discounts to increase purchase frequency
3. **Big Spender Focus**: Develop premium product lines for 93 Big Spenders segment

### Operational Improvements
1. **Monthly Monitoring**: Continue tracking monthly trends to identify seasonal patterns
2. **Geographic Expansion**: Analyze city-level performance for market penetration opportunities
3. **Category Optimization**: Invest in marketing for Technology category to boost customer adoption

## Technical Highlights

- **Advanced DAX**: Time intelligence functions for YoY comparisons
- **Data Modeling**: Star schema with fact and dimension tables
- **Custom Segmentation**: Logic-based customer categorization
- **Performance Optimization**: Efficient measures for fast dashboard loading
- **Conditional Formatting**: Dynamic color coding based on performance indicators
- **User Experience**: Clean, dark-themed professional interface

## Skills Demonstrated

✅ RFM Analysis & Customer Segmentation  
✅ Power BI Dashboard Development  
✅ DAX Calculations & Measures  
✅ Data Visualization Best Practices  
✅ Business Intelligence & Analytics  
✅ KPI Development & Monitoring  
✅ Sales Analytics & Trend Analysis  
✅ Stakeholder Communication & Reporting  

## Future Enhancements

- **Predictive Analytics**: Machine learning models to predict customer churn
- **Cohort Analysis**: Track customer behavior over time periods
- **Real-Time Integration**: Connect to live sales database for current data
- **Customer Lifetime Value**: Calculate CLV for each segment
- **Automated Alerts**: Email notifications for at-risk customers
- **Multi-Year Analysis**: Historical trend comparison across years
- **Geographic Heat Maps**: Visual representation of sales by location

## Use Cases

This RFM analysis framework can be applied to:
- **E-commerce platforms** for customer retention strategies
- **Retail businesses** for inventory and promotion planning
- **SaaS companies** for subscription management
- **B2B enterprises** for account prioritization
- **Marketing teams** for campaign targeting and personalization

## Author

[LOKESH C]  
[lokeshlokeshc007@gmail.com]  
[LinkedIn Profile]  
[GitHub Profile]  
[Portfolio Website]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Project Category:** Sales Analytics | Customer Segmentation | Business Intelligence  
**Domain:** Retail Analytics | CRM | Marketing Analytics  
**Status:** Completed  
**Dashboard Type:** Single-Page Executive Dashboard

**Note:** This project demonstrates practical application of RFM analysis for customer segmentation and sales performance monitoring, providing actionable insights for data-driven business decisions.
