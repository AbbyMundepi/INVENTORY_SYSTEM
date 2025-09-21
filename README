Grocery Store Inventory System

Course Code: ENCS253
Course: Data Structures
Lab Assignment 1 — Arrays and Complexity Analysis

📌 Project Description

This project implements a simple Inventory Management System for a grocery store using C++ arrays.
The system supports:

Storing items (ItemID, ItemName, Quantity, Price)

Performing operations (insert, delete, search)

Managing price and quantity data using row-major and column-major ordering

Optimizing memory using sparse representation for rarely restocked products

The solution also includes time and space complexity analysis for each function.

⚙️ Features Implemented

Inventory Item ADT

Attributes: ItemID, ItemName, Quantity, Price

Methods: insertItem(), deleteItem(), searchItem()

Inventory Management System

Uses arrays to store items

Supports addItemRecord(), removeItemRecord(), searchByItem()

Manages Price-Quantity Table in row-major & column-major order

Implements Sparse Representation for rarely restocked products

Complexity Analysis

insertItem() → O(1)

deleteItem() → O(n)

searchItem() → O(n)

displayRowMajor() / displayColumnMajor() → O(n)

optimizeSparseStorage() → O(n)

🧑‍💻 How to Run

Clone the repository:

git clone <repo-link>
cd inventory-system


Compile the program:

g++ inventory.cpp -o inventory


Run the program:

./inventory

📊 Sample Output
Item inserted successfully.
Item inserted successfully.
Item inserted successfully.
Item inserted successfully.
Item inserted successfully.

Current Inventory:
101 | Rice | Qty: 50 | Price: 45.5
102 | Sugar | Qty: 30 | Price: 40
103 | Oil | Qty: 20 | Price: 120
104 | Salt | Qty: 4 | Price: 20
105 | Tea | Qty: 3 | Price: 150

Item Found: 102 - Sugar, Qty: 30, Price: 40
Item Found: 105 - Tea, Qty: 3, Price: 150
Item deleted successfully.

Current Inventory:
102 | Sugar | Qty: 30 | Price: 40
103 | Oil | Qty: 20 | Price: 120
104 | Salt | Qty: 4 | Price: 20
105 | Tea | Qty: 3 | Price: 150

Price-Quantity Table (Row-Major Order):
Item 1: 40 30
Item 2: 120 20
Item 3: 20 4
Item 4: 150 3

Price-Quantity Table (Column-Major Order):
Column 0: 40 120 20 150
Column 1: 30 20 4 3

Sparse Representation (Items with Quantity <= 5):
ItemID | Name | Qty | Price
104 | Salt | 4 | 20
105 | Tea  | 3 | 150
