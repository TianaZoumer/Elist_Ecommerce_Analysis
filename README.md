# Elist Evolution: The Role of Seasonality, Loyalty and Purchase Platforms in Performance Improvement

In order to draw insights for the next best steps, the dataset was scrutinized using conditional formatting, aggregate functions, Pivot Tables, and statistical analysis. Utilizing the granularity of individual order data from 2019-2022, including total sales, average order count, and count of sales, and determining the success of our seasonal and regional product-offerings, loyalty programs and purchase platforms, we gain perspective on the historical alignment of customer drives with company practices and design the success of future initiatives.

### **Cleaning:**

The raw data, 108,128 order values, was subjected to rigorous cleaning and optimization processes:

- Created new fields like 'Month' and 'Year' from order date for granular analysis.
- Isolated order country code to derive a new 'Region' field.
- Detected and removed duplicate orders (15,197 in number, amounting to 14% of the total).
- Eliminated entries with blank fields (167 in number, 0.001% of the total). 
- Ensured consistency in product names

Post cleaning, working Dataset: 92,763 unique order values.

### **KEY INSIGHTS**

### **Yearly Trends:**

- **2020 saw a 163% increase in total sales**, largely due to an **increase in order count (101%) and a 31% increase in average order value(AOV)**. This reflects the pandemic-uptick of online shopping and our success in meeting market needs.

- The **AOV decreased in both 2021 and 2022**. This suggests that while the business might have reached more customers, customers were spending less on each order. 

- **2022 showed a 46% decline in sales, a 10% drop in AOV, and a 40% drop in order count** compared to 2021. This shows we have failed to pivot with the current market trends.

![yearly_trends](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/c55b11d1-ce1a-4416-9fbf-1dbb7f380a30)
### **Seasonality:**

- The highest total sales occur at the end of the year, specifically in November and December. **In 2021 and 2022, sales in November and December were averaging 20% higher** on total sales and order count. The beginning of the year shows a trend of decreased sales, with significant drops in total sales observed in **January and February, representing an average of 30% decreased order count and sales total.**

- The **AOV growth rate spikes up to 13% in January and February 2020** which could be reflective of post-holiday sales, possibly coinciding with growing pandemic-concerns. There’s another **significant 18% spike in AOV in September 2022**, suggesting a successful end-of-summer sales campaign.

- **October is the lowest performing month averaging a 30% drop** in total sales and order count across all years.

![seasonality1](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/6793c8fa-c11c-4251-8146-00e67a6d426f)
![seasonality2](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/2666e0a0-eb39-48cd-8431-18dbf82e3c22)
### **Regionality**

- **North America (NA) is the largest (52%) in terms of total sales and order count across all years**, and it shows a significant growth rate in 2020. However, **the region has seen declining sales, AOV, and order count in 2021 and 2022**, which indicates a need for targeted strategies to maintain its market share.

- The Europe, Middle East, and Africa (EMEA) region is the **second largest (29%)** and shows a significant boost in 2020, but like NA, it sees a decline in the following years. However, **the decrease is less severe than in NA**, which might indicate more consistent demand in EMEA.

- The Asia Pacific (APAC) region, the **third largest (13%)**, has a higher AOV compared to other regions for all years except 2019, indicating that **customers in this region tend to purchase more expensive items**. 

- The Latin America (LATAM) region, the **smallest at (6%)**, while having the smallest total sales and order count, shows strong growth rates in 2020. However, **the region has a significant decrease in AOV, sales, and order count in 2022, more so than the other regions**.

![Regionality](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/81b235dd-b651-445a-b06d-effbe11fefbc)
### **Products:**

- Top: The 27in 4K gaming monitor, Apple Airpods Headphones, and Macbook Air Laptop consistently **contribute to over 80% of total sales from 2019 to 2022**, indicating their significant impact on the business's total performance.

- Bottom: The Apple iPhone, despite its high AOV, contributes minimally to the total sales (**1% in each year**), reflecting its limited impact on overall sales performance. The Bose Soundsport Headphones and Samsung Charging Cable Pack also contribute minimally to total sales. Despite the high sales volume of the Samsung Charging Cable Pack due to its lower price point, it still **only accounts for 1-2% of the total sales**.

