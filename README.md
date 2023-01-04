# Resturant_system-not_finished-
Resurant__order_system
Order System

This is a Python-based order system for a restaurant. The system allows users to place orders for various menu items such as salads, meals, sodas, drinks, and desserts. The system also allows users to view their orders and the total bill.
Prerequisites

    Python 3.8 or higher
    mysql-connector-python 2.2.9 or higher
    PIL (Python Imaging Library) 6.2.2 or higher

Installation

    Clone the repository:

git clone https://github.com/YOUR_USERNAME/order-system.git

Navigate to the project directory:

cd order-system

Install the required dependencies:

pip install mysql-connector-python
pip install Pillow

Connect to your MySQL database and create a new database and table:

mysql -u root -p
CREATE DATABASE order_system;
USE order_system;
CREATE TABLE orders (table_id TEXT, bill TEXT);

Run the program:

    python order_system.py

Features

    Place orders for various menu items such as salads, meals, sodas, drinks, and desserts
    View the total bill for all orders
    View the orders for a specific table
    Delete orders
    Clear all orders for a specific table

Usage

    On the main menu, select the table number you wish to place an order for.
    Select a menu category from the side panel (e.g. salad, meal, soda).
    Select the specific menu item you wish to order.
    The selected menu item will be added to the orders list and the total bill will be updated.
    To view the orders for a specific table, select the table number and click the "View Orders" button.
    To delete an order, select the order in the orders list and click the "Delete" button.
    To clear all orders for a specific table, click the "Clear Orders" button.

Note: This program is for educational purposes only and is not intended for use in a real restaurant.
