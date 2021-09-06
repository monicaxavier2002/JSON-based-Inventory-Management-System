# JSON-based-Inventory-Management-System
This repository is having all the codes used in AI/ML Skill India Scholarship Assignment on Inventory Management System

-------
### About the Repository?
You'll learn JSON, NoSQL databases, File handling

### Files
1. record.json: It contains details of all products in the inventory in the form of dictionary having Product ID, Product name, Product category, Product Brand,  quantity and price

2. sales.json: It contains all sales transactions performed in the form of a dictionary having Transaction ID, Product ID, Quantity purchased, billing amount and billing time.

3. Managing inventory_GUI.ipynb:
Username: admin, password:admin
It displays the entire inventory in tabular format and a refresh button is provided. After adding/updating/deleting products, on pressing refresh, it will show the updated inventory
On pressing 'See all transactions' button, it will display all transactions in tabular format.
When adding products, it will check for null/invalid values and displays error message. It also checks that the entered product is not present in inventory and displays an error message if present. It accepts only integer values for product ID, price and quantity
When updating/deleting products, it will check for null/invalid values and displays error message. It also checks that the entered product is present in inventory and displays an error message if not present. It accepts only integer values for product ID, price and quantity
After every adding/updating/deleting a product, it is updated in record.json

4. Purchasing products.ipynb:
Customer can purchase products by entering product ID and quantity. Transaction ID, Product ID, Quantity purchased, billing amount and billing time are updated into sales.json file after every purchase
When purchasing, it checks null/ invalid values for product ID and quantity and displays error message. It accepts only integer values for product ID and quantity

### Features
1. Login system for admin.
2. Login credentials:  username: admin, password: admin
3. GUI based system for easily managing inventory for admin as well as purchasing products for costumers
4. Admin can add new items/update existing items/delete items from inventory
5. The inventory and sales transactions are displayed in tabular format
6. The inventory is displayed to customer so that he/ she can easily choose from products.
-------

### Who am I?

My name is Monica. I am a Third year Biomedical Engineering student. My long term goal is to create innovations in the medical field through Machine learning, artificial intelligence, neural networks, etc.

-------

### Other Useful Links:
LinkedIn- https://www.linkedin.com/in/monica-xavier-/
Instagram- https://www.instagram.com/monicaxavier144/
