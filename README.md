# python-challenge-1

## Groceries List

This challenge is about adding to provided code that displays a grocery store within the console. The coder is required to handle user inputs and do basic coding tasks such as: if else, casting, iterations, input validation, error handling, documentation etc. 

The goal of this challenge is to explore data structures such as lists and dictionaries, which we learned about during our lectures. 

## How to use:

This program works with the users terminal and does not have a GUI, as we are still in a primitive time of this class. Initially, the user will be greeted and then prompted with a list of choices of different menus. The class-provided code does this for us using a nested for loop:

``` 
for key in menu.keys():
        print(f"{i}: {key}")
        # Store the menu category associated with its menu item number
        menu_items[i] = key
        # Add 1 to the menu item number
        i += 1
```

The user then inputs a number (which is validated as part of our assignment), and their menu selection is saved. After this the user simply follows the instructions printed to the console, and forms their groceries list. 

Finally the user is given a receipt printed to the console with their items, quanities and costs displayed.


```
print("Item name                 | Price  | Quantity")
print("--------------------------|--------|----------")
```