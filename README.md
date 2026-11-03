# ShopEasy: Sales and Customer Analysis with SQL

You have just joined the analytics team at **ShopEasy**, an online store. Management has sent you a list of requests about our products, customers and orders. Answer each one with a MySQL query. All amounts are in rupees, and "revenue" means what customers actually paid.

## How to submit

1. **Fork** this repository.
2. Run `setup.sql` in MySQL Workbench to create the `shopeasy_db` database.
3. Save your queries in a file named `solutions.sql`, one per request, with the request number above each query.
4. Commit and push to your fork, then share your fork's link.

## Requests from management

1. Marketing wants to know which cities our orders come from and which payment methods customers use. Give me each as a separate list.
2. The catalogue team needs a clean product list showing the product name, category and price, with proper headings.
3. Finance is auditing the April to June 2026 quarter. Show me all delivered orders from Kochi or Chennai placed in that period.
4. The payments team is reviewing card and net banking activity. Show me the orders paid by credit card or net banking where more than 2 units were bought and the order was not cancelled.
5. Which products are priced between ₹1,000 and ₹5,000 and are not in the Electronics category?
6. The website search team is testing premium-sounding product names. Which products have "Pro" or "Max" in their name?
7. Marketing wants to send a message to customers whose names start with "S". Give me each such customer once.
8. Show me all cancelled or returned orders where we gave no discount.
9. Which products launched in 2026 have not received a customer rating yet?
10. Who are our 5 most expensive products, and what do they cost?
11. Give me the full product list sorted by category from A to Z, and within each category with the most expensive product first.
12. Show me our 10 biggest delivered orders: who ordered, from which city, and how much they paid.
13. Give management a one-line summary of all orders that were not cancelled: how many orders, total revenue, average order value, smallest order and largest order. Use readable headings.
14. How many orders do we have in total, how many of them had a discount, and how many different customers have ordered?
15. For delivered orders, show each city with its number of orders and revenue, biggest revenue first.
16. For orders that were not cancelled, show each payment method with its number of orders and average order value. Only include methods used on more than 12 orders.
17. We want to reward loyal customers. Who has placed more than 4 orders (not counting cancelled ones)? Show their name, number of orders and total spend, and give me only the top 5 spenders.
18. For each product category, show how many products we sell, their average price and the total units in stock. Leave out categories with 3 products or fewer.
19. Operations wants to find slow cities. Among delivered orders, which cities take more than 6 days on average to deliver? Show the average, slowest first.
20. Looking only at delivered orders placed on or after 1 April 2026, and leaving out Delhi, show the number of orders and revenue for each payment method. Only include methods with revenue above ₹15,000, and show just the top 2.
