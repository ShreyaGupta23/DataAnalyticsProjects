As part of Jobaaj Learnings I attended the Data Analytics Workshop where skills like data cleaning,querying,visualising were covered using the tools like spreadsheets(Formatting,viewing and analysing the data),SQL(Joins),Google notebooks(Python) and PowerBI(Visualising).

Note: All the datasets were provided during the workshop.
# Use of PowerBI
Walmart.csv file is used for visualising purpose.We will be analysing the sales of walmart by using different attributes.
Open the Sales.pbix file in PowerBi for better understanding. sales.PNG shows the glimpse of the visualization. It includes slicers,cards,area map,tree map,clustered bar chart and decomposition tree.
# Use of Google Notebook(Python)
Here we Superstore.csv file is being used. Upload it in google notebooks and clean it using python. Then save the result in Sales.csv . 
Code for the same : https://colab.research.google.com/drive/1EcDwL5Azo5D_cUTiGt2QxPe3rGYVmwTr?usp=sharing
# Use of SQL
SQLite has been used for using SQL (https://sqliteonline.com/). Upload ReturnOrder.csv and Walmart.csv file and explore some basic SQL commands. 

We will be joining both the files on order id and then save the final sheet in SQLite.csv. This is the basic implementation of joins.
Query : SELECT customer_name, product_name,profit, returned 
FROM Walmart join Return_Order
on order_id = orders
