Order system 

This is a Python script that uses Tkinter and PIL to create a GUI based ordering system for a restaurant. The script allows the user to select items from a menu, display the order and bill, and stores the order data in a MySQL database.
Requirements

    Python 3.x
    Tkinter (Included with Python)
    PIL (Python Imaging Library)
    mysql-connector-python

Installation

To use this script, you will need to have the following software installed on your machine:

    MySQL server

You will also need to install the required Python packages. You can do this by running the following command:

pip install mysql-connector-python pillow

Usage

    Create a database with a name of your choice.
    Update the con = mysql.connector.connect(host="", user="", password="", database="") variable in the script to match the host, user, password, and the name of the database you created.
    Update the menu variable to match the menu of your restaurant.
    Change the path of the images in the script to match the path of your images on your machine
    Run the script by running the command

python main.py

Please make sure that the paths you provide for the images exists and are accessible.
Note

Make sure that the menu prices and items you want to add are correct and that the images you want to add exist in your machine and the path is correct. Also make sure that you have the required software and packages installed on your machine, and update the host, user, password and the name of the database in the script to match the name of your database.