![products](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/89f178b2-6756-4621-a556-e92a09d91353)
### **Loyalty Program:**

- The non-loyalty members have significantly led sales in 2019 and 2020, but **the gap between the two groups has been decreasing over time, from $3,037,163 in 2019 to a mere $478,742 in 2022 with loyalty members accounting for the largest impact**. Loyalty members account for higher total sales in 2021 and 2022.

- The AOV for non-loyalty members has been decreasing since 2020, while it has been increasing for loyalty members whose AOV took the lead in 2021. In 2022 they **spent $31 more on average than non-loyalty members** even including their discounts.

- The count of sales for non-loyalty members was significantly higher than that for loyalty members in 2019 and 2020. However, this gap has been closing over the years, with **the count of sales for loyalty members surpassing that for non-loyalty members in 2021 and 2022**.

![loyalty_program](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/a311bec4-962f-41e6-84f2-5eea802ed6b0)
### **Purchase Platform**

- The website accounts for **97% of total sales each year.** This purchasing trend is consistent across all regions, indicating its success in marketing higher value products.

- The AOV for the website has been increasing over the years from **$237 in 2019 to $294 in 2022**. On the other hand, the AOV for the mobile app has been decreasing significantly over the years, from **$111 in 2019 to just $36 in 2022**.

- Although the website dominates in terms of total sales and AOV, **the proportion of sales coming from the mobile app has been increasing over the years, from only 6% in 2019 to 24% in 2021 25% in 2022.**

![purchase_platform](https://github.com/TianaZoumer/Elist_Ecommerce_Analysis/assets/115896875/002b5fe9-0405-4cef-a2a7-f9c80535cf81)
### **MARKETING STRATEGIES:**

**Seasonality-Based Campaigns**: Capitalize on high-sales periods like Q4 and specifically the holiday season in November and December for targeted marketing campaigns. Given these periods drive the highest sales, marketing efforts should be ramped up to maximize revenue. For off-peak seasons, offer special deals, discounts, or bundled packages, which, optionally, could coincide with off-loading inventory that doesn’t perform as well.

**Loyalty Program Expansion**: The loyalty program shows significant growth and contributes to higher sales, AOV and order count. Consider developing targeted marketing campaigns that encourage more customers to join the loyalty program with ease of process and exclusive and consistent rewards.

**Focus on High-Performing Products**: Leverage the popularity of the top 3 products: 27in 4K gaming monitor, Apple Airpods Headphones, and Macbook Air Laptop. Develop specific marketing campaigns around these products, which consistently make up over 80% of total sales.

**Mobile App Promotions**: Given the growth in sales through the mobile app, consider mobile-specific promotions or app-exclusive deals to encourage higher order value and frequency of purchase. 

### **FURTHER RESEARCH:**

**Investigate Low AOV on Mobile App:**: Despite an increasing proportion of sales, the mobile app has a significantly lower AOV compared to the website. Research should be conducted to understand why customers prefer certain platforms for purchase and how this influences their buying behavior, which can guide improvements in the user experience across platforms.

**Product-Specific Research:** The bottom three products vary in sales but consistently include the Apple iPhone and Bose Soundsport Headphones. It would be beneficial to understand why these products underperform and whether it would be beneficial to discontinue this offering and off-load in an off-season sale.

**Loyalty Program:** While the loyalty program shows growth, research should be conducted to identify ways to increase the loyalty-members, who are leading our customer base and also ways to improve loyalty-member purchasing habits in down-turn months. Research the impact of offering additional loyalty program options and/or perks to target specific platforms, regions and products with exclusive discounts.

**Regional Sales:** With sales growth decreasing across all regions and most severely in the APAC region, it's important to investigate the reasons behind these trends and identify possible solutions. Broader understanding of regional purchasing trends in the market are needed.

**Evaluate Seasonality:**: Further research on the factors contributing to the seasonality in sales could provide valuable insights for future planning, including inventory management and marketing initiatives. Understanding the purchasing habits of our customers and the purchasing habits in the market at large will influence how we can meet customer needs and be competative in the market.
