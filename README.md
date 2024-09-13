# Restaurant Menu/Order Program

## Overview
This program simulates a menu ordering system for a restaurant, fundraiser, or anything related to food, merchandise, and buying items (originally meant as a fun project to aid in our fundraiser for a project we were doing!). It allows users to view the menu, enter food items they wish to order, and calculates the total cost of their order in the end! 

## Features
- **Menu Display**: Shows a list of 10 menu items with their prices.
- **Order Input**: Users can enter the names of the items they wish to order.
- **Total Calculation**: Calculates and displays the total cost of the order.

## Components
1. **Struct Definition**: Defines a `menu_item` struct with `item` (name) and `price`.
2. **Menu Array**: An array of `menu_item` structs to store the menu items.
3. **Functions**:
   - `add_items()`: Populates the menu array with predefined items and prices.
   - `get_cost(string item)`: Searches the menu array for the item and returns its price.

## Usage
1. **Compile and Run**: Compile the program using a C compiler and run the executable.
2. **View Menu**: The program displays the menu items and their prices.
3. **Enter Items**: Enter the names of the items you wish to order. Press enter on an empty line to finish.
4. **Total Cost**: The program calculates and displays the total cost of the entered items.

## Example
```
Welcome to ______ (your affiliation/organization)!!! 
Choose from the following menu to order. Press enter when done.

Burger: $9.50
Vegan Burger: $11.00
Hot Dog: $5.00
Cheese Dog: $7.00
Fries: $5.00
Cheese Fries: $6.00
Cold Pressed Juice: $7.00
Cold Brew: $3.00
Water: $2.00
Soda: $2.00

Enter a food item: Burger
Enter a food item: Fries
Enter a food item: 

Your total cost is: $14.50
```

![image](https://github.com/user-attachments/assets/34e310d2-99f9-4470-b9f9-7bb23728c12b)

## Notes
- The program uses a linear search method to find the price of each entered item.
- If an item is not found, it returns a price of $0.00.
