# Takeout Restaurant Order System

## Description

The Takeout Restaurant Order System is a Python application that allows customers to view a menu, place an order, and receive an itemized receipt—all via the command line. This project is designed with accessibility in mind for customers with hearing and vocal impairments, enabling them to place their orders without the need for direct verbal communication. The project leverages core Python concepts such as conditionals, loops, functions, list comprehensions, and data structures (dictionaries and lists) to manage menu items and orders.

![Takeout Restaurant](https://github.com/user-attachments/assets/79c5d4e9-9328-4200-8795-72082033a177)

## Technologies Used

### Programming Language
- Python 3.x

### Concepts and Techniques
- Conditionals & Loops
- Functions and List Comprehensions
- Data Structures (Dictionaries and Lists)

## Table of Contents

- [Description](#description)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/takeout-restaurant-order-system.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd Develop
   ```
3. **(Optional) Create and activate a virtual environment**
   ```bash
   python3 -m venv env
   source env/bin/activate # On Windows use: env\Scripts\activate
   ```
4. **Run the Program**
   ```bash
   python3 order_menu_system.py
   ```

## Usage

When you run the program, you'll be guided through a simple ordering process. Follow these steps to place your order:

1. **View the Menu:**  
   Upon launching the application, a welcome message is displayed along with a list of available menu items. Each item is presented with a unique number, its food category, meal name, and price.

2. **Place an Order:**  
   - Type the number corresponding to the menu item you wish to order.
   - When prompted, enter the quantity you desire. If an invalid quantity is provided, the system will default the quantity to 1.

3. **Continue Ordering:**  
   After adding an item to your order, you'll be asked if you want to continue:
   - Enter any key to continue ordering.
   - Type `n` or `N` to finish your order.

4. **View Receipt:**  
   Once you indicate that you are done ordering, the system displays an itemized receipt that includes:
   - Each ordered menu item along with its price and quantity.
   - The total cost of your order.

## Features

- **Interactive Menu:**  
  Displays a neatly formatted menu with unique numbers, food categories, meal names, and prices.

- **Flexible Ordering:**  
  Allows customers to order multiple items with custom quantities, while handling invalid inputs gracefully.

- **Error Handling:**  
  Provides clear error messages for invalid menu selections or quantities, ensuring a smooth user experience.

- **Itemized Receipt:**  
  Generates a detailed receipt that lists all ordered items, their individual costs, quantities, and the overall total price.

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! To contribute to this project:

1. **Fork the repository.**
2. **Create a new branch:**

   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit your changes:**
   ```bash
   git commit -m "Add feature/YourFeature"
   ```
4. **Push to your branch**
   ```bash
   git push origin feature/YourFeature
   ```
5 **Open a pull request with a clear description of your changes**

## Questions

If you have any questions or need further assistance, please feel free to contact:

- **GitHub:** [Sinnema1](https://github.com/Sinnema1/menu-order-system)
- **Email:** test@test.com
