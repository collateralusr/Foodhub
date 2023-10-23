# Foodhub


Project Foundations for Data Science: FoodHub Data Analysis



Context:

The increasing number of restaurants in New York has led to a rise in demand for online food delivery services. FoodHub, a food aggregator company, connects customers with multiple restaurants through a smartphone app. The app allows customers to place orders directly with restaurants, and FoodHub arranges for a delivery person to pick up and deliver the food. The company collects a margin on the delivery orders. As a Data Scientist at FoodHub, the objective is to analyze the data related to food orders to gain insights into restaurant demand and enhance customer experience.



Objective:

The objective is to answer key questions that will help FoodHub improve its business. This includes analyzing restaurant demand and understanding customer preferences. The data analysis will provide insights to enhance the customer experience.



Data Description:

The dataset contains information related to food orders and customer ratings. The data dictionary is as follows:



order_id: Unique ID of the order

customer_id: ID of the customer who ordered the food

restaurant_name: Name of the restaurant

cuisine_type: Cuisine ordered by the customer

cost: Cost of the order

day_of_the_week: Indicates whether the order is placed on a weekday or weekend (Monday to Friday is considered a weekday, Saturday and Sunday are considered the weekend)

rating: Rating given by the customer out of 5

food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food, calculated by the time difference between the restaurant's order confirmation and the delivery person's pick-up confirmation

delivery_time: Time (in minutes) taken by the delivery person to deliver the food package, calculated by the time difference between the delivery person's pick-up confirmation and drop-off information

Key Questions:



What are the most popular cuisines ordered by customers?

Do customers rate weekend orders differently from weekday orders?

Which restaurants have the fastest food preparation times, and does it impact customer ratings?

Is there a relationship between order cost and customer ratings?

How does delivery time impact customer ratings and order cost?

Are there any trends in customer ratings over time?

Can FoodHub identify high-demand time periods for marketing campaigns?

Are there customer segments with specific preferences, and how can FoodHub cater to these segments?
