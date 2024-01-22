# Supermarket Sales Analysis

## Introduction

In this project we will take a look at the sales data of the company between Janaury - March of 2019 to find patterns, trends and oppertunities that can help in the decision making process to imporove our branches performance.

## The required tasks

1) **Customer Demographics:** What is the gender distribution among customers, and does it impact the choice of product line?
 
2) **Branch Performance:** How do sales and customer types differ across the three branches of the business?

3) **Product Line Analysis:** Which product line generates the highest total sales and gross income?

4) **Pricing Strategy:** Are there any correlations between unit price, quantity, and customer ratings? Can this information be used to adjust pricing strategies?

5) **Payment Methods:** What are the preferred payment methods among customers, and do they vary by branch?

6) **Time Analysis:** Are there specific months, times of the day or days of the week when sales tend to peak or dip??

7) **Customer Loyalty:** Do certain customer types tend to generate more sales, and are they more satisfied with their shopping experience?

8) **City Comparison:** Are there significant differences in Quantity sold, customer ratings, or product preferences between cities??

## Data cleaning and preparatrion

After cleaning, preparing and understanding the data found the following notes

1) The dataset includes 1000 records.
2) No missing values were found.
3) The dataset contains 17 features.
4) New columns were added **Day, Day Id, Month, Month Id and Hour**

## Data features

| Column | Count | Type |
| ------ | ----- | ---- |
| Invoice ID | 1000 | TEXT |
| Branch | 1000 | TEXT |
| City | 1000 | TEXT |
| Customer type | 1000 | TEXT |
| Gender | 1000 | TEXT |
| Product line | 1000 | TEXT |
| Unit price | 1000 | CURRENCY |
| Quantity | 1000 | NUMBER |
| Tax 5% | 1000 | CURRENCY |
| Total | 1000 | CURRENCY |
| Date | 1000 | DATE |
| Time | 1000 | TIME |
| Payment | 1000 | TEXT |
| cogs | 1000 | CURRENCY | 
| gross margin percentage | 1000 | NUMBER |
| gross_income | 1000 | CURRENCY |
| Rating | 1000 | NUMBER |
| Day | 1000 | TEXT |
| Day Id | 1000 | NUMBER |
| Month | 1000 | TEXT |
| Month Id | 1000 | NUMBER |
| Hour | 1000 | NUMBER |

## Conclusions

![Gender Distribution](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/gender_distribution.jpg)
1) There is a slightly higher number of female shoppers compared to male shoppers.

![Gender Distribution Per Product Line](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/gender_distribution_per_product_line.jpg)
2) Female customers tend to dominate sales across various product lines, except for the Health and Beauty category.

![Total Sales Per Branch](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/total_sales_per_branch.jpg)
3) Branch C stands out with the highest revenue generation of $110,568.71.

![Customer Type Per Branch](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/customer_type_per_branch.jpg)
4) Branch A and B have a higher number of regular customers making purchases, while Branch C has a larger number of members among its customer base.

![Total Sales Per Product Line](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/total_sales_per_product_line.jpg)
5) The highest-performing product line is "Food and Beverages," which generated a total revenue of $56,144.84 and a gross income of $2,673.56, In contrast, the "Health and Beauty" product line is the lowest-performing, with a total revenue of $49,193.74 and a gross income of $2,342.56 .

6) Based on the correlation coefficients, there are very weak and nearly negligible linear relationships between these variables(Unit price, Quantity and Rating). Changes in unit price or quantity purchased do not appear to be strongly associated with changes in customer ratings.

![Customer Per Payment Method](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/customer_per_payment_methodjpg.jpg)
7) The most preferred payment method by customers is the Ewallet payment method, with a total of 345 customers choosing this option.

![Payment Method Per Branch](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/payment_method_per_branch.jpg)
8) The Ewallet payment method was the most preferred in Branch A and B, with a total of 126 and 113 customers choosing this option, respectively, while the Cash payment method was preferred in Branch C, with a total of 124 customers choosing this option.

![Sales Per Month](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_per_month.jpg)
9) January recorded the highest revenue, totaling $116,291.87 , while February recorded the lowest revenue, with a total of $97,219.37 .

![Sales Per Day]([https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_per_month.jpg](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_per_day.jpg)
10) Revenue is at its peak on Saturdays, with a total of $56,120.81  recorded on Saturdays. Conversely, revenue is at its lowest on Mondays, with a total of $37,899.08 recorded.

![Sales Per Time Of Day]([https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_per_month.jpg](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_by_time_of_day.jpg)
11) The peak period of the day is 7 PM, with a total revenue of $39,699.51 recorded. Conversely, the least period of the day is 8 PM, with a total of $22,969.53 recorded.

![Gender Distribution]([https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_per_month.jpg](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/sales_by_customer_type.jpg)
12) Customers who are registered members generated the highest revenue, totaling $164,223.44 .

![Average Rating Per Customer Type](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/avg_rating_per_cutomer_type.jpg)
13) Customers who are not registered members recorded the highest average rating, with a rating of 7.01.

![Quantities Sold Per City](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/quantities_sold_per_city.jpg)
14) Yangon leads in terms of the quantity sold, with a total of 1859 units sold, while Mandalay recorded the lowest quantity ordered, with a total of 1820 units.

![Average Rating Per City](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/avg_rating_per_city.jpg)
15) Yangon and Naypyitaw received higher customer ratings from customers, with an average rating of 7, while Mandalay recorded the lowest customer rating, with an average rating of 6.8.

![Product Preference Per City](https://github.com/ahadel943/supermarket_sales_analysis/blob/main/assets/product_preference_per_city.jpg)
16) In Mandalay, the most preferred product line is Sports and Travel (322 units sold), in Naypyitaw it is Food and Beverages (369 units  sold), and in Yangon it is Home and Lifestyle (371 units sold).

## Recommendations:

Based on these findings, here are some recommendations:

1) **Marketing Strategy:** Given that females make up a significant portion of the customer base and dominate sales in many product lines, consider tailoring marketing strategies to target female shoppers more effectively.

2) **Branch Performance:** Investigate why Branch C is performing exceptionally well. This could provide insights into strategies that can be replicated in other branches.

3) **Product Line Enhancement:** Explore opportunities to improve the performance of the "Health and Beauty" product line, which is currently the lowest-performing.

4) **Payment Methods:** Given the popularity of Ewallet payment, consider offering promotions or incentives for customers who choose this method to encourage its continued use.

5) **Seasonal Marketing:** Leverage the knowledge that January is the highest revenue month to plan special promotions or events during this period.

6) **Weekday Strategies:** Develop strategies to boost sales on Mondays, which currently have the lowest revenue.

7) **Peak Sales Period:** Focus on maximizing sales during the peak period at 7 PM, potentially by offering promotions or enhancing the shopping experience.

8) **Membership Benefits:** Enhance the benefits of membership to encourage more customers to join and increase revenue.

9) **Customer Satisfaction:** Investigate why non-registered members provide the highest ratings. Understanding their preferences and needs can help improve overall customer satisfaction.

10) **City-Specific Marketing:** Tailor marketing efforts to each city's preferences, as product line preferences vary by location.
