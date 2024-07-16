# E-Commerce Brazil Customer Segmentation

E-Commerce, also known as electronic commerce, involves the buying and selling of goods or services using the internet. Payments are usually made by money transfer, enabling the processing of products. This platform is especially helpful for sellers, particularly SMEs, who want to promote their brand and sell their products to attract a variety of customers. However, customers rarely make repeat transactions. Therefore, engaging customers to repeat transactions is essential for achieving a better conversion rate and increasing revenue. In this context, we aim to identify which customers have the potential to become loyal customers, new customers, and so on. The impact of this segmentation can be used to make decisions on targeting our campaigns or benefit programs.

# Data and Exploration

## Exploration Questions
In my exploratory data analysis, I will answer the following questions:
1. How many orders has been delivered accross all our transaction? How is about our review performance?
2. What is our sales summary? Has there been significantly growth months over months?
3. Which product are in our top 10 sales?
4. Where are our product sold the most?
5. Who are our top 10 customers?
6. Can you segment our customers?

# How many orders has been delivered accross all our transaction? How is about our review performance?

The given pie chart below `(Figure 1)` delitenates the percentage of our order status with 97.8% of 112,650 orders has been delivered. Furthermore, there are only 461 orders has been canceled which indicates how well our transaction process is. Additionally, with mean and median review scores of 4 and 5, respectively conclude that our performance showed good performance and it needs to be maintained or slightly improved in order to enhance customer satisfaction `(Figure 2)`.

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/3fc50b2129d73ffff36aaa492254a970fe77705e/Picture/Total%20Order%20by%20Status.jpg" alt="Total Order by Status">
  <p>Figure 1: Total Order by Status</p>
</div>

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/ec772c2c1fa205fcf73a97e1a1f2df980c8211a1/Picture/Description%20Review%20Score.jpg" alt="Review Score Description">
  <p>Figure 2: Review Score Description</p>
</div>

# What is our sales summary? Has there been significantly growth months over months?

Based on combo chart below `(Figure 3)`, it can be seen that GMV month-over-month showed significant growth from October 2016 to November 2017. However, GMV has slightly decreased afterwards, which requires a root-cause analysis. Unfortunately, this analysis cannot be performed due to limited data. Total income for our merchant approximately reached R$13.22 Million with around 96,000 orders with November 2017 was our standout performance with approximately R$987.77K, representing an increase of more than 50% in GMV. Additionally, AOV tends to stagnant as the majority spend their money below R$149.90

<div align="center">
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/d0c9be44efdaed95a6bbeb18db78b50a3aa82c9d/Picture/Sales%20Growth%20Month%20over%20Month.jpg" alt="Sales Growth Month-Over-Month">
  <p>Figure 3: Sales Growth Month-Over-Month</p>
</div>

# Which product are in our top 10 sales?

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
  <img src="https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/021791c7f887dabd782254e98157a1f625130b4a/Picture/Top%2010%20Product%20Pareto%20Last%203%20Months.jpg" alt="Pareto Product in the Last 3 Months">
  <p>Figure 6: Pareto Product in the Last 3 Months</p>
</div>

![Top 10 Product Sales in the Last 3 Months](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/021791c7f887dabd782254e98157a1f625130b4a/Picture/Top%2010%20Product%20Sales%20Last%203%20Months.jpg "Top 10 Product Sales in the Last 3 Months") ![Pareto Product in the Last 3 Months]([image2.png](https://github.com/jafarsidiq98/E-Commerce-Brazil-Customer-Segmentation/blob/021791c7f887dabd782254e98157a1f625130b4a/Picture/Top%2010%20Product%20Pareto%20Last%203%20Months.jpg) "Pareto Product in the Last 3 Months")


