# Library Management System (Tkinter-based GUI Application)

A simple Python-based Library Management System built using the `Tkinter` library. This application allows librarians to log in, register, and manage books by adding, removing, and issuing them. It also provides the functionality to view all available books in the library's inventory.

## Features

- **User Authentication**: 
  - Users can log in or register as librarians.
  - Username and password authentication with in-memory storage for quick access.

- **Book Management**:
  - **Add Book**: Librarians can add books to the library.
  - **Remove Book**: Books can be removed from the library if they are no longer available.
  - **Issue Book**: Books can be issued to borrowers, which moves them from the main book list to an "issued" list.
  - **View Books**: Displays all available books in a list format.

- **Error Handling**:
  - Alerts for invalid login credentials.
  - Messages for successful or unsuccessful book transactions (e.g., adding/removing/issuing).

## Usage

1. **Login/Register**: 
   - Enter a username and password to log in if you are already registered.
   - If not registered, enter a username and password and click "Register."

2. **Manage Books**:
   - After logging in, the user interface provides options to add, remove, issue, and view books.
   - Alerts and information messages guide the user through successful actions or errors.

## Code Structure

- **`__init__`**: Initializes the main window, sets up the login screen, and declares the lists for books and issued books.
- **`login()`**: Checks user credentials and grants access to the main library management screen if correct.
- **`register()`**: Allows new users to register with a username and password.
- **`library_management_screen()`**: Displays the main screen for managing books, including options for adding, removing, and issuing books.
- **`add_book()`**: Adds a new book to the library inventory.
- **`remove_book()`**: Removes a specified book if it exists in the library.
- **`issue_book()`**: Issues a specified book to a borrower and removes it from the library inventory.
- **`view_books()`**: Shows a list of all available books in the inventory.

## Prerequisites

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## Installation and Execution

1. Clone the repository or download the code file.
2. Run the application:
   ```bash
   python library_management.py
   ```
3. Use the GUI to log in/register and manage the library’s books.


## Future Enhancements

- Persistent storage of librarian credentials and book inventory using a database.
- Enhanced user interface with more functionalities.
- Support for managing book details (e.g., author, publication year, etc.).
## Contact  hanzalawaleed6@gmail.com
