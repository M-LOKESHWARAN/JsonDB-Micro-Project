# JsonDB-Micro-Project

Student Enrollment Form Micro Project

Overview

This project is a Student Enrollment Form developed with HTML, JavaScript, and Bootstrap. The form allows users to enter student details, which are stored in a mock database represented as a JavaScript object. This form simulates basic CRUD operations (Save, Update, and Reset) and includes features like form validation, primary key uniqueness, and disabled/enabled states for inputs based on user interactions.

Features

Form Fields: Includes fields for Roll No, Full Name, Class, Birth Date, Address, and Enrollment Date.
Buttons:
Save: Saves a new student record.
Update: Updates an existing student record if the Roll No is already in the database.
Reset: Resets the form fields to the initial state.
Mock Database: Uses a JavaScript object (studentDB) to simulate a JSON-based database, allowing the addition and modification of student records without a real backend.

CRUD Operations:

Save: Adds a new student record if the Roll No does not already exist.
Update: Modifies an existing student record based on the entered Roll No.
Reset: Clears all fields and resets the form to its initial state.
Form Validation: Ensures all fields are filled before saving or updating data.
Responsive Design: Uses Bootstrap for styling, making the form responsive and easy to navigate.

How to Use:

Open the form by launching index.html in a web browser.
Enter Roll No in the form:
If the Roll No exists in the database, the form fields will populate with the student's existing data, enabling the Update and Reset buttons.
If the Roll No does not exist, the form fields are enabled for data entry, activating the Save and Reset buttons.
Enter or modify student data in the form fields.
Click Save to add a new student to the mock database or Update to modify an existing student's data.
Click Reset at any time to clear the form and return it to its initial state.

Mock Database:
{
    "token": "-1935843913|3223940520357615501|-1935843909",
    "cmd": "PUT",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
        "id": "1",
        "name": "Soniya",
        "email": "soniya@gmail.com",
        "mobileno": "9967825671"
    }
}

Usage:

Only the Roll No field is enabled initially. All other fields and buttons are disabled.
The cursor will automatically focus on the Roll No field.
Saving a New Record:

Enter a unique Roll No.
If the Roll No does not exist in the mock database, the form fields and Save button will be enabled.
Complete the remaining fields, ensuring no empty fields.
Click Save to add the record to the database.
Updating an Existing Record:

Enter an existing Roll No in the form.
If the Roll No exists, its associated data will be loaded into the form fields, with the Update and Reset buttons enabled.
Update any fields as needed.
Click Update to save changes to the database.
Resetting the Form:

Click Reset at any time to clear the form and reset it to its initial state.
Acknowledgments
This project uses Bootstrap for styling and is inspired by the requirements of a student enrollment system to demonstrate basic form handling and CRUD operations in a web application.

Acknowledgments
This project uses Bootstrap for styling and is inspired by the requirements of a student enrollment system to demonstrate basic form handling and CRUD operations in a web application.
