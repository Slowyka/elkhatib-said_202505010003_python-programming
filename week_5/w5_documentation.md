# Week 5 Tutorial 5 Documentation

## 1. Define the problem statement
A small cafe needs a simple Python program to calculate customer bills automatically. The cashier currently calculates the total manually, so this program will help calculate the total price based on the quantity of items ordered.

## 2. What are the inputs?
The inputs are:
- Customer name
- Coffee quantity
- Tea quantity
- Sandwich quantity

## 3. What are the outputs?
The output is a receipt that shows:
- Customer name
- Coffee quantity
- Tea quantity
- Sandwich quantity
- Total bill in RM

## 4. What would be the typical process flow?
1. Ask the user to enter the customer name.
2. Ask the user to enter the quantity of coffee, tea, and sandwich.
3. Calculate the total bill using the item prices.
4. Print the receipt.

## 5. What are the constraints?
- Coffee price is RM 8.50.
- Tea price is RM 6.00.
- Sandwich price is RM 12.00.
- Quantities must be whole numbers.
- Quantities should not be negative.

## 6. How do you decompose the problem into smaller tasks?
The problem can be divided into smaller tasks:
1. Get input from the user.
2. Calculate the total bill.
3. Print the receipt.
4. Run the main program.

## 7. Pseudocode

START

SET coffee price = 8.50  
SET tea price = 6.00  
SET sandwich price = 12.00  

INPUT customer name  
INPUT coffee quantity  
INPUT tea quantity  
INPUT sandwich quantity  

CALCULATE total = coffee quantity * coffee price + tea quantity * tea price + sandwich quantity * sandwich price  

PRINT receipt  
PRINT customer name  
PRINT coffee quantity  
PRINT tea quantity  
PRINT sandwich quantity  
PRINT total  

END