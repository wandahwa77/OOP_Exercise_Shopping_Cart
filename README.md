# Object Oriented Shopping Cart 

## Introduction

In this lab, you will be building a **Shopping Cart** using **Object-Oriented Programming (OOP)** principles in Python. The goal is to create a cart that can manage various items with different quantities and prices, calculate discounts, track the items added, and void transactions if necessary.

This project will help you deepen your understanding of classes, instance methods, attributes, and how to organize a program using OOP concepts.

## Objectives

By completing this lab, you will be able to:

- Define and call **instance methods**.
- Define and access **instance attributes**.
- Call instance methods inside other instance methods.
- Create methods that calculate statistics of the attributes of an object.
- Create a domain model using **Object-Oriented Programming (OOP)**.

## Technologies Used

- **Python 3.x** (or any version you're using)
- Basic knowledge of **Object-Oriented Programming** (classes, methods, attributes)

## Setup and Installation

### Prerequisites

- Make sure you have Python 3.x installed. You can download it from the official site [here](https://www.python.org/downloads/).

### Steps to run the project:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/shopping-cart-lab.git
   ```

2. Navigate to the project directory:

   ```bash
   cd shopping-cart-lab
   ```

3. Open the `shopping_cart.py` file to modify and experiment with the code.

4. You can test your class by creating instances and calling the defined methods inside a Python interactive shell or another script.

## Usage

Once you have the project set up, you can start using the shopping cart by creating an instance of the `ShoppingCart` class and adding items to it. Here’s an example:

```python
# Create an instance of the shopping cart
cart = ShoppingCart()

# Add items to the cart
cart.add_item('Apple', 3, 0.5)  # (item name, quantity, price)
cart.add_item('Banana', 2, 0.3)

# Calculate the total price of the items in the cart
cart.calculate_total()

# Apply a discount
cart.apply_discount(10)  # Apply 10% discount

# Print out the cart contents
cart.print_receipt()

# Void the transaction if needed
cart.void_transaction()
```

Make sure you define all the required methods (e.g., `add_item`, `calculate_total`, `apply_discount`, `print_receipt`, `void_transaction`) as described in the instructions above.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request. Here are the basic steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Commit your changes and push them to your fork.
5. Submit a pull request to the main repository.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Additional Information

- Ensure that when you modify the `shopping_cart.py` file, you reinitialize your class instance to see the changes.
- You can experiment with the cart by adding various items, applying discounts, and checking how the total price is calculated.
  
---

This structure covers all the basics for a GitHub README. You can modify it as needed, depending on additional features or instructions you'd like to include. Let me know if you need any other sections added or modified!
