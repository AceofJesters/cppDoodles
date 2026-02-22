## Overview

The software will function as a cash register and keep an inventory file. The inventory file will be a database of all of the books in the bookshop.
The software will be able to:
* Calculate the total of a sale, including sales tax
* When a book is purchased, remove it from the shop's inventory file
* Add, change, delete, and search for books in the inventory file
* Display various reports

## Modules

Upon program startup, the user will be able to select which module they would like to access.

This software will have three modules, expanded upon below:
* Cashier module
* Inventory Database module
* Report module

### The Cashier Module

The cashier module will be able to calculate the total cost of a purchase.
The module takes the input of what books the customer is purchasing, and will output the total price of the sale.
> The final price will include sales tax
When books are purchased, the cashier module will remove the book from the store's inventory, as stored in the inventory database module (see below)

### The Inventory Database Module

The inventory database will be a file containing a list of all of the books in the bookstore's inventory.
##### The following information about each book will be stored: 
* ISBN: International Standard Book Number. A unique number assigned to each book by the publisher. Essentially, an index number.
* Title
* Author
* Publisher
* Data Added: The date that the book was added to the shop's inventory
* Quantity-On-Hand: The number of copies of the book in the shop's inventory
* Wholesale Cost: The price paid by Serendipity for the book
* Retail Price

##### The user will be able to:
* Look up information about any book in the database
* Add books to the database
* Remove books from the database
* Alter information about books in the database

### The Report Module

The report module will analyse information stored in the database module to produce reports concerning the following: 
* Inventory list: A list of the shop's current inventory
* Inventory wholesale value: The wholesale value of each individual book in the inventory and the sum of each book's wholesale value
> Developer's note: Make a column for the wholesale value of each individual book and every book with the same index number collectively
* Inventory retail value: The same information and layout as the inventory wholesale value report, but for the retail value of the books
* List by quantity: A list of all of the books in inventory sorted by how many iterations of each book are in the database
> Sorted greatest to least
* List by cost: A list of all of the books in inventory sorted by wholesale cost
> Sorted greatest to least
* List by age: A list of all of the books in inventory sorted by date added
> Oldest to newest