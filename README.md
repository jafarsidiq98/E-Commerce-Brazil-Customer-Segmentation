# **E-Commerce Brazil Customer Segmentation**

E-Commerce, also known as electronic commerce, involves the buying and selling of goods or services using the internet. Payments are usually made by money transfer, enabling the processing of products. This platform is especially helpful for sellers, particularly SMEs, who want to promote their brand and sell their products to attract a variety of customers. However, customers rarely make repeat transactions. Therefore, engaging customers to repeat transactions is essential for achieving a better conversion rate and increasing revenue. In this context, we aim to identify which customers have the potential to become loyal customers, new customers, and so on. The impact of this segmentation can be used to make decisions on targeting our campaigns or benefit programs.

# Data and Exploration

## Data
* https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Exploration Questions
In my exploratory data analysis, I will answer the following questions:
1. How many orders has been delivered accross all our transaction? How is about our review performance?
2. What is our sales summary? Has there been significantly growth months over months?
3. Which product are in our top sales?
4. Where are our product sold the most? Who are our top customers?
5. Can you segment our customers?

# How many orders has been delivered accross all our transaction? How is about our review performance?

The given pie chart below `(Figure 1)` delineates the percentage of our order status with 97.8% of 112,650 orders has been delivered. Furthermore, there are only 461 orders has been canceled which indicates how well our transaction process is. Additionally, with mean and median review scores of 4 and 5, respectively conclude that our performance showed good performance and it needs to be maintained or slightly improved in order to enhance customer satisfaction `(Figure 2)`.

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/3fc50b2129d73ffff36aaa492254a970fe77705e/Picture/Total%20Order%20by%20Status.jpg" alt="Total Order by Status">
  <p>Figure 1: Total Order by Status</p>
</div>

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/ec772c2c1fa205fcf73a97e1a1f2df980c8211a1/Picture/Description%20Review%20Score.jpg" alt="Review Score Description">
  <p>Figure 2: Review Score Description</p>
</div>

# What is our sales summary? Has there been significantly growth months over months?

Based on combo chart below `(Figure 3)`, It can be seen that GMV almost consistently rose every month from October 2016 to November 2017, with significant growth occurring between October and November 2017, reaching a peak in November 2017 with approximately R$987.77K, representing an increase in GMV of more than 50% from the previous month. However, GMV fluctuated afterwards, never exceeding the sales figures of November 2017, which requires a root-cause analysis. Unfortunately, this analysis cannot be performed due to limited data. Total income for our merchant approximately reached R$13.22 Million with around 96,000 orders. Additionally, AOV tends to stagnant as the majority spend their money below R$149.90

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/d0c9be44efdaed95a6bbeb18db78b50a3aa82c9d/Picture/Sales%20Growth%20Month%20over%20Month.jpg" alt="Sales Growth Month-Over-Month">
  <p>Figure 3: Sales Growth Month-Over-Month</p>
</div>

# Which product are in our top sales?

The data below represent the top 10 products based on all historical transactions with bb50f2e236e5eea0100680137654686c as our best product `(Figure 4)`. However, some products have not had any sales in the last 3 months. Given the rapid growth of E-Commerce, focus only on the products that have made sales in the past 3 months.

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/a2d078e66c020d66f3e74a5a0d7e4a67133e0f75/Picture/Top%2010%20Product%20Pareto%20All%20Transaction.jpg" alt="Top 10 Products by Historical Sales">
  <p>Figure 4: Top 10 Products by Historical Sales</p>
</div>

Based on the chart on `Figure 5`, it can be seen that bb50f2e236e5eea0100680137654686c remains our best product. Additionally, the consistent performance of 6cdd53843498f92890544667809f1595 as one of our top products indicates that people are already aware of them, so we do not need to promote these products extensively.

On the other hand, there are only 7 Pareto products that we need to monitor in terms of stock and market `(Figure 6)`. This is not ideal because if one of these products goes out of stock or loses market interest, our GMV will significantly drop. Therefore, we must promote other products to increase GMV and not rely solely on these 7 Pareto products.

