Introduction 

Welcome to the detailed analysis of "Tony's Pizza Restaurant"! Situated in the heart of Chicago, "Tony's Pizza Restaurant" has established itself as a beloved dining destination for pizza enthusiasts. Since its inception, the restaurant has garnered a reputation for serving mouthwatering pizzas crafted from the finest ingredients. In this analysis, we will dive into various aspects of this establishment, providing insights into its operations and customer preferences. In this examination will cover a range of topics, including the busiest days of the week, the most popular pizza selections, those ordered the least, and much more.

About DataSet
This pizza sales dataset make up 12 relevant features:

order_id: Unique identifier for each order placed by a table

order_details_id: Unique identifier for each pizza placed within each order (pizzas of the same type and size are kept in the same row, and the quantity increases)

pizza_id: Unique key identifier that ties the pizza ordered to its details, like size and price

quantity: Quantity ordered for each pizza of the same type and size

order_date: Date the order was placed (entered into the system prior to cooking & serving)

order_time: Time the order was placed (entered into the system prior to cooking & serving)

unit_price: Price of the pizza in USD

total_price: unit_price * quantity

pizza_size: Size of the pizza (Small, Medium, Large, X Large, or XX Large)

pizza_type: Unique key identifier that ties the pizza ordered to its details, like size and price

pizza_ingredients: ingredients used in the pizza as shown in the menu (they all include Mozzarella Cheese, even if not specified; and they all include Tomato Sauce, unless another sauce is specified)

pizza_name: Name of the pizza as shown in the menu

Business Tasks
1- What was the total Revenue?
2- How many pizzas were sold?
3- What is our monthly order performance?
4- What days and times do we tend to be busiest?
5- How many pizzas are made in the bussiest day?
6- What are the best and worst-selling pizzas?
7- Which of our Pizza Category is the most in demand?
8- What pizzas sizes sell the most and the least?

General View
To start of let´s look how things went during the year. In the year of 2015, wich is the year analyzed , "Tony´s Pizza Restaurant" sold a total of 49.574 pizzas wich represented a total revenue of 817.860 USD. During this period 21350 orders were made , meaning that that in average 2,32 pizzas were requested by order and the average value of wich order was 38,31USD.

![gt1](https://github.com/AndreCammoes/pizza_sales/assets/160741788/342f0253-9e23-4b8a-8a80-f5c8941ede8b)

2-Montlhy order performance
In terms of the busiest months ,July was the month where the most orders were registered adding a total of 1935 orders. The months of January , March, April, May, August and December had similiar performances , where the numbers of orders floated between 1773 and 1853. In the order hand the months with the lowest volume of orders were February with 1685 registered orders, followed by December with 1680 orders and finally September and October with 1661 and 1646 respectively.

![git2](https://github.com/AndreCammoes/pizza_sales/assets/160741788/dbb5719f-7715-4dd4-905c-26b558ffbf2d)




