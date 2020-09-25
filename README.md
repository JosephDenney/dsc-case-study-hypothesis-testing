# Welcome to Case Study 2: Hypothesis Testing
Group members:
Tia Plagata & Joseph Denney

​
![hello](https://media1.tenor.com/images/a29b98e67fea932ef3a0871bc64dab4b/tenor.gif?itemid=17392429)
​
# Navigation
​
* [Project Overview](#Project-Overview)
* [Question 1](#Question-1)
* [Question 2](#Question-2)
* [Question 3](#Question-3)
​
# Important Links
* [Jupyter Notebook with Cleaning & Questions]()
​
# Project Overview
​
We are data scientists working for Northwind, a supplier company. Our job is find interesting relationships in their SQL database. In this case study we will explore their data and perform hypothesis tests to find the significance of these relationships.
​
In the process, we explored the following questions: 
​
# Question 1
**Is there a difference in quantity of products sold by discount rate?**
​
**Findings/Actionable Insights:**
​
There is no significant difference between quantity of products ordered for 0% discount and 10% discount, Therefore, we should not offer a 10% discount.
​
# Question 2
**Is there a difference in number of orders and region?**
​
**Findings/Actionable Insights:**
​
There seems to be a more significant difference between North America and the other regions, and Western Europe and the other regions, but not between North America and Western Europe. Therefore, we should investigate further between North America, Western Europe, and regions with lower order quantities, such as Scandanavia and Central America. 
​
# Question 3
(Deep-dive into Q2)
​
**Is there a difference in number of orders between North America and Western Europe?**
​
**Findings/Actionable Insights:**
There is no significant difference between mean number of orders in North America and Western Europe. They are the two regions with the highest mean number of orders, compared to all other regions. Therefore, when allocating budgets, we should consider this finding and potentially allocate an even amount of resources between the two of them. We should further investigate what is causing Scandinavia and Central America to have such low per order item quantities. Finally, we can also investigate which regions, if any, are not seeing increased item quantity as a result of the 10% discount.  





