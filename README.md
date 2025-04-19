# Project Background

**MercadoNova**, founded in 2016, is a rapidly growing Brazilian e-commerce platform that offers a wide range of consumer products — from electronics and home goods to fashion and food — serving customers across the country through its online store and mobile app.

Over the years, MercadoNova has accumulated substantial data on customer reviews, sales performance, product categories, seller activity, and delivery logistics. While this data holds tremendous potential, it has been underutilized in driving strategic decisions. This project aims to unlock that potential by analyzing key metrics that directly influence customer satisfaction and business performance.

The objective of this project is to generate actionable insights across three critical areas: **sales trends**, **delivery time performance**, and **customer satisfaction**, as measured by review scores.

Insights and recommendations are provided across the following key areas:

- **Sales Trends Analysis**: Exploration of product sales, revenue growth, and regional performance trends over time, with a focus on top-performing categories and customer behavior by region.
- **Delivery Time Evaluation**: Analysis of delivery speed by region and product category, identifying patterns of delays and areas for operational improvement.
- **Customer Satisfaction Drivers**: Examination of customer review scores in relation to delivery speed, product types, and seller performance to determine key satisfaction and dissatisfaction points.

# Data Structure

MercadoNova's database structure as seen below is composed of **eight tables** with a total of **over 100,000 records**.

