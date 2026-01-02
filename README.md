# 2019 Electronic Devices Sales Analysis using Pandas
![Python_Matplotlib](https://img.shields.io/badge/Python-Matplotlib-brightgreen)
![Python_Pandas](https://img.shields.io/badge/Python-Pandas-purple)

### Project Overview
Techex is a U.S.-based consumer electronics and home appliances retailer operating on a direct-to-customer sales model. It sells a mix of high-value electronics (laptops, monitors), home appliances, and everyday accessories through centralized order processing and fulfillment. 
Revenue is generated through individual product sales, with pricing varying by product category. 

This analysis explores 5 high level business questions to surface insights on product sales performance in 2019 for Sales and Marketing teams:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

### Dataset Description
The database captures 12 months worth of transactional sales data at the order level. The consolidated dataset contains hundreds of thousands of order entries broken down by order identifiers, product details, quantities, unit prices, purchase timestamps, and customer purchase addresses.

Data cleaning process was carried out to prepare the dataset for analysis, this includes:
- Drop NaN and static values from Dataframe
- Change column to appropriate data type for applying analysis (to_numeric, to_datetime, as type)
  
### Analysis: [Sales Analysis](Sales_Analysis.ipynb)
- **Peak Sales Period**
  - December 2019 recorded the highest overall sales, likely driven by holiday demand and year-end promotions.
![Sales Month](https://github.com/user-attachments/assets/03b9dd66-0869-4b88-8bf2-2f7427828cf6)

- **Top-Performing City**
  - **San Francisco** leads sales performance across the 10 operating cities.
  - Contributing factors may include a high concentration of tech professionals, stronger purchasing power, and greater demand for electronic devices.
![City](https://github.com/user-attachments/assets/b8f48325-f33c-4851-ab6b-48540400851b)

- **Customer Purchase Timing**
  - Highest website purchase activity occurs at **12:00 PM** and **7:00 PM**.
  - These time windows represent peak customer engagement and buying intent.
![Hour](https://github.com/user-attachments/assets/a82a23bc-905c-45d9-9da1-2897927a4815)

- **Product Bundling Behavior**
  - The top 3 most frequently purchased product combinations are:
    1. iPhone + Lightning Charging Cable  
    2. Google Phone + USB Charging Cable  
    3. iPhone + Wireless Headphones  

- **Standalone Product Performance**
  - **AAA Batteries (4-pack)** is the highest-selling single product.
![High_Sales_Product](https://github.com/user-attachments/assets/0e673991-14eb-4b6d-816e-b069c9464924)
![Sales_Quantity_vs_Price](https://github.com/user-attachments/assets/af3001da-3e6a-4e18-9b7f-e1d7449a520e)

  - Lower-priced items (batteries, charging cables, wired headphones) show significantly higher sales volume.
  - Higher-priced items (MacBook Pro Laptop, LG Dryer, LG Washing Machine) sell less frequently, indicating price sensitivity plays a role—though it is not the sole driver of sales performance.

#### Recommendations for Sales & Marketing team:
- **Seasonal Strategy**
  - Increase marketing spend, promotions, and inventory planning ahead of December to capitalize on peak seasonal demand.

- **High performed City Target Campaigns**
  - Prioritize San Francisco with tailored campaigns, premium product messaging, and early access promotions.
  - Replicate successful San Francisco strategies in other tech-focused metropolitan areas.

- **Ad Scheduling Optimization**
  - Run digital advertisements shortly **before peak buying hours**:
    - Morning push at **11:00 AM**
    - Evening push at **6:00 PM**
  - This increases visibility during high-intent purchase windows.

- **Bundling & Cross-Selling**
  - Actively promote proven product bundles (phones + accessories) with small discounts to increase average order value.
  - Highlight “Frequently Bought Together” recommendations at checkout.

- **Pricing & Product Mix**
  - Use low-cost, high-volume items as traffic drivers.
  - Bundle accessories with higher-priced products to improve conversion rates and perceived value.

### Acknowledgements
This project is based on concepts learned from a Pandas Data Science Tasks tutorial by **Keith Galli** on YouTube. The tutorial served as a foundation for understanding and applying Python Pandas and Matplotlib. This repository reflects my personal learning and experimentation.

### Find me at:
Minh Nguyen — Business Intelligence Analyst |
Linkedin: www.linkedin.com/in/minh-n-nguyen | Email: mim.n.nguyen@gmail.com
