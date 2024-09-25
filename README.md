Restaurant Management System

This project is a simple Restaurant Management System built using Python's Tkinter library for the GUI. The system helps to manage food orders, calculate the total cost, service charge, and tax, and display the final bill for customers.
Features

    Order Management: Allows the user to enter the quantity of various food items.
    Cost Calculation: Automatically calculates the cost of individual items and the total cost.
    Service Charge and Tax Calculation: Includes a 10% service charge and 5% tax on the total cost.
    Reset and Exit Functions: Reset the order form or exit the application.
    Interactive GUI: Easy-to-use graphical interface with buttons and entry fields for input.

Technologies Used

    Python
    Tkinter (for the GUI)

Clone
git clone https://github.com/eugenius-watchman/restaurant_app.git

python restaurant_app.py

    Make sure Python and Tkinter are installed on your system.

Usage

    The user can input the quantity of various food items like Waakye, Rice, Plantain, Meat, etc.
    Clicking on PRICE calculates the total cost of the items.
    Clicking on TOTAL adds the service charge and tax and displays the final bill.
    The RESET button clears all input fields, and the EXIT button closes the application.

Code Overview

    calculate_price: Computes the cost based on item quantities and updates the cost field.
    calculate_total: Adds service charge and tax to the total cost.
    reset: Resets all input fields to default values.

License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.
Contributing

    Fork the repository.
    Create a new branch for your feature (git checkout -b feature-branch).
    Commit your changes (git commit -m 'Add some feature').
    Push to the branch (git push origin feature-branch).
    Open a pull request.


