# cpp-contact-management-system
This repository implements a basic contact management system using C++ which allows users to manage contacts by adding, viewing, and deleting contact information.

---
## Overview

This repository contains a simple command-line contact management system written in C++. The system allows users to add, view, and remove contacts. It demonstrates basic C++ concepts like classes, vectors, and input/output operations.

## Features

*   **Add Contact:** Allows the user to add a new contact with a name and phone number.
*   **View All Contacts:** Displays all the contacts stored in the system.
*   **Delete Contact:** Allows the user to remove a contact by name.
*   **User-Friendly Interface:** Provides a simple and intuitive command-line interface.
*  **Basic Error Handling**: Handles some basic errors like user entering invalid option

## Project Structure

The project consists of the following files:

*   `main.cpp`: Contains the main function and the menu-driven loop that controls the application.
*   `PersonContact.h`: Header file for the `PersonContact` class, defining its interface.
*   `PersonContact.cpp`: Implementation file for the `PersonContact` class, which provides methods to manage contacts.

## Class Details

*   **`PersonContact` Class:**
    *   **Private Members:**
        *   `string contactName`: Stores the name of the contact.
        *   `long phoneNo`: Stores the phone number of the contact.
    *   **Public Methods:**
        *   `PersonContact()`: Default constructor.
        *   `PersonContact(string n, long p)`: Parameterized constructor that initializes contact with given name and number.
        *   `static void AddPerson(vector<PersonContact>& contactList)`: Adds a new contact to the given contact list by getting input from user.
        *   `static void ShowAll(const vector<PersonContact>& contactList)`: Prints all the contacts in the given contact list.
        *   `void printDetails() const`: Prints the details of an individual contact.
        *  `static void RemovePerson(vector<PersonContact>& contactList)`: Removes a contact from the list if it matches the user input.
