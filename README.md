# Shopping List Manager — Week 7 Assignment

## Part A: List Warmup
list_warmup.py demonstrates Python list operations, including indexing, append(), remove(), and len().

## Part B: Shopping List Manager
shopping_list.py allows users to add, remove, and display shopping items using an interactive menu.

## Part C: List Report
list_report.py displays a numbered shopping list, counts items with more than four letters, and finds the longest item name.

## Why Check Membership Before Removing an Item?

Checking if an item is in a list before calling remove() prevents the program from crashing. If the item does not exist, Python raises a ValueError. Using the `in` operator makes the program safer and allows it to display a helpful message.
