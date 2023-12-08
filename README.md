# Library Management System

This is a simple console-based Library Management System implemented in C++. It allows you to manage a library catalog of books. Each book in the catalog has a title, an author, an ISBN, and an availability status.

## Features

The system provides the following features:

1. **Add Book**: This feature allows you to add a new book to the library catalog. You will be prompted to enter the book's title, author, and ISBN. The availability of the newly added book is set to true by default.

2. **Remove Book**: This feature allows you to remove a book from the library catalog. You can remove a book by its title or ISBN.

3. **Check Availability**: This feature allows you to check the availability of a book. You can check a book's availability by its title or ISBN.

4. **Display Catalog**: This feature allows you to view the entire library catalog. It displays the title, author, ISBN, and availability of each book in the catalog.

5. **Exit**: This feature allows you to exit the program.

## Usage

To use the system, simply run the program. You will be presented with a menu of options. Enter the number corresponding to the option you want to select. If you want to add a book, for example, enter `1`. If you want to exit the program, enter `5`.

Please note that this is a console-based system, so it does not persist data between runs. If you exit the program, any books you added during your session will not be saved. If you want to save your data, you will need to implement a data persistence layer.

## Code Structure

The code is structured around a `Book` struct and a `libraryCatalog` vector. The `Book` struct represents a book, and the `libraryCatalog` vector represents the library catalog. The `addBook`, `removeBook`, `checkAvailability`, and `displayCatalog` functions manipulate the `libraryCatalog` vector. The `main` function provides the user interface. 

## Dependencies

This program uses the `<iostream>`, `<vector>`, and `<string>` standard libraries. It does not have any external dependencies. 

## Compilation

You can compile this program using any C++ compiler. If you're using the GNU Compiler Collection, you can compile the program with the following command:

```bash
g++ library_management_system.cpp -o library_management_system
```

You can then run the program with the following command:

```bash
./library_management_system
```
