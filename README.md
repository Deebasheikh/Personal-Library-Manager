# Personal-Library-Manager
# Overview
The Personal Library Manager is a Python-based application that allows users to manage their book collection. The program allows the user to add, remove, search, and display books, as well as view statistics on the books they have read versus unread.

# Features
# Add a Book: 
Add a book to your library with details like title, author, year, genre, and whether you've read it.
# Remove a Book:
Remove a book from the library by its title.
# Search the Library:
Search for books based on the title or author.
# Display All Books: 
Display a list of all books in the library with their details (title, author, year, genre, and read status).
# Display Statistics:
View the total number of books in the library and the percentage of books marked as "read."
# Requirements
Python 3.x
No additional libraries required (uses built-in Python libraries json and os).
# How to Use
Clone the repository or download the Python file (library_manager.py).
Ensure you have Python installed on your system.
Run the Python script by executing the following command:
python library_manager.py
Follow the on-screen prompts to add, remove, search, or display books in your personal library.
# Available Options
When running the application, you'll see a menu with the following options:

# Add a book:
Enter the details (title, author, year, genre, read status) for a new book and add it to the library.
# Remove a book:
Remove a book from your library by specifying its title.
# Search the library: 
Search for books by title or author.
# Display all books:
View a list of all books in your library, along with their details.
# Display statistics: 
View the total number of books in your library and the percentage of books you’ve read.
# Exit:
Exit the program.
# File Storage
The book data is stored in a file called library.txt in the same directory as the script. The data is saved in JSON format, which allows for easy saving and loading between program runs.

# Example
✨Welcome to the Personal Library Manager📚✨
Menu
1.Add a book📘
2.Remove a book📘
3.Search🔎 the library
4.Display all books📘
5.Display statistics📊
6.Exit
Enter your choice: 1
Enter the title of the book: The Great Gatsby
Enter the author of the book: F. Scott Fitzgerald
Enter the year of the book: 1925
Enter the genre of the book: Fiction
Have you read the book? (yes/no): yes
Book The Great Gatsby added successfully.
# License
This project is open source and available under the MIT License.

