# Restaurant-Orders-Data-Analysis

## 🍜 🍟 Food Ordering Platform Data Analysis in SQL
A food delivery platform UrbanEats wants to understand its business performance. The company had data pertaining to orders, customers, restaurants, meals, and monthly summary of its customers. However, they lacked clear insights on revenue, regional & category-wise restaurant performance and their customer's loyalty & ordering patterns.

Through this analysis, UrbanEats is provided with insights to help it:
1. Analyze the platform's performance
2. Identify popular regions, meals, and restaurant categories among customers
3. Detect loyal customers
4. Understand ordering (time, gender, behaviour) and restaurant pricing patterns
5. Evaluate whether customers are spending beyond target
6. Understand restaurants' performance

## Tech Stack
The analysis was performed in MySQL which was used to store data and execute queries.  

## Dataset Description
Data on ~36 k orders placed on a food delivery platform from 1st January 2020 to 1st July 2020 from Kaggle with details on orders, restaurants, customers and meals. Here is the dataset link: [Dataset Link](https://www.kaggle.com/datasets/vainero/restaurants-customers-orders-dataset/data)

## Highlights
* All the data files were loaded in a MySQL database.
* Build Data model to understand the relationship between different entities in the dataset.
* Performed exploratory and analytical SQL queries to generate insights.
* Applied Common Table Expressions (CTEs) to improve query readability and optimize complex queries.
* Used window functions to obtain advanced analytical insights.
  
## Key Business Insights
- Total revenue earned by platform over 6 months is 6.06 lakhs ILS, with monthly revenue around 1 lakh ILS on an average , showing slight increases in February and April and a dip in March.
- The restaurants having high order volumes are 13,30,18 and 20,making them key partners for the platform.
- Popular restaurant categories include Fast Food, Asian and Indian while cheese and vegan meals were preferred by most customers.
- Identified best-performing restaurants in each restaurant category which can help improve restaurant suggestions.
- As restaurants located in Herzelia and Ramat Hasharon are popular among customers for ordering food, the platform should optimize delivery operations in these cities.
- 20.5% customers contribute significantly to overall revenue earned by the platform, highlighting the importance of focusing on high-value users.
- Identified customers who place the most number of orders on a monthly basis. The platform can boost their earnings by offering appealing discount and coupons to such customers.
- Peak ordering hours were observed between 11 AM – 1 PM and 7 PM – 9 PM, close to lunch and dinner time,respectively. The platform can increase revenue by promoting breakfast and appetizer options during off-peak hours. 
- Males and Females place almost the same number of orders and prefer same restaurant categories and meal types. Some restaurants are popular across both genders
while others are preferred by specific gender. Gender-based preferences can help the platform recommend restaurants more effectively and plan targeted campaigns on weekends and other special occasions.
- Restaurants in Ramat Hasharon are more popular among women while those in Tel Aviv are more popular among men. Restaurants in Herzelia are preferred by both the genders. Upcoming restaurants can use these insights to decide on the ideal location of their restaurants. 
- Customer ordering behavior shows that, on an average, users order 2 meals per order, which can help the platform optimize delivery pricing strategies.
- Restaurants 3 & 28 are the economically friendly restaurants whereas 11,10 & 4 are the high end restaurants. This can help align recommendations with the customer's spending pattern.
- The average price per order is approximately 87 ILS. Vegan, cheese and beef meals are budget friendly options for customers and a chicken meal is the premium option. This gives the company an opportunity to suggest appropriate meals as per occasion and budget.
- Interestingly, only one customer exceeded their monthly budget. This indicates an opportunity for the platform to encourage higher spending through targeted marketing strategies,such as discounts.
- Restaurants 10,4,27,15 and 11 generate the highest payouts and hence, drive strong sales on the platform but also represent higher costs, so the platform should balance promoting these partners with maintaining healthy profit margins.

## Conclusion
This analysis has provided UrbanEats with data-driven insights that can help enhance customer satisfaction, optimize operations, and make strategic business decisions in relation to pricing, delivery, and recommendations, ultimately driving growth and profitability.

