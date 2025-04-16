# Basic-Password-Generator

## Description

This is a Python program that generates random passwords based on user-specified criteria.  The program asks the user for:

* The number of letters they want in their password.
* The number of symbols they want.
* The number of numbers they want.
* Whether they want an "easy" or "hard" password.

For an "easy" password, the characters are concatenated in the order: letters, symbols, numbers.  For a "hard" password, the characters are randomly shuffled.

## Features

* Customizable Password Length:** Users can specify the desired length of the password by setting the number of letters, symbols, and numbers.
* Choice of Complexity:** The program offers two options for password complexity:
    * Easy: Characters are combined in a predictable order.
    * Hard: Characters are randomly shuffled for stronger security.
* Random Character Selection:** The program uses the `random.choice()` function to select characters randomly from predefined lists.
* Uses Python Lists:** The "hard" mode efficiently uses Python lists and the `random.shuffle()` function.
* Clear Output:** The generated password is printed to the console.
* Error Handling:** Handles invalid input for the easy/hard option.

## How to Use

1.  Make sure you have Python installed on your system.
2.  Save the code as a Python file (e.g., `password_generator.py`).
3.  Open a terminal or command prompt.
4.  Navigate to the directory where you saved the file.
5.  Run the script using the command `python password_generator.py`.
6.  The program will prompt you to enter the desired number of letters, symbols, and numbers.
7.  The program will ask you to choose between "easy" (0) and "hard" (1) password.
8.  The program will then display the generated password.
