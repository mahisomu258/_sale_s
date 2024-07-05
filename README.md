# _sale_s

This database tracks sales data for a pizza shop. It includes information on pizzas, pizza types, orders, and order details. The database schema consists of the following tables:

pizza_types: Contains information about different types of pizzas.

pizzas: Contains information about individual pizzas.

orders: Contains information about customer orders.

order_details: Contains details about each order, including which pizzas were ordered and in what quantities.


pizza_types table contains : pizza_type_id,name,category,ingredients

pizzas contains:pizza_type_id,pizza_id,size,price

orders contains:order_id,date,time

order_details contains:order_details_id,order_id,pizza_id,quantity