Additionally, we should check the market and stock for products that have made it into the top 10 historical sales but have not been in the top 10 for the last 3 months, even if they have had sales during this period. We need to determine whether the market has lost interest in these products. If so, and we still have stock of these products, it would be better to use them as giveaways or free products.

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/021791c7f887dabd782254e98157a1f625130b4a/Picture/Top%2010%20Product%20Sales%20Last%203%20Months.jpg" alt="Top 10 Product Sales in the Last 3 Months">
  <p>Figure 5: Top 10 Product Sales in the Last 3 Months</p>
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/021791c7f887dabd782254e98157a1f625130b4a/Picture/Top%2010%20Product%20Pareto%20Last%203%20Months.jpg" alt="Pareto Product in the Last 3 Months" >
  <p>Figure 6: Pareto Product in the Last 3 Months</p>
</div>

# Where are our product sold the most? Who are our top customers?

Most of our sales are in São Paulo, with 14.06% of our revenue coming from that area, followed by Rio de Janeiro and Belo Horizonte, which contribute 7.23% and 2.62% of our revenue, respectively `(Figure 7)`. On the other hand, Polo Petroquímico de Triunfo, Sabaudia, and Santo Antônio do Rio Abaixo have the lowest sales. Regarding customer insights, the customer with unique ID 0a0a92112bd4c708ca5fde585afaa872 is our best customer, alongside da122df9eeddfedc1dc1f5349a1a690c and 763c8b1c9c68a0229c42c9fc6f662b93 `(Figure 8)`.

|![](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/4b79d3a53302016e6dcb66c74a88d8ee30966ab3/Picture/Top%2010%20City%20Sales.jpg)|![](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/4b79d3a53302016e6dcb66c74a88d8ee30966ab3/Picture/Top%2010%20Customers%20Sales.jpg)|
|:-:|:-:|
|Figure 7: Top 10 City Sales|Figure 8: Top 10 Customer Sales|

# Can you segment our customers?

We segmented our customer based on their recency `(Figure 9)`, frequency `(Figure 10)`, and monetary `(Figure 11)`. Recency refers to the number of days since a customer made their most recent purchase, while frequency indicates the number of transactions within a given period, and monetary refers to the spending amount. 

|![](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/fba480cb06964195bc6dfffbcc526a749c0e1533/Picture/Recency%20Boxplot.jpg)|![](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/fba480cb06964195bc6dfffbcc526a749c0e1533/Picture/Frequency%20Boxplot.jpg)|![](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/fba480cb06964195bc6dfffbcc526a749c0e1533/Picture/Monetary%20Boxplot.jpg)|
|:-:|:-:|:-:|
|Figure 9: Recency|Figure 10: Frequency|Figure 11: Monetary|

As you can see in the `Figure 10`, most of them are one-time purchasers. Therefore, our clustering relies more on recency and monetary value. However, to increase our GMV, We will provide recommendations to engage customers in repeat transactions. For instance, creating loyalty programs that offer benefits such as earning points after each transaction, which can be exchanged for rewards, or offering giveaways after multiple transactions. Here are the results:

## Customer Group 0
We classified Customer Group 0 as our churned customers. These customers have not made a transaction for an average of 6-7 months. Furthermore, due to their low spending amount, we believe it is best to deprioritize this group. 

## Customer Group 1
We categorized Customer Group 1 as our potential customers. These customers have made their last purchase within the last month on average. Despite the recent activity, their average spending amount remains low. Therefore, we need to encourage repeat transactions by offering vouchers and discounts for the second transaction with a minimum purchase of $86.50, as $86.50 is our Q3 value, to increase our Average Order Value. Additionally, promoting our loyalty program to attract and engage customers, encouraging them to return for future purchases.

## Customer Group 2
We identified Customer Group 2 as our best customers. With low recency and high spending, we have to engage our customers by implementing our customer loyalty program in order to encourage them for future purchases. Also, provide product recommendation based on their preference at the beginning of the page as well as their previous purchase to enhance the shopping experience and make it easier for customers. Additionally, Launce cross-selling or up-selling campaign to increase our average order value.

## Customer Group 3
We have designated Customer Group 3 as our high potential churn. These customers has high spending amount but high recency. Since they spent a lot in our platform, I think that it will be better if we tried to conduct survey or feedback to understand about the needs of customers who have spent significantly. This will help tailor the approach to address their specific requirements. Try to offer a discount and other benefits on their first purchase upon returning as well as promote our loyalty program to incentivize their return.

## Customer Group 4
We have designated Customer Group 4 as our at risk customers. These customers has medium recency but low monetary. Because of that, I think we should focus on conducting satisfaction surveys for our services to identify and address any issues that may be causing dissatisfaction. Additionally, we might consider promoting our loyalty program to encourage them to return for future purchases.

