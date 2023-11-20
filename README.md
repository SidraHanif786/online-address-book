# Online Address Book

## Problem Statement

Design and implement an online address book using linked lists to keep track of the information related to family members, close friends, and business associates. The address book should store names, addresses, email addresses, phone numbers, and dates of birth. The program should support various operations, including data loading, sorting by first name, searching, printing details, birthday filtering, city-based filtering, and categorization. Additionally, the program should allow inserting, deleting entries, and saving data to a file on program termination.

## Guidelines

### A. Class `addressType`

Define a class `addressType` to store house number, street address/society, city, and country. Utilize appropriate functions for printing and storing the address, and employ constructors for automatic initialization of member variables.

### B. Class `extPersonType`

Define a class `extPersonType` using the classes `personType` (containing first and last names), `dateType` (with day, month, and year), and `addressType` (as defined in part A). Add member variables for phone number, email address, and a classification variable for family, friend, or business associate. Override functions for printing and storing relevant information, and use constructors for automatic variable initialization.

### C. Class `addressBookType`

Define the class `addressBookType` using the previously defined classes (`personType`, `dateType`, and `addressType`). Implement this class using linked lists as an Abstract Data Type (ADT) with class templates for nodes. This design allows processing an arbitrary number of entries.

### D. Operations

- Load data into the address book from a file.
- Sort the address book by first name.
- Search for a person by first name.
- Print details of a given person (address, phone number, email, and date of birth).
- Print names of people with birthdays in a given year.
- Print names of people belonging to the same city.
- Print names based on user's request (family members, friends, or business associates).
- Insert a new entry to the address book.
- Delete an entry from the address book.
- Save data to a file on program termination.
