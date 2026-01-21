# Dataset Schema

## gold.dim_customers
- customer_key
- customer_id
- customer_number
- first_name
- last_name
- country
- marital_status
- gender
- birthdate
- create_date

## gold.dim_products
- product_key
- product_id
- product_number
- product_name
- category_id
- category
- subcategory
- maintenance
- cost
- product_line
- start_date

## gold.fact_sales
- order_number
- product_key
- customer_key
- order_date
- shipping_date
- due_date
- sales_amount
- quantity
- price
