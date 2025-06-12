# E-Commerce-Olist-Store
**INTRODUCTION**
Olist Store is a leading Brazilian e-commerce platform that connects small and medium-sized businesses with customers. It enables merchants to list their products and services across various marketplaces while efficiently managing their sales operations.

This Analysis Aims to: 1.Explore the company's product volume, sales, and customer satisfaction rating for products.
                       2. Analyze delivery performance.
                       3. Investigate product ratings and discover product categories that are prone to customer dissatisfaction.
                       4. To analyze the preferred mode of payment used by customers.

**DATA OVERVIEW**
The given dataset consists of 100k e-commerce orders from 2016 to 2018, structured across 9 CSV files. These files allow us to analyze various aspects of the business, including:

   1.Order Status – Track the journey of orders from placement to fulfillment
   2.Pricing & Payments – Understand pricing strategies and preferred payment methods
   3.Freight & Delivery – Analyze shipping costs and delivery times
   4.Customer Insights – Explore customer locations, behaviors, and feedback
   5.Seller Performance – Assess marketplace dynamics and seller contributions

By leveraging this dataset, we can extract valuable insights to enhance decision-making, improve operational efficiency, and optimize customer experience.

**KPIs**
    1.Weekday Vs Weekend (order purchase timestamp) Payment Statistics
    2.Number of Orders with review score 5 and payment type as credit card.
    3.Average number of days taken for order delivered customer date for pet shop
    4.Average price and payment values from customers of sao paulo city
    5.Relationship between shipping days (order delivered customer date – order purchase timestamp) Vs review scores.

**KPI-1:Weekday Vs Weekend Payment**
    Payment data based on transactions occurring on weekdays vs. weekends.
    Key Insights:
                a. Higher Transactions on Weekdays – Customers tend to shop more during the workweek.
                b. Lower Weekend Sales – Fewer purchases and lower payment value on weekends.
    Payment Distribution:
                Weekdays: $12.40M (77.44%)
                Weekends: $3.61M (22.56%)
    Conclusion : Customers are significantly more active on weekdays than weekends, indicating that marketing and promotional strategies should focus                  on weekday engagement.

**KPI 2: Orders By Review Score 5 And Payment Type **
    This analysis focuses on orders with a review score of 5 and the preferred mode of payment.
    Key Insights:
                1.Credit Card Dominates – The majority of customers prefer using credit cards.
                2.Boleto is the Second Choice – A significant portion still opts for boleto (bank slip).
                3.Lower Preference for Debit Cards & Vouchers – Limited adoption compared to other payment methods.
    Payment Method Breakdown:
                1.Credit Card: 74.62% (45,170 orders)
                2.Boleto: 18.99% (11,495 orders)
                3.Voucher: 4.82% (2,915 orders)
                4.Debit Card: 1.57% (950 orders)
                5.Average Review Score: 4.0
    Conclusion: Customers who give high ratings (5 stars) predominantly use credit cards, indicating a smoother payment experience. Strategies can be                 developed to enhance adoption of other payment methods.

**KPI 3: Average order delivery days for pet shop**
    We analyzed the average shipping time for different product categories, focusing on Pet Shop orders.
    Shipping Time Breakdown by Category:
               Pet Shop: 11 days (average delivery time)
               Furniture Bedroom: 14 days
               Electronics: 13 days
               Overall Average: 13 days
    Conclusion:
               The Pet Shop category has the fastest delivery time, taking 11 days on average, which is below the overall average. In comparison,                    categories like Furniture Bedroom and Electronics take longer to deliver.

**KPI 4:Average Payment value and average price for Sao Paulo**
    This KPI focuses on the analysis of the average payment value and average product price for Sao Paulo City.
    Key Metrics:
               Average Payment Value: 135.04
               Average Price: 107.53
               Customer Base in Sao Paulo: 16,337 customers
    Conclusion:
               Both total price and payment values in Sao Paulo have seen a significant increase over the years, indicating growing customer                         engagement and higher transaction volumes.

**KPI 5:Relationship between shipping days vs review score**
    This KPI analyzes the relationship between shipping days and review scores given by customers.
    Key Metrics:
               Average Estimated Shipping Days: 24 days
               Average Shipping Days: 13 days
               Average Review Score: 4
    Key Insights:
               Shorter Shipping Days = Higher Review Scores
               Highest Review Score (5): Orders shipped within 11 days
               Lowest Review Score (1): Orders shipped within 20 days
   Conclusion:
              Customers tend to rate products lower when shipping times are longer, emphasizing the importance of timely delivery for higher customer               satisfaction.

**Recommendations & Insights**
   1.Sales Trends: Weekday sales outperform weekend sales, indicating an opportunity to boost weekend engagement through targeted promotions,                            discounts, and advertising campaigns.
   2.Payment Preferences: Credit cards dominate as the preferred payment method (74.62%). To drive adoption of other payment methods, Olist Store can                    introduce exclusive discounts and offers.
   3.Delivery Impact on Reviews: The average delivery time is 13 days, while the estimated delivery time is 24 days—a factor influencing customer                        review scores. Optimizing logistics can enhance customer satisfaction.
   4.Seller Growth: A steady rise in sellers, from 130 in 2016 to 1.7K in 2017 and 2.3K in 2018, highlights a growing marketplace.
   5.Top Revenue City: Sao Paulo leads in payments, aligning with its status as Brazil’s most populated city, reinforcing its strategic importance                       for sales and marketing efforts.

**Conclusion**
              In conclusion, the Olist Store analytics project provided valuable insights into the performance of the company’s Various branches and               account executives. Through the use of Excel, Power BI, Tableau and SQL we were able to Develop a comprehensive branch dashboard that                allowed us to identify key areas for improvement.









