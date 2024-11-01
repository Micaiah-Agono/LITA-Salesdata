used postgresql's pgadmin to analyze the sales performance of a retail store, then generated insight by

-- retrieving the total sales for each product category. 

result --

product	total_sales

Socks	40000
Shoes	72500
Gloves	62500
Shirt	62500
Jacket	27500
Hat	80000


-- finding the number of sales transactions in each region.

result --

region	sales_transaction

South	122500
West	57500
North	62500
East	102500


-- finding the highest-selling product by total sales value.

result --

product	total_sales

Jacket	27500


-- calculating total revenue per product.

result --

product	total_revenue

Socks	912500
Shoes	3087500
Gloves	1500000
Shirt	2450000
Jacket	1050000
Hat	1587500


-- calculating monthly sales totals for the current year.

result --

month			monthly_sales_total

2024-01-01 00:00:00+01	1000000
2024-02-01 00:00:00+01	1500000
2024-03-01 00:00:00+01	275000
2024-04-01 00:00:00+01	200000
2024-05-01 00:00:00+01	225000
2024-06-01 00:00:00+01	750000
2024-07-01 00:00:00+01	187500
2024-08-01 00:00:00+01	875000


-- finding the top 5 customers by total purchase amount.

result --

customerid	total_purchase_amount

Cus1001		18235
Cus1002		18200
Cus1003		21365
Cus1004		23310
Cus1005		20130


-- calculating the percentage of total sales contributed by each region.

result --

region	region_sales	percentage_of_total_sales

East	2450000		23.14
North	1950000		18.42
South	4675000		44.16
West	1512500		14.29


-- identifing products with no sales in the last quarter

result -- 

product

Gloves
Jacket
Shirt
Socks
