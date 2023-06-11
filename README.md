# case-study

## Description
Used the Danny's diner data from 8weelsqlchallenge.com for the case study. It contained the following 3 key datasets:  
* Sales
* Menu
* Members
Below image depicts database schema of the case study:
![Schema](./img/Schema.png)
  
  In this schema, the "Sales" table represents the fact table, as it contains the transactional data capturing the sales information. The "Menu" and "Members" tables are dimension tables, as they provide additional descriptive information about the products and customers, respectively.
* The sales table captures all customer_id level purchases with an corresponding order_date and product_id
information for when and what menu items were ordered.
* The menu table maps the product_id to the actual product_name and price of each menu item.
* The final members table captures the join_date when a customer_id joined the beta version of the Danny’s Diner
loyalty program.
