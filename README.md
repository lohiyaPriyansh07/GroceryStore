# groceryStore

In this python project, we will build a grocery store management application. It will be 3 tier application,
1. Front end: UI is written in HTML/CSS/Javascript/Bootstrap
2. Backend: Python and Flask
3. Database: mysql

![](homepage.JPG)

### Installation Instructions

1. Clone the repository:
`git clone https://github.com/yourusername/GroceryStore.git`

2. Navigate to the backend directory:
`cd GroceryStore/backend`

3. Install dependencies:
`pip install -r requirements.txt`

4. Create a `.env` file in the `server` directory and add your database credentials:
`DATABASE_URL=your_database_url`

5. Start the Flask server:
`flask run`

Navigate to the frontend directory `index.html` open with live server

### Features
```
1.Product Catalog: Display and browse a wide range of grocery items present in store 
2.Product Category: Product is divide into category whether its price is calculated as per weight or per piece
3.Billing: Billing can be done for perticular customer and its details are stored
4.Order History: Track of order history and toltel amount of items sold is maintained
5.Admin Interface: Manage inventory and view sales reports.
```
### Project Structure
```
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
|   |   ├── custom.css
|   |   ├── sidebar-menu.css
|   |   ├── bootstrap.min.css
|   |   └── style.css
│   ├── js/
│   │   ├── custom/
│   │   │   ├── common.js
│   │   │   ├── dashboard.js
│   │   │   ├── order.js
│   │   │   └── manage-product.js
│   │   ├── packages/
│   │   │   ├── bootstrap.min.js
│   │   |   └── jquery.min.js
|   |   └── images/
|   |   
│   ├── index.html
│   ├── manage-product.html
│   └── order.html
│
├── .gitignore
├── homepge.jpj
└── README.md
```
