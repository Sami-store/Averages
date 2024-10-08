The AverageWithMethods program is designed to prompt the user to enter a series of numbers (between five to ten), calculate their average, and display the results in various formats. The program utilizes multiple methods for structured functionality.
Method Overview

    Print Description Method:
        Prints a brief description of the program to the user.

    Get Numbers Method:
        Prompts the user for input and collects five to ten numbers entered on a single line, separated by spaces.
        Utilizes a Scanner object to read input.
        Validates that the number of inputs is between five and ten. If the input is invalid, the program prints an error message and exits.
        Returns a String of the numbers separated by spaces.

    Calculate Average Method:
        Takes a String (the input numbers) as an argument and calculates the average.
        Uses a Scanner to parse the String and reads each number using a while loop.
        Returns the calculated average as a double.

    Print Results Method:
        Accepts a String of numbers and a double (the calculated average) as arguments.
        Prints the results in the format: "The average of the numbers [numbers] is [average]." with the average displayed as a whole number, a decimal, and with two decimal places.

Program Flow

    Main Method:
        Calls the method to print the program description.
        Calls the method to get the numbers from the user.
        Calls the method to calculate the average of those numbers.
        Calls the method to print the results.
