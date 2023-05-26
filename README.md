# Stock Management

This is a console-based inventory management system implemented in C#. It allows users to manage and track products in the inventory. Below is an overview of the program:

Program Overview
The program consists of a single class named Program within the BrandsStockManagement namespace. It includes the main entry point (Main method) where the execution of the program starts.


Functionality
User is prompted to choose an apparel type from the available options (Tshirt, Jeans).
The selected apparel type is used to retrieve the corresponding IApparel object from the ApparelFactory class.
The user is then prompted to enter the quantity of products to add to the inventory.
For each product, the user is prompted to enter the product code, name, quantity, and price.
The entered product information is used to create a Product object, which is added to a list of products (productsList).
The list of products is then added to the inventory using the AddProductsToInventory method of the Inventory class.
The current inventory is displayed using the DisplayInventory method of the Inventory class.
The user is prompted to enter a product code to remove a product from the inventory. The product is removed using the RemoveProduct method of the Inventory class.
The updated inventory is displayed.
The user is prompted to enter a product code to update the quantity of a product in the inventory. The quantity is updated using the UpdateQuantity method of the Inventory class.
The updated inventory is displayed.
The user is prompted to enter a product code to add the corresponding product to the cart. The AddtoCart method of the Inventory class is used to add the product to the cart.
The updated inventory is displayed.
The processes (operations performed) on the inventory are displayed using the DisplayProcesses method of the Inventory class.

Getting Started
To run the program, follow these steps:

Ensure you have a C# development environment set up (e.g., Visual Studio).
Copy the code provided into a new C# console application project.
Build and run the project.

Note
This program assumes the existence of additional classes (IApparel, ApparelFactory, Product, Inventory) and their respective implementations. However, the code provided only includes the Program class, which contains the main logic of the program.

Please note that the above content is generated based on the provided code. It provides an overview of the program's functionality and instructions on how to run it.
