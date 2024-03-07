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
1- What was the total Revenue and how many ordes were made?
2- What is our monthly order performance?
3- What days tend to be the busiest?
4- How many pizzas are sold in the bussiest day?
5- What are the best and worst-selling pizzas?
6- Which of our Pizza Category is the most in demand?
7- What pizzas sizes sell the most and the least?

1- Total revenue and orders
To start of let´s look how things went during the year. In the year of 2015, wich is the year analyzed , "Tony´s Pizza Restaurant" sold a total of 49.574 pizzas wich represented a total revenue of 817.860 USD. During this period 21350 orders were made , meaning that that in average 2,32 pizzas were requested by order and the average value of wich order was 38,31USD.

![gt1](https://github.com/AndreCammoes/pizza_sales/assets/160741788/342f0253-9e23-4b8a-8a80-f5c8941ede8b)

2-Montlhy order performance

In terms of the busiest months ,July was the month where the most orders were registered adding a total of 1935 orders. The months of January , March, April, May, August and December had similiar performances , where the numbers of orders floated between 1773 and 1853. In the order hand the months with the lowest volume of orders were February with 1685 registered orders, followed by December with 1680 orders and finally September and October with 1661 and 1646 respectively.

![git2](https://github.com/AndreCammoes/pizza_sales/assets/160741788/dbb5719f-7715-4dd4-905c-26b558ffbf2d)

3-Busiest days

The days that registered the highest amount of volume orders were the Fridays , with a total of 3500 orders followed by the Saturdays and Thursdays where both days registered around the same amount of orders wich was around 3200. Tuesdays and Wendnesdays also matched in terms of orders requests , with 3000 each , and finally the calmest days in the restaurant were Mondays and Sundays with 2800 and 2600 resquested orders repectively.

![git3](https://github.com/AndreCammoes/pizza_sales/assets/160741788/41554c3b-0539-4182-850d-3bc972466c07)

4- Pizzas sold in the buisest day

 As shown in the last topic , Friday is the day of the week where the restaurant has more activity. In total 8200 pizzas were sold on Fridays , followed by Thursdays and Saturdays where both days registered the same amout of sold pizzas wich was around 7500 units each.

 ![git5](https://github.com/AndreCammoes/pizza_sales/assets/160741788/a074fb1d-96fe-432e-8a18-20cb03c72888)

 5- Worst and best selling pizzas

 In terms of the most sold pizzas we got in 5th place The Thai Chicken Pizza, with 2371 pizzas sold , in 4th place The Pepperoni pizza with 2418 units sold , in 3rd position The Hawaiin Pizza that registered 2422 units sold and in 2nd and 1st place the The Barbecaue Chicken Pizza and the The Classic Deluxe Pizza that sold 2432 and 2453 respcetvily.
 In the other hand , the pizza the sold the least was the The Brie Carre Pizza that sold only 490 units, followed by The Mediterranean Pizza ,The Calebrese Pizza , The Spinach Supreme Pizza and The Soppressata Pizza.

 ![git6](https://github.com/AndreCammoes/pizza_sales/assets/160741788/dae699e5-9f12-4465-8004-be62518711ec)

 6- Wich pizza category had the more demand?

 The pizza category that showed the most sucess was the Classic one. This pizza category represent almost one third of all the sales (30,03%) and sold around 15000 units. In the second place we got category of supreme that sold around 12000 units (24,18% of the total) , and in third place with a business value very close of the second place is the Veggie , wich also sold close to 12000 units (23,50% of the total). In last place we got the Chicken category wich only sold 11000 units and represented 22,29% of the total pizzas category sales.

 ![image](https://github.com/AndreCammoes/pizza_sales/assets/160741788/71f61a38-fffa-408d-b813-5d56b2150adc)


 

 

 

 

 














