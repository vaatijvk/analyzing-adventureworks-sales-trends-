# analyzing-adventureworks-sales-trends-

I conducted a comprehensive analysis focusing on several key aspects to provide actionable insights for business decisions using the AdventureWorks dataset. From evaluating monthly sales trend, performance analysis for the salespersons, countries and territories and comparing online and offline orders, this his project seeks to empower stakeholders with actionable recommendations for optimizing sales strategies, improving operational efficiency, and capitalizing on emerging opportunities. 
 By leveraging the APPASA framework—Ask, Prepare, Process, Analyse, Share, Act—this endeavor ensures a methodical approach to uncovering trends, understanding customer behavior, and driving sustainable growth in a competitive market environment.

What is the monthly sales trend?
How do online orders compare to non-online orders?
What is the delivery performance trend (lag between order date and ship date)?
Who are the top salespersons by sales and by volume?
Which countries are the top performers in sales?
What are the top performing territories by revenue? 
What are the top sales reasons?

I cleaned my data and gathered the relevant data which includes splitting the order date into years and month, using vlookup function to get the sales reasons, the sales persons names and the territory names and the countries as well as calculating the orderdate and shipdate lag. 
Verifying data accuracy by checking if the data needed for analysis is complete and accurate.
Consulted  through an open session to confirm and understand the data set (onlineorder flag) and the revision number
  

Monthly Sales Trend and Monthly order Trend
I used a pivot table to group my data in months and years. From 2001 to 2004. 
Online orders vs offline orders
I grouped my data using revenue/ Total due as values and compared them. 
I made a comparison using the number of orders as well. 
Delivery performance trend 
Averagely, it takes 7 days for an order to be shipped. 
From our data, all the orders that take 8 days have 2 revisions and are offline order

Top salesperson by sales(Totaldue/Revenue)
From my pivot table, the top performing salespersons have a higher sum of the revenue/ total due than the average sum of all the Total due

Top salesperson by number of orders
From my pivot table, the top performing salespersons have a higher sum of the sales orders  than the average sum of all the sales orders



Top performing countries by revenue
From my pivot table it is evident that top performing countries have a total revenue that is higher than the average of the total revenue. 
We can further see the performance of the countries using a pie chart 
Top performing countries by orders
From my pivot table it is evident that top performing countries have a total number number of orders  that is higher than the average of the total number of orders 
We can further see the performance of the countries using a pie chart 

 Top performing territories  by revenue
From my pivot table it is evident that top performing territories  have a total revenue that is higher than the average of the total revenue. 
We can further see the performance of the countries using a pie chart. 


Recognizing top performing salespersons based on both revenue and orders
This could include implementing incentive programs to motivate the team.
Increasing marketing efforts in top performing countries and territories by establishing partnerships with  local distributors. 
Ensuring timely deliveries and enhancing customer satisfaction. 
Promote Top Sales Reasons: 
This could involve highlighting these reasons in marketing campaigns and training sales teams to emphasize these points during customer interactions.
Enhancing online sales channels 
 	This includes website usability, optimizing mobile responsiveness, and streamlining the checkout process to reduce cart abandonment rates.
Customer Service Training: Enhance training for offline sales staff to ensure they can effectively upsell and provide exceptional customer service, further driving higher revenue per transaction.

# https://docs.google.com/presentation/d/1JK2HvSthLOw4b_Q5FBSHa3eBvm-RDPZDZEx5P6Auyoc/edit#slide=id.g2e7a7dbbb9a_0_274
# https://docs.google.com/spreadsheets/d/1BKOTAMGXMPTzRta2l3QtcEJUiPlzbJJm8HHOBtW8L7Q/edit?usp=sharing










