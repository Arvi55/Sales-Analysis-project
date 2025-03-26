# Sales-Analysis-project


# Project Background

Atliq hardware is a company which supplies computer hardware and peripheral manufacturer.

The company has significant amounts of Data on its sales, Transactions,Customer,Products, Market and Date that has been underutilized. This project throughly analyzes and synthesizes this data in order to uncover insights that will improve Atliq hardware success.

Insights and recommendation are provided on the following key areas:

- **Revenue Trends Anaysis**: Evalution of historical sales patterns,both region and year wise focusing on sales.
- **Product level performance**: An analysis of Atliq hardware various Products, understanding their impact on sales and returns.
- **Customer balancing**: Analysis of dependency on percentage of top customer.
- **Sales vs Revenue**: Evalution of sales and revenue by region.

# Data Structure & Initial Checks

 Atliq database structure as seen below consist of five tables :
     **Products, Customers, transactions, markets, date**
with a total row count of 150,283 records.

![App Screenshot](https://github.com/Arvi55/Sales-Analysis-project/blob/main/ERD%20diagram.png?raw=true)

# Executive Summary


**Overview of Findings**

After peaking in early 2018, the company's sales have continued to decline, with significant drop in 2022. key performance indicator have all shown year-over-year decrease: order sales by 58.67% and revenue by 57.67%.This decline is most likely due to the impact of the pandemic. The following section will explore additional contributing factors and highlight key opportunity areas for improvement.

Below is the overview page from the PowerBI dashboard.

![App Screenshot](https://github.com/Arvi55/Sales-Analysis-project/blob/main/dashboard_preview.png?raw=true)



**Sales Trends:**
   - The company's sales peaked in May 2018 with 92525 sales totalling ₹3,21,88,350 monthly revenue. 
   - Beginning in April 2019, revenue declined on a year-over-year basis , revenue hits a company lifetime low in june 2020, with the company earning just over ₹14.71M.
   - In all the years more than 90% sales come from top 5 region like Delhi NCR,Mumbai,Ahemdabad,Bhopal,Nagpur.It can be due to high IT hardware usage in these area.

   ![App Screenshot](https://github.com/Arvi55/Sales-Analysis-project/blob/main/sales_overview.png?raw=true)

**Revenue Trends**
  - The company's Revenue peaked in january 2018 with totalling ₹4,25,20,492 monthly revenue. 
   - from january 2018 revenue declining was started and continued till may 2018 after that a slight recovery for months and once again started to decline.

  - In all the years more than 90% Revenue come from top 5 region like Delhi NCR,Mumbai,Ahemdabad,Bhopal,Nagpur.It can be due to high IT hardware usage in these area.

   ![App Screenshot](https://github.com/Arvi55/Sales-Analysis-project/blob/main/sales_overview.png?raw=true)


**Sales VS revenue**

An analysis of the dashboard data reveals that sales volume and revenue do not have a direct correlation. Sales peaked in May 2018 with a volume of 92,525 and revenue of ₹32.18 million, whereas revenue peaked in January 2018 at ₹42.52 million, despite a lower sales volume of 87,873. This indicates that factors such as pricing strategies, discounts, or product mix may be influencing revenue fluctuations.

![Alt1](https://github.com/Arvi55/Sales-Analysis-project/blob/main/sales.png?raw=true) 

 ![Alt2](https://github.com/Arvi55/Sales-Analysis-project/blob/main/revenue.png?raw=true)

 **Customer balancing** 


 - A customer-wise analysis reveals that ElectricalSara Store accounts for 32.7% of total sales, with a volume of 654K, while contributing a significant 42% of total revenue, amounting to ₹413.33 million. This indicates that despite representing nearly one-third of the sales volume, the store's revenue share is disproportionately higher, suggesting a higher average selling price or premium product mix.

 - Sales analysis shows a heavy reliance on ElectricalSara Store, contributing 32.7% of sales (654K) and 42% of revenue (₹413.33M). In contrast, the second-highest buyer, ElectricalSlytical Store, accounts for only 79K sales and ₹49.64M revenue, highlighting an imbalance and dependency risk.

 ![Alt1](https://github.com/Arvi55/Sales-Analysis-project/blob/main/1st%20product.png?raw=true) 

 ![Alt2](https://github.com/Arvi55/Sales-Analysis-project/blob/main/2nd%20product.png?raw=true)

 **Region Decoding**

 - Region-wise analysis shows that Delhi NCR dominates sales and revenue, generating ₹519.58M (52.75% of total revenue) with 988K sales (49.4% of total sales). This highlights a strong regional concentration, indicating potential opportunities or risks in market dependency

 - The top 5 regions (Delhi NCR, Mumbai, Ahmedabad, Bhopal, and Nagpur) collectively generate ₹915.61M, contributing 92.96% of total revenue. This significant concentration suggests a heavy reliance on a few key markets, posing both growth opportunities and potential risks.

![Alt1](https://github.com/Arvi55/Sales-Analysis-project/blob/main/Delhi%20NCR%20data.png?raw=true) 

 ![Alt2](https://github.com/Arvi55/Sales-Analysis-project/blob/main/top%205%20region.png?raw=true)

 **Recommendations**

 - **Diversify Customer Base:** With ElectricalSara Store contributing 32.7% of total sales and 42% of revenue, there's a high dependency on a single customer. Expanding to new B2B clients or increasing retail sales can mitigate risk and improve revenue stability.

 - **Expand Sales in Underperforming Regions:** 92.96% of revenue comes from just five regions (Delhi NCR, Mumbai, Ahmedabad, Bhopal, and Nagpur). Focusing on untapped regions with strategic marketing and distributor partnerships can reduce reliance on a few key markets.

 - **Optimize High-Value Customer Retention Strategies:** The revenue-to-sales ratio suggests that some customers, like ElectricalSara Store, purchase high-margin products. Implementing exclusive discounts, priority service, or loyalty incentives can strengthen these relationships and boost long-term revenue.

- **Adjust Product Pricing or Bundling Strategy:** The disparity between sales and revenue peaks (May 2018 for sales vs. Jan 2018 for revenue) indicates that higher-priced products drive more revenue. A well-structured pricing strategy, bundled offerings, or seasonal discounts could align sales volume with revenue growth.

- **Re-evaluate Low-Performing Products:** The bottom 5 products (Prod247, Prod154, Prod181, Prod115, and Prod111) contribute less than 1% of total revenue, indicating poor market demand. Consider discontinuing these products, bundling them with popular items, or implementing targeted promotions to clear inventory and improve profitability.








