# Email Validator 📧

A simple Python program that checks whether an email address is valid using a Python validation library.

## About the Project

The program asks the user to enter an email address and checks whether the input follows a valid email format.

Instead of using regular expressions, the project uses the **validator-collection** library to validate the email address.

If the email is valid, the program prints:

```text
Valid
```

Otherwise, it prints:

```text
Invalid
```

The program only checks the format of the email address and does not verify whether the domain actually exists.

## How It Works

The program asks the user to enter an email address:

```text
Email: malan@harvard.edu
Valid
```

An incorrectly formatted email produces:

```text
Email: malan@@@harvard.edu
Invalid
```

## What I Practiced

* Using external Python libraries
* Installing packages with `pip`
* Email validation
* Input handling
* Boolean conditions
* Working with validation functions
* Avoiding regular expressions when a library can handle validation

## Technologies

* Python
* validator-collection

## Installation

Install the required package with:

```bash
pip install validator-collection
```

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
