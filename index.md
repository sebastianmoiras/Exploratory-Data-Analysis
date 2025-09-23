📊 Global Superstore Analysis

Project Description

This project explores the Global Superstore dataset to uncover insights on sales, profit, discounts, shipping costs, customer segments, product categories, and regional markets.

The main objective is to answer several Business Questions (BQ):
- How do discounts affect profit margins across categories?
- Which customer segments drive the most profit?
- Which global markets are most profitable?
- Which sub-categories are consistently loss-making?
- How do shipping costs relate to order value and profitability?

## Key Insights
### 1. 
![Discount vs Profit](/assets/EDA1.png)
- Discounts & Profitability: Discounts above 50% often result in negative profit, especially in the Furniture category.
### 2. 
![Customer Segments](/assets/EDA2.png)
![Customer Segments](/assets/EDA3.png)
- Customer Segments: Corporate customers generate higher profit margins per order compared to Consumer and Home Office segments.
### 3. 
![Regional](/assets/EDA4.png)
![Regional](/assets/EDA5.png)
![Regional](/assets/EDA6.png)
- Regional Markets: Canada achieves the highest profit margin (26.6%) despite smaller sales volume. EU, US, and APAC dominate in total sales and profit, maintaining ~12% margins. Africa, LATAM, and EMEA lag behind, with EMEA showing the weakest profitability at only 5.4%.
### 4. 
![Subcat](/assets/EDA7.png)
![Subcat](/assets/EDA8.png)
- Product Sub-Categories: Tables are consistently loss-making. Papers and Labels are the strongest profit drivers.
### 5. 
![Shipping](/assets/EDA9.png)
![Shipping](/assets/EDA10.png)
![Shipping](/assets/EDA11.png)
- Shipping Costs: Shipping costs strongly correlate with order sales values, but not always with profitability. Some high-cost shipments still generate losses, indicating inefficiencies.

## Techstack
- Python (Pandas, Numpy) – data cleaning & wrangling
- Matplotlib, Seaborn – data visualization
