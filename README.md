Grocery Store
In this Python project, we will build a grocery store management application. It will be a 3-tier application:

Front End: UI is written in HTML/CSS/JavaScript/Bootstrap
Backend: Python and Flask
Database: MySQL


Installation Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/GroceryStore.git
Navigate to the backend directory:

bash
Copy code
cd GroceryStore/backend
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Create a .env file in the backend directory and add your database credentials:

env
Copy code
DATABASE_URL=your_database_url
Start the Flask server:

bash
Copy code
flask run
Navigate to the frontend directory and open index.html with a live server.

Features
Product Catalog: Display and browse a wide range of grocery items present in the store.
Product Category: Products are divided into categories based on whether their price is calculated by weight or per piece.
Billing: Billing can be done for a particular customer, and its details are stored.
Order History: Track order history and total amount of items sold.
Admin Interface: Manage inventory and view sales reports.
Project Structure
vbnet
Copy code
GroceryStore/
├── backend/
│   ├── orders_dao.py
│   ├── products_dao.py
│   ├── uom_dao.py
│   ├── server.py
│   └── sql_connection.py
│
├── ui/
│   ├── css/
│   │   ├── custom.css
│   │   ├── sidebar-menu.css
│   │   ├── bootstrap.min.css
│   │   └── style.css
│   ├── js/
│   │   ├── custom/
│   │   │   ├── common.js
│   │   │   ├── dashboard.js
│   │   │   ├── order.js
│   │   │   └── manage-product.js
│   │   ├── packages/
│   │   │   ├── bootstrap.min.js
│   │   │   └── jquery.min.js
│   |── images/
│   |
│   ├── index.html
│   ├── manage-product.html
│   └── order.html
│
├── .gitignore
├── homepage.JPG
└── README.md
