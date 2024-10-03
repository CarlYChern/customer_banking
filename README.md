# Customer Banking   
Repository: customer_banking

Files: customer_banking.py  main function
       Accounts.py  Account class
       savings_account.py savings account function
       cd_account. py     cd account function     

## What it does

* Adapt menu to allow customers to place an order.
* This includes storing the customer order and printing
the receipt with the total prices of all items ordered.

## Overview
* Print menu - code already provided.
* Order system - new code.
* Order receipt - new code.

## Coding overview
* Dictionary: menu is a dict of dict.
* Dictionary: menu_items creates a dictionary to store the menu for
              later retrieval.
* Dictionary: selected_item
* List: customer_order is a  list of dict
* Variables: long list including place_order (bool), i (int), and
            menu_category (str)

## Coding notes
* Includes: while True, for loops, if else, and match: case
    
## Small sample program output

Enter you savings balance: 1000
Enter your interest rate: 3
Enter the duration in months: 3
Interested earned on savings: $ 7.50
Updated savings account baance: $ 1,007.50


Enter you CD balance: 5000
Enter you interest rate: 5
Enter the duration in months: 36
Interested earned on savings: $ 750.00
Updated savings account balance: $ 5,750.00
