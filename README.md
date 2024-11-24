A fully-featured eCommerce website built with Django, providing essential functionalities such as user authentication, product catalog, cart management, checkout, and secure payment integration.

Features
User Authentication: Registration, login, and profile management.
Product Catalog: Browse and search products.
Shopping Cart: Add/remove items, manage quantities.
Checkout: Order summary and shipping address management.
Payment Integration: Razorpay for secure transactions.
Admin Panel: Manage products, orders, and users.
Screenshots
Home Page
Product Page
Cart & Checkout
Order History
Profile & Settings
Technologies Used
Django for backend
HTML/CSS/JS for frontend
Razorpay API for payments
Bootstrap for responsive design
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/pratikdhumal101/Ecommerce-site.git

Install dependencies:

bash
Copy code
pip install -r requirements.txt
Migrate the database:

bash
Copy code
python manage.py migrate
Create a superuser:

bash
Copy code
python manage.py createsuperuser
Run the server:

bash
Copy code
python manage.py runserver
Usage
Access the site at http://127.0.0.1:8000/.
Admin panel available at http://127.0.0.1:8000/admin/.






