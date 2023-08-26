# Pizza-Project
SQL query on pizza project

we will be using a pizza dataset attained from kaggle for project purposes 
the first thing we need to do is create a database

in sql we can create a database by querying 
create database pizza_sales;

after that we will need to query the information that we want to analyse. 

Question 1.	Total Revenue: the sum of the total price of all pizza orders
to solve this we need to get the total revenue all we need to do is to add up all the total price of all the pizza and to do that we can use SUM to add up all the total price which is $817860.04

Question 2: the average order value. 
To get the result of average order value we first need to add the total price which we use sum and then divide it by the order id. The count function is used to count up the order id but we also use distinct because we don’t want to add up duplicate values in order to get the average order value. 

Question 3 Total Pizzas sold: 
The total pizza sold would require us to query the sum of the quantity table. 

Question 4 Total Pizza orders
The total number of orders will require us to query and count the orders but don’t want to include duplicate values therefore we use the distinct function which only returns different values 

Question 5: average pizza orders
To get the average pizza orders we will need to calculate by diving the total number of pizzas sold by the total number of orders.
The query shows that we will need to cast is as a numeric in the precision scale and we can use round to round it down 
