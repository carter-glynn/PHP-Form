#  PHP and Databases<br>
## Goal <br>

 - Build an HTML/CSS/PHP website which takes feedback and inserts the data into tables
 - Use PHP with XAMPP to make a local server that can host PHP files
 - Develop skills with user input using $_POST
 - Create a relational database and develop skills with SQL statements

## Description <br>

1. Create four html files named index.html, feedback.html, project.html, and about.html. Include appropriate elements as needed. The content within each file using appropriate html elements such as \<html\>, \<head\>,\<body\>, \<section\>, \<header\>, and \<footer\>. Each page must be navigable by a nav menu.
2. Modify the feedback.html file by the following: <br>
 - Add a form with appropriate labels and with following client-side validated inputs fields:
   - Name: At least one letter is required and accepts upper and lower case letters.
   - Email: Required and accepts only Conestoga College email addresses.
   - Postal Code: Required and accepts a valid postal code.
   - Message: Optional and accepts no more than 200 characters.
   - "Send” button: Submits the form performing indicated HTML5 validations.
   - “Reset” button: Clears all input fields.
 - Before form data is submitted, the form has following behaviour.
   - When the html file is accessed, first input field gets the focus.
   - When any input field is in focus, its background colour is changed to aqua. Once valid data is entered in a field, its background colour is changed to lime.
   - After the submit button is clicked, the form data is processed by a php file that displays the data (name and value pairs) in tabular form with a different colour for even numbered rows.
   - Use CSS to move navigation list (created in Assignment 1) to the left of the form. The list should cover approximately 25% of page width. Do not use a table to perform this formatting.
3. Create another file with a form with appropriate labels to collect name, email, postal code, and a message. Perform the following validations using server-side code and display appropriate error messages upon form submission for any failed validation(s).
 - Name: At least one letter is required and accepts upper and lower case letters.
 - Email: Required and accepts only Conestoga College email addresses.
 - Postal Code: Required and accepts a valid postal code.
 - Message: Optional and accepts no more than 200 characters.
4. Create a database containing a feedback table. This table contains data for the form created. Choose appropriate data types for the columns and choose an appropriate primary key. Save all SQL code in a text file.
5. Using PHP, in response to “Send” button click, insert data collected from the form into the table. Add another web-page to select and display all data in the feedback table. Data should be displayed in tabular format. The table cells should have borders. This page can be used to verify the successful submission of the form.

