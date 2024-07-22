# Student Registration Management

## Introduction

The **Student Registration Management** application is designed to assist universities in managing student registrations and administration records. It allows users to view and manage student details, including names, faculties, departments, and advisors.

## Features

### Administration Management (Tab 1)
- **Show Button**: Fetches and displays all administration records from the database.
- **Add Button**: Adds new administration records, with validation for input fields. Displays messages for errors and clears fields upon successful addition. Updates the spinner to reflect new records.
- **Delete Button**: Deletes the selected administration record, clears fields upon successful deletion, and updates the spinner.
- **Search Button**: Searches for administration records based on input and displays results in the list view.
- **Update Button**: Updates existing administration records and updates the spinner.

### Student Registration (Tab 2)
- **Register Button**: Registers a student with a generated 10-digit student ID. Clears the display or shows a toast message if information is missing. Populates the spinner with the newly registered student.
- **Update Button**: Updates existing student records and updates the spinner.
- **Show Button**: Fetches and displays all student records from the database.
- **Cancel Button**: Cancels student registration, validates information, and displays messages for errors.
- **Search Button**: Searches for registered students in the database.

### Registered Students (Tab 3)
- Displays a list of registered students along with details such as student ID, name, faculty, department, and advisor.

## Architecture

The application uses a tabbed interface to separate administrative management, student registration, and the display of registered students. The Java file handles the connection and functionality of buttons and tabs.
