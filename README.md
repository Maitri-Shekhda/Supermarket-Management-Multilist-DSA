# Supermarket Management System

This project implements a supermarket management system using a multi-list data structure. It provides functionalities for both users and administrators, allowing them to manage inventory, perform searches, update product details, and more.

## Features

- **User Login:** Users can log in as either regular users or administrators.
- **User Functions:**
  - Display product details
  - Search for a product
  - View the cart
  - Delete items from the cart
  - Checkout
- **Admin Functions:**
  - Update items (price or quantity)
  - Display all products
  - Delete items from inventory

## Code Structure

The code is written in C and utilizes structures to represent products, categories, and the shopping cart. Various functions such as insert, swap, sorting, printArray, search_item, update, price, delete, display, printArray_admin, and deleteadmin are implemented to manage products and cart operations.

## Data Format

Data is stored in a CSV file with the following format:

PID,IID,NAME,PRICE,EXPDATE,QTY
1,10,Soap,48,11-03-2024,20
1,11,Shampoo,100,14-03-2025,60


## Setup and Installation

1. **Clone the repository** git clone https://github.com/Maitri-Shekhda/supermarket-management-multilist-dsa.git
cd supermarket_managament-multilist-dsa
2. **Compile the code** gcc final.c -o inventory_system.
3. **Run the executable** ./inventory_system
4. **Follow the on-screen instructions** to interact with the system.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.