![Screenshot 2025-04-18 211152](https://github.com/user-attachments/assets/a9988db1-3366-4e88-9b66-c4f3bbe70e4b)

# Executive Summary

### Overview of Findings

MercadoNova’s transaction and customer data revealed three core performance trends across sales, delivery, and customer satisfaction. Revenue peaked in late 2017 and stabilized through 2018, with top-performing categories like Health & Beauty and Watches generating over **$1.2M each**, contributing more than **25% of total revenue**. Delivery performance varied widely—customers in northern states like RR and AP experienced delays of **27–29 days**, more than **3× the national average** of ~10 days. Additionally, review scores showed a strong correlation with both delivery speed and seller reliability; products delivered in under 10 days averaged **4.4 stars**, while delayed orders (21+ days) dropped to just **2.9 stars**. Top sellers like CasaNova Imports consistently received **5.0 star** ratings, compared to bottom-tier sellers averaging **2.2–3.0 stars**.

## Sales Trends:

- **MercadoNova's sales peaked in November 2017 with over $980,000 in monthly revenue.**  
  This represents a **128% increase** from the start of 2017, reflecting the strongest point of customer demand across all regions and categories. Health & Beauty and Watches & Gifts alone accounted for over **29%** of total revenue during this peak period.

- Beginning in December 2017, **monthly revenue fluctuated slightly but remained above the $850K average through mid-2018**. Despite some dips, performance stayed **35% higher** than the national monthly average of **$629K**, showing a healthy level of sustained demand.

- **SP and RJ states drove the highest regional revenue contributions**, together accounting for over **60%** of all sales during peak months. SP alone generated more than **45%** of monthly revenue at its highest point, more than triple the contribution of any other state. In contrast, states like GO, SC, and BA each contributed less than **5%**, indicating opportunities for regional expansion.

- **Top product categories maintained consistent revenue levels across the observed period.**  
  Health & Beauty, Watches & Gifts, and Bed & Bath were the most consistent revenue generators, combining for over **36%** of total sales. These categories also showed steady growth, with Health & Beauty increasing by **23%** from early 2017 to mid-2018.

![Screenshot 2025-04-18 222810](https://github.com/user-attachments/assets/9e9b487f-b74f-4dd7-a2df-137409798a50)

![Screenshot 2025-04-18 222907](https://github.com/user-attachments/assets/86ce8388-4c62-430f-a07b-9d1beccf4d07)


### Review Score Trends:

- **Review scores remain high for fast deliveries**, with an average rating of **4.4 out of 5** for orders delivered within **10 days**. However, scores begin to dip as delivery times increase — dropping to **4.1** for 16–20 day deliveries and sharply to **2.9** once delivery exceeds 21 days, a **34% decrease** from the fastest tier.

- **Products in Books and Flowers categories receive the highest customer ratings**, with top items averaging **4.37 to 4.45 stars**. These items consistently outperform the platform’s satisfaction benchmark of 4.0, suggesting strong alignment between expectations and product delivery for these segments.

- On the other hand, **Baby Essentials and Phone Accessories receive the lowest satisfaction**, with review scores falling between **3.26 and 3.68** — representing a **17%–26% drop** compared to top-rated categories. These lower scores could stem from quality concerns, longer delivery times, or mismatched expectations.

- **Seller performance plays a significant role in customer experience.** CasaNova Imports and Loja do Sul both maintained a perfect **5.0 average rating**, while Loja 360 sits at the bottom with a **2.2 average**, a dramatic **56% lower** than the top sellers. This gap highlights major inconsistencies in seller reliability and fulfillment standards.



![Screenshot 2025-04-18 224148](https://github.com/user-attachments/assets/6031e77b-5653-4f21-a440-73a85574c4e6)

![Screenshot 2025-04-18 224218](https://github.com/user-attachments/assets/bd0458dd-878c-4be1-b2c9-33a2b5ca3d0d)


### Delivery Trends:

- **Delivery delays are concentrated in Brazil’s Northern states**, with Roraima (RR), Amapá (AP), and Amazonas (AM) recording the longest average delivery times at 29.3, 27.2, and 26.4 days respectively. These figures are significantly higher than the national average of 18.7 days, highlighting major logistical challenges in these regions.

- **São Paulo (SP) outperforms all states in fulfillment speed**, delivering orders in just 8.7 days—**54% faster** than the national average. Other top-performing states include Paraná (11.9 days) and Minas Gerais (12.0 days), showcasing the efficiency of more developed regional infrastructure.

- **Product type also plays a major role in delivery time.** Office Furniture and Holiday Items face the slowest fulfillment speeds, averaging 20.8 and 15.7 days, respectively. These items exceed the national product delivery average of 14.7 days by as much as **41%**.

- On the other end of the spectrum, **books and essential goods are fulfilled much faster.** Imported Books are delivered in just 8.0 days, followed by Food & Groceries (9.5 days) and Construction Lights & Tools (9.7 days). These categories are fulfilled **32–46% faster** than average, likely due to lighter shipping weights and optimized supply chains.

![Screenshot 2025-04-18 230549](https://github.com/user-attachments/assets/c0dfde6b-06fd-49d0-9c1a-04229cf41639)

![Screenshot 2025-04-18 230626](https://github.com/user-attachments/assets/65dc5eb8-cdea-4cfa-a943-db49c1126999)


## Recommendations

Based on the uncovered insights across sales, delivery performance, and customer satisfaction, the following strategic recommendations are proposed:

- **Broaden marketing around high-performing categories.**  
  Health & Beauty and Watches & Gifts collectively generated over **$2.46M in revenue**, contributing more than **20% of total sales**. These categories also demonstrated steady month-over-month growth. Doubling down on targeted promotions and bundling offers in these segments can further drive revenue gains.

- **Improve service levels in northern states experiencing long delivery delays.**  
  States like **Roraima (RR)** and **Amapá (AP)** had the **highest delivery times**, averaging over **27 days**, compared to the **national average of 18.7 days**. Investing in better regional logistics partnerships or fulfillment centers could significantly improve customer satisfaction and reduce churn in underserved areas.

- **Consider pruning or re-evaluating low-rated product categories.**  
  Categories such as **Baby Essentials** and **Office Furniture** received review scores as low as **3.26**, which is **27% below** the satisfaction benchmark of 4.0. Introduce quality audits or customer feedback loops to address complaints and determine whether these products should remain in the catalog.

- **Incentivize and replicate top seller behavior.**  
  Sellers like **CasaNova Imports** and **Loja do Sul** maintained **perfect 5.0 ratings**, while others like **Loja 360** scored as low as **2.2**. Offer incentives for top sellers to expand their catalogs and provide onboarding support or training for low-performing sellers to improve service levels.

- **Optimize delivery time for high-volume product lines.**  
  **Office Furniture** averaged over **20.8 days in delivery**, nearly **42% longer than the national average**. In contrast, **Books and Kitchen Tools** shipped in under **10 days** and received the highest customer reviews. Shift fulfillment of slower product lines to more responsive logistics networks or offer expedited shipping options.
