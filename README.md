# cos101-mvc-calculator
# Python MVC Calculator

This project is a calculator built in Python using the MVC architecture.

Features
- Addition
- Subtraction
- Multiplication
- Division
- Clear function

Technologies
- Python
- Tkinter GUI
- MVC Design Pattern


# Model ('model/calculator_model.py')
It's the brain of the calculator.  It handles all mathematical calculations:

 Addition, subtraction, multiplication, division

 square root («sqrt»)

 Puissance ("power")

 Module ("modulo")

 History of operations

 MODEL does not manage the display of results.  It only performs calculations.
 
# Error Handling
The program protects against:

 Division by zero → clear the error message

 Square root of a negative number → clear the error message

 Modulo par zero → clear the error message

 Enter text instead of a number → the program prompts you again to enter text

 # View ('view/calculator_view.py')
 Here is the program interface. The eye handles everything the user sees and enters:

Display the menu
Ask the user for a number
Display the results
Display error messages
Display the calculation history
VIEW performs no calculations. It simply displays information.

# Controller ('controller/calculator_controller.py')
Consult the MODEL and VIEW configuration. It specifies:

Receiving user selections in the VIEW

Calling the appropriate operation in the MODEL

Returning results to the VIEW for display

Handling potential errors

# Technology used
Language: Python 3

Model: 'math' (Python standard library)

Test: 'unittest' (Python standard library)

Architecture: MVC (Model-View-Controller)

# Author
 Bigord Abnerson, Janvier Marc Duverson, Wydlyn Charles, Laveus Berns, Cledanor Montini
