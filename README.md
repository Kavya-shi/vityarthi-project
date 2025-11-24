# vityarthi-project
This is my first git Repository
Currency Converter
A simple and user-friendly command-line currency converter that converts between US Dollars (USD) and Indian Rupees (INR).

Features
Bidirectional Conversion: Convert USD to INR and INR to USD

Custom Exchange Rates: Set and update exchange rates as needed

Input Validation: Robust error handling for invalid inputs

User-Friendly Interface: Clear menu-driven interface with real-time rate display

Non-Negative Validation: Ensures only valid positive amounts are processed

Installation
Ensure you have Python 3.6 or higher installed on your system

Download or clone the repository containing the money_converter.py file

No additional dependencies required - uses only Python standard library

Usage
Running the Converter
bash
python money_converter.py
Program Flow
Initial Setup:

The program starts with a default exchange rate of 89.62 INR per 1 USD

You can keep the default rate or set a new one

Main Menu Options:

Option 1: Convert USD to INR

Option 2: Convert INR to USD

Option 3: Set a new exchange rate

Option 4: Exit the program

Input Requirements:

Amounts must be non-negative numbers

Exchange rates must be positive numbers

Invalid inputs will prompt for correction

Example Usage
text
--- Simple USD/INR Converter ---
--- Setup Exchange Rate ---
   Enter the new exchange rate (1 USD = ? INR) or press Enter to keep default (89.62): 85.50

 Conversion rate set: 1 USD = 85.50 INR

--- Current Rate: 1 USD = 85.50 INR ---
What conversion do you need?
1. USD to INR (Dollar to Rupee)
2. INR to USD (Rupee to Dollar)
3. Set New Exchange Rate
4. Exit
Enter your choice (1, 2, 3, or 4): 1
   Enter the amount you want to convert: 100
100.00 USD is equal to 8,550.00 INR.
Code Structure
Main Functions
usd_to_inr(amount_usd, rate): Converts USD to INR

inr_to_usd(amount_inr, rate): Converts INR to USD

get_valid_amount(): Validates user input for amounts

get_valid_rate(default_rate): Validates user input for exchange rates

currency_converter_tool(): Main program loop and interface

Global Variable
EXCHANGE_RATE: Stores the current conversion rate (default: 89.62)

Error Handling
The program includes comprehensive error handling for:

Non-numeric inputs

Negative amounts

Invalid menu choices

Zero or negative exchange rates

Customization
Modifying Default Rate
Change the EXCHANGE_RATE variable at the top of the file:

python
EXCHANGE_RATE = 85.00  # New default rate
Adding New Currency Pairs
The code can be easily extended to support additional currency pairs by:

Adding new conversion functions

Expanding the menu options

Adding additional rate variables

Technical Details
Language: Python 3

Dependencies: None (uses standard library only)

Compatibility: Cross-platform (Windows, macOS, Linux)

File: money_converter.py

Contributing
Feel free to fork this project and submit pull requests for:

Additional currency support

Enhanced user interface

Real-time exchange rate integration

Additional features

License
This project is open source and available under the MIT License.

Support
For issues or questions:

Check the input requirements

Ensure you're using a supported Python version

Verify numeric inputs are valid
