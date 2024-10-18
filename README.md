# Coffee Machine ☕️

A simple object-oriented Python program that simulates a coffee machine. The coffee machine offers a menu of drinks, processes payments, checks resources, and makes coffee. You can also view reports on resources and money.

## Features
- **Menu Options**: Choose from available drinks or view a report on resources and money.
- **Payment System**: The program ensures you have enough money before making your drink.
- **Resource Management**: Checks if enough resources (water, milk, coffee) are available before making the drink.
- **Easy to Use**: Command-line interface with clear options.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/coffee-machine.git
   cd coffee-machine
   ```

2. Make sure the following files are in your project directory:
   - `menu.py`
   - `coffee_maker.py`
   - `money_machine.py`

3. Run the Python script:
   ```bash
   python main.py
   ```

## Available Options

- Type `off` to turn off the machine.
- Type `report` to get a resource and money report.
- Choose a drink (e.g., "latte", "espresso", etc.) from the menu to get your drink!

## Files Overview

- **`menu.py`**: Handles the drink menu and drink selection.
- **`coffee_maker.py`**: Manages resources and the coffee-making process.
- **`money_machine.py`**: Handles money transactions and payment processing.

## Example Usage

```
What would you like to have? (espresso/latte/cappuccino): latte
Please insert coins.
How many Tens?: 0
How many Twenties?: 1
How many Fifties?: 0
How many Hundreds?: 1
Here is your latte ☕️. Enjoy!
```
