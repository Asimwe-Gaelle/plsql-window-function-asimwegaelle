# plsql-window-function-asimwegaelle
PL/SQL window functions assignment - Asimwe Gaelle

## 1. Business problem
Analysing sales and customer behaviour for an e-commerce platform to identify top products, measure growth, and segment customers for marketing.

## 2. Project contents
- create table.sql - DDL for customers, products, transactions
- insert sample data.sql
- queries.sql - window function queries (ranking, aggregate, LAG/LEAD, NTILE, moving average)
- ER_diagram.png - entity relationship diagram
- screenshoots - screenshoots of queries and results

## 3. how to run (brief)
1. run 'create table.sql' in yout oracle?SQL client
2. run 'insert sample_data.sql'
3. execute queries

## 4. key findings 
1. Top customers and products drive most of the revenue
- the ranking and quartile analysis showed that a small portion of customers account for majority of total sales.
- similarly, sneakers and coffe beans ranks among the best selling products across regions.
This means that business should focus promotions and loyalty program on these high value customers and products.

2. sales growth is seasonal with sharp spikes
- the month over month growth and moving average queries revealed a significant jump in sales from february to march (by 214.58%).
-  however, moving average shows that this spike snooths out into a stable upward trend.
This indicates sales are influenced by seasonal demand or promotions, so the business should prepare extra stock and marketing campaigns for peak months.

## 5. Refernces
1. oracle documentation - window functions
2. postgreSQL documentation - window functions
3. w3schools - MySQL | LEAD and LAG function
4. GeeksforGeeks - SQL window fucntions explained with examples
5. Mode Analysis - SQL tutorial: window functions
6. Stack overflow discussions - when to choose rank() over dense_rank or row_number
7. oracle liveSQL - analytic functions
8. MySQL 8.0 documentation - window functions
## 6.Integrity statement
"All sources were properly cited. Implementations and analysis represent original work. No AI-generated content was copied without attribution or adaptation."

