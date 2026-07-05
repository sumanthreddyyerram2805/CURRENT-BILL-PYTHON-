# CURRENT-BILL-PYTHON-
# Electricity Bill Calculator

A simple Python program that calculates an electricity bill using slab-based pricing. The program accepts the customer's name and the number of units consumed, calculates the bill according to predefined rate slabs, and applies a **10% surcharge** when consumption exceeds **500 units**.

## Features

* Accepts customer name and units consumed
* Calculates bill using slab-wise rates
* Applies a 10% surcharge for usage above 500 units
* Console-based application
* Beginner-friendly Python project

## Technologies Used

* Python 3

## Tariff Slabs

| Units     | Rate                    |
| --------- | ----------------------- |
| 0–100     | ₹2/unit                 |
| 101–200   | ₹3/unit                 |
| 201–300   | ₹4/unit                 |
| 301–500   | ₹5/unit                 |
| Above 500 | ₹6/unit + 10% surcharge |

## Example

```
Enter name: Rahul
Enter units: 550

Final Amount is: 2860.0
```

## Concepts Used

* Variables
* User Input
* Conditional Statements (`if`, `elif`, `else`)
* Arithmetic Operations
* Output Formatting

## How to Run

1. Make sure Python 3 is installed.
2. Run the program:

   ```bash
   python electricity_bill.py
   ```
