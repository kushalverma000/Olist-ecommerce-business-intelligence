# Olist E-Commerce Business Intelligence

## Project Overview
End-to-end Business Intelligence solution built on the Olist E-Commerce dataset from Kaggle.
Transforms raw transactional data into actionable insights via a structured workflow: business understanding, data quality assessment, modelling, SQL analysis, and dashboarding.
Covers key marketplace areas: sales, customer behaviour, operational efficiency, seller & product performance, payments, and customer satisfaction.
Uses SQL Server for data preparation/analysis and Power BI for interactive visualizations.
Delivers strategic recommendations to support data-driven decision-making.
Simulates a real-world BI engagement, showcasing the full lifecycle from raw data to executive-level reporting.

## Business Problem
- E-commerce marketplaces produce vast transactional data on customers, orders, products, sellers, payments, deliveries, and reviews.  
- Organizations often struggle to turn this data into actionable insights for strategic decisions.  
- Competitive marketplaces need clear visibility into sales performance, customer behaviour, operational efficiency, seller/product contributions, payment trends, and satisfaction.  
- Without structured analysis, growth opportunities, bottlenecks, and experience issues remain hard to identify.  
- This project implements a full BI workflow—data quality assessment, SQL analysis, and Power BI dashboards—to convert raw data into meaningful insights.  
- Stakeholders can monitor KPIs, evaluate performance, and make informed, data-driven decisions.

## Project Objectives

The primary objective of this project was to develop a comprehensive Business Intelligence solution that transforms raw e-commerce data into actionable business insights using industry-standard analytics 
practices.

The project was designed to achieve the following objectives:

- Assess and improve data quality to ensure analytical accuracy and reliability.
- Design a structured analytical framework by defining fact tables, dimensions, and business measures.
- Analyze marketplace performance across sales, customers, operations, sellers, products, payments, and customer satisfaction.
- Identify business trends, performance drivers, operational inefficiencies, and growth opportunities through SQL-based analysis.
- Develop interactive Power BI dashboards to monitor key performance indicators and support executive decision-making.
- Generate strategic business recommendations based on analytical findings to improve marketplace performance.
- Demonstrate the complete end-to-end Business Intelligence lifecycle, from business understanding and data preparation to visualization and business reporting.

## Dataset Information
- Project Utilizes the Olist Brazilian E-Commerce Public Dataset from Kaggle, covering 2016–2018 marketplace transactions.
- Captures the full order lifecycle: purchases, payments, deliveries, and customer reviews.
- Includes multiple relational tables for customers, orders, items, products, sellers, payments, reviews, geolocation, and category translations.
- Provides a comprehensive view of marketplace operations across key business functions.
- Data was imported into Microsoft SQL Server for quality assessment, modelling, and analysis.
- Processed data powers interactive Power BI dashboards with visualizations and KPIs for stakeholders.

### Dataset Summary
 - Dataset :  Olist Brazilian E-Commerce Public Dataset 
 - Source :  Kaggle 
 - Domain :  E-Commerce Marketplace 
 - Time Period :  2016 – 2018 
 - Database :  Microsoft SQL Server 
 - Visualization Tool :  Microsoft Power BI 
 - Number of Tables :  9 
 - Analysis Scope :  Sales, Customers, Operations, Sellers, Products, Payments, Customer Satisfaction

## Technology Stack

The project was developed using industry-standard Business Intelligence and data analytics tools, with each technology serving a specific role throughout the 
analytical workflow.

- Microsoft SQL Server: Database management, data preparation, modelling, aggregation, business analysis, and reusable views.
- Power BI: Interactive dashboard development, KPI visualization, and executive reporting.
- Microsoft Excel: Initial dataset exploration and validation.
- Microsoft Word: Project documentation and business reporting.
- Chat GPT: Documentation assistance and grammar checking for the report.

## Project Workflow

The project followed a structured end-to-end Business Intelligence workflow, simulating the lifecycle of a real-world BI engagement. Each phase was completed sequentially to ensure data accuracy,
analytical consistency, and business relevance.

```text
Business Understanding
        │
        ▼
Analytical Feasibility Assessment
        │
        ▼
Data Preparation & Change Log
        │
        ▼
Data Quality Assessment
        │
        ▼
Data Modelling
(Fact Tables, Dimensions & Measures)
        │
        ▼
SQL-Based Business Analysis
        │
        ▼
Business Insights & Strategic Recommendations
        │
        ▼
Power BI Dashboard Development
        │
        ▼
Executive Reporting
```

## Data Modelling

A structured dimensional modelling approach was adopted to support efficient business analysis and reporting. The analytical framework was designed by identifying business processes, 
defining the appropriate level of granularity, and establishing fact tables, dimensions, and business measures.

### Fact Tables
The analysis was built around four core fact tables representing the primary business transactions:

- **Orders** – Order lifecycle and status information.
- **Order Items** – Product-level sales transactions.
- **Order Payments** – Payment transactions and payment methods.
- **Order Reviews** – Customer review scores and feedback.

### Dimensions
The following dimensions were defined to enable multidimensional business analysis:

- **Customer**
- **Product**
- **Seller**
- **Date**
- **Order Status**

### Business Measures
Key business measures were identified and documented to evaluate marketplace performance, including:

- Total Revenue
- Total Orders
- Average Order Value (AOV)
- Average Delivery Time
- Customer Lifetime Metrics
- Review Score
- Payment Metrics
- Seller Performance Metrics

This dimensional model established a consistent analytical foundation for SQL-based business analysis and Power BI dashboard development, enabling efficient KPI calculation, trend analysis, 
and interactive reporting.


## Business Analysis Domains

The project evaluates marketplace performance through seven key business domains. Each domain addresses a specific set of business questions, supported by SQL-based analysis, key performance indicators (KPIs), 
business insights, and strategic recommendations.

- **Sales Performance Analysis**: Evaluated revenue trends, order volume, customer behaviour, average order value, and sales distribution.  
- **Customer Analysis**: Analysed acquisition, purchasing patterns, segmentation, repeat purchases, and customer value for retention/growth insights.  
- **Orders & Delivery Analysis**: Examined fulfilment, delivery performance, shipping efficiency, delays, and regional operations.  
- **Seller Analysis**: Assessed contribution, revenue generation, product sales, and overall seller performance.  
- **Product Analysis**: Evaluated categories, demand, revenue contribution, pricing, and portfolio performance.  
- **Payment & Customer Experience Analysis**: Analysed payment methods, instalments, preferences, review scores, and satisfaction drivers linked to delivery.


### Business Analysis Coverage
The analytical framework addressed key business questions across the following areas:

- Revenue and sales performance
- Customer behaviour and retention
- Marketplace operations and logistics
- Seller performance evaluation
- Product portfolio analysis
- Payment behaviour and transaction trends
- Customer satisfaction and service quality

Together, these analytical domains provide a comprehensive understanding of marketplace performance, enabling the identification of business opportunities, operational challenges, and 
data-driven strategies for sustainable growth.


## Power BI Dashboard

The analytical findings were transformed into an interactive Power BI report designed to support executive decision-making. The dashboard suite provides a comprehensive view of marketplace 
performance through interactive visualizations, KPI cards, trend analyses, and business-focused metrics.
The report follows a consistent dark-themed executive design with intuitive navigation, enabling stakeholders to monitor performance across multiple business functions.

### Dashboard Preview

#### Executive Overview
<img width="1287" height="721" alt="Executive Overview" src="https://github.com/user-attachments/assets/e51e4ac9-d8cc-42f8-a600-44e8e1c273a4" />

#### Sales Performance Analytics
<img width="1287" height="720" alt="Sales Performance Analytics " src="https://github.com/user-attachments/assets/06da7fab-d87a-4b3f-ae45-55201a68fa52" />


#### Customer Analytics
<img width="1285" height="720" alt="Customer Analysis" src="https://github.com/user-attachments/assets/ded3fae2-6a06-47e1-8de6-9cd00797e831" />

#### Operational Analytics

<img width="1285" height="701" alt="Operational Analytics " src="https://github.com/user-attachments/assets/f49c6ee8-3f95-4f3f-9232-1e8e07e7958a" />

#### Seller & Product Analytics

<img width="1277" height="712" alt="Seller   Product  Analytics" src="https://github.com/user-attachments/assets/2758723c-911d-42c7-840f-ebec0c71fa72" />

#### Customer Experience Analytics
<img width="1285" height="720" alt="Customer Analysis" src="https://github.com/user-attachments/assets/76507495-a68a-4d6e-8c3d-250e89823568" />

### Dashboard Features

- Interactive slicers for dynamic data exploration
- Executive KPI cards for performance monitoring
- Trend analysis across multiple business dimensions
- Comparative business performance visualizations
- Consistent dashboard layout and navigation
- Professional dark-themed executive design


## Key Business Insights

The analysis uncovered several important insights into Olist's marketplace performance, customer behaviour, operational efficiency, and overall business health.

- Marketplace revenue grew steadily, driven mainly by higher order volume and an expanding customer base rather than rising Average Order Value.  
- A small group of customers generated a large share of total revenue, underscoring the need for strong retention and loyalty programs.  
- Delivery delays directly lowered customer review scores, linking operational performance to satisfaction.  
- Performance varied significantly across Brazilian states in demand, delivery efficiency, and satisfaction levels.  
- Sales were concentrated in a few product categories and top sellers, highlighting diversification opportunities.  
- Clear customer preferences for certain payment methods, combined with overall findings, show that sustainable growth requires balancing revenue, operations, and customer experience.

## Strategic Recommendations

Based on the analytical findings, the following strategic recommendations are proposed to enhance marketplace performance, improve customer experience, and support long-term business growth.

- **Strengthen Customer Retention**: Launch loyalty programs, personalized campaigns, and targeted promotions to boost repeat purchases and lifetime value.  
- **Improve Delivery Performance**: Optimize logistics, reduce delays, and monitor shipping to raise satisfaction and operational efficiency.  
- **Support Seller Development**: Offer performance insights, guidance, and incentives to help underperforming sellers improve.  
- **Expand High-Potential Categories**: Invest in strong-demand products while diversifying the portfolio to reduce revenue concentration.  
- **Enhance Customer Experience**: Monitor feedback, fix recurring issues, and prioritize changes that lift review scores and loyalty.  
- **Drive Sustainable Growth**: Use interactive dashboards for ongoing KPI monitoring and balance revenue with operations, sellers, and satisfaction.
