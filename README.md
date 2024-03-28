# python-challenge-1

## Groceries List

This challenge is about adding to provided code that displays a grocery store within the console. The coder is required to handle user inputs and do basic coding tasks such as: if else, casting, iterations, input validation, error handling, documentation etc. 

The goal of this challenge is to explore data structures such as lists and dictionaries, which we learned about during our lectures. 

## How to use:

This program works with the users terminal and does not have a GUI, as we are still in a primitive time of this class. Initially, the user will be greeted and then prompted with a list of choices of different menus. The class-provided code does this for us using a nested for loop:

### Provided code:
``` 
for key in menu.keys():
        print(f"{i}: {key}")
        # Store the menu category associated with its menu item number
        menu_items[i] = key
        # Add 1 to the menu item number
        i += 1
```

The user then inputs a number (input is validated as part of our assignment), and their menu selection is saved. After this the user simply follows the instructions printed to the console, and forms their groceries list. i.e.
```
From which menu would you like to order? 
1: Snacks
2: Meals
3: Drinks
4: Dessert
```

The user is then simiarly prompted with the items within each subcategory and their respective prices:
```
You selected Dessert
What Dessert item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Chocolate lava cake      | $10.99
2      | Cheesecake - New York    | $4.99
3      | Cheesecake - Strawberry  | $6.49
4      | Australian Pavlova       | $9.99
5      | Rice pudding             | $4.99
6      | Fried banana             | $4.49
```

## Input validation example
```
From which menu would you like to order? 
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 6
6 was not a menu option.
```

Finally the user is given a receipt printed to the console with their items, quanities and costs displayed.


```
print("Item name                 | Price  | Quantity")
print("--------------------------|--------|----------")
```