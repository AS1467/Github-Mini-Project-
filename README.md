# Subscriber Management System

This project is a simple console-based application written in C that manages subscriber records. It was developed as a part of the curriculum and demonstrates basic file operations and data management in C.

## Features

- **Add Records**: Allows adding new subscriber records.
- **List Records**: Displays a list of all subscriber records.
- **Modify Records**: Enables modifying existing subscriber records.
- **Delete Records**: Allows deleting subscriber records.
- **Search Records**: Provides functionality to search for subscriber records by phone number.
- **Process Payments**: Manages payment transactions for subscribers.

## Usage

Upon running the program, you will be presented with a menu to choose from the available operations. Select an option by pressing the corresponding key.

### Menu Options:

- `A` : Add new records
- `L` : List all records
- `M` : Modify records
- `P` : Process payments
- `S` : Search records
- `D` : Delete records
- `E` : Exit the application

### Example Workflow

1. **Adding a Record**
   - Select `A` from the menu.
   - Enter the phone number, name, and amount for the new subscriber.
   - The record is saved to the file.

2. **Listing Records**
   - Select `L` from the menu.
   - All subscriber records are displayed.

3. **Modifying a Record**
   - Select `M` from the menu.
   - Enter the phone number of the subscriber to modify.
   - Update the details as needed.

4. **Deleting a Record**
   - Select `D` from the menu.
   - Enter the phone number of the subscriber to delete.
   - The record is removed from the file.

5. **Searching for a Record**
   - Select `S` from the menu.
   - Enter the phone number to search.
   - The corresponding record is displayed if found.

6. **Processing a Payment**
   - Select `P` from the menu.
   - Enter the phone number of the subscriber.
   - Enter the payment amount.
   - The subscriber's amount is updated accordingly.

## Project Structure

- **main.c**: The main source file containing the implementation of the subscriber management system.
- **file.ojs**: The data file used to store subscriber records.

## Requirements

- A C compiler (e.g., GCC)
- A Windows environment (due to the use of `<conio.h>` and `<windows.h>`)

## How to Compile and Run

1. Open a terminal or command prompt.
2. Navigate to the project directory.
3. Compile the program using a C compiler, for example:
4. Run the compiled executable:


## Acknowledgments

This project was uploaded as a part of the curriculum and serves as an educational example of file operations and data management in C.
