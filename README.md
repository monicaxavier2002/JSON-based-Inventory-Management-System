# JSON-based-Inventory-Management-System
This repository is having all the codes used in AI/ML Skill India Scholarship Assignment on Inventory Management System

-------
### About the Repository?
You'll learn JSON, NoSQL databases, File handling

### Files
record.json: It contains details of all products in the inventory in the form of dictionary having Product ID, Product name, Product category, Product Brand,  quantity and price

sales.json: It contains all sales transactions performed in the form of Transaction ID, Product ID, Quantity purchased, billing amount and billing time.

Managing inventory_GUI.ipynb:
It displays the entire inventory in tabular format and a refresh button is provided. After adding/updating/deleting products, On pressing refresh, it will show the updated inventory
On pressing 'See all transactions' button, it will display all transactions in tabular format.
When adding products, it will check for null/invalid values and displays error message. It also checks if the entered product is already present in inventory and displays an error message for the same. It accepts only integer values for product ID, price and quantity
When updating products, it will check for null/invalid values and displays error message. It also checks if the entered product is not present in inventory and displays an error message for the same. It accepts only integer values for product ID, price and quantity
When deleting products, it will check for null/invalid values and displays error message. It also checks if the entered product is not present in inventory and displays an error message for the same. It accepts only integer values for product ID

Purchasing products.ipynb
Customer can purchase products by entering product ID and quantity and the Transaction ID, Product ID, Quantity purchased, billing amount and billing time are updated into sales.json file
When purchasing, it checks null/ invalid values for product ID and quantity and displays error message.  It accepts only integer values for product ID and quantity

### Features
1. Login system for admin. username: admin, password: admin
2. GUI based system for easily managing inventory for admin as well as purchasing products for costumers
3. Admin can add new items/update existing items/delete items from inventory
4. The inventory and sales transactions are displayed in tabular format
5. The inventory is displayed to customer so that he/ she can easily choose from products.
