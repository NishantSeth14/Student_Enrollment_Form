# Student Enrollment Form using JsonPowerDB

## Description

This project is a web-based HTML form for student enrollment that utilizes JsonPowerDB as the database. JsonPowerDB simplifies CRUD operations and offers a real-time database experience. The form allows for easy data retrieval in JSON format without the need for backend code or defining a schema. The Tech Stack used includes HTML, CSS, JavaScript, and JsonPowerDB.

## Illustrations

### UPDATE

If a student's roll number is already present in the database, the form fetches the existing information, allowing the user to update the student's details.

### SAVE

If the student's roll number is not in the database, the user can fill in the remaining fields and save the information to the database.

### CLEAR

This button clears all form fields except the roll number. Other fields are disabled until the user enters a valid roll number.

### ALERT

The website uses disposable alert prompts using Bootstrap for user notifications.

## How to Use

### Initial Setup

1. Enter a roll number.

### If Roll Number is Invalid

*Provide details on what happens if the roll number is not valid.*

### If Roll Number is Valid and Exists in the Database

*Explain the process of fetching student data using the roll number. If the student is present, the fields are filled with existing information.*

### Updation of Student Details

To update student details, input the roll number, and update the necessary information.

### Adding New Student Data

1. Enter a new roll number.
2. All other fields are enabled.
3. Fill in the student information.
4. Save the data to the database if the input is valid.

### If Input Data is Not Valid

*Describe the steps or alerts for handling invalid input data.*

## Installation

1. Clone the project to your local machine:

   ```bash
   git clone https://github.com/prashant-smart/Recommendation-system.git
   ```

2. After cloning, navigate to the `public_html` folder and then the `script` folder. In the `script.js` file, replace the `connectionToken` with your JsonPowerDB Connection Token.

## Sources

- Introduction to JsonPowerDB - V2.0 course on [Login2Explore](https://careers.login2explore.com/)
- [Bootstrap](https://getbootstrap.com/)

