
# Bank Management System

## Project Overview

This is a Java Swing-based Bank Management System application. It allows users to fill multi-page forms to create a bank account by entering personal and additional details. The system stores the form data into a database.


## Features

* Multi-page user form interface
* Input validation for important fields like PAN and Aadhar
* Database connectivity to store user details
* User-friendly GUI with dropdowns and radio buttons for selections
* Error handling with appropriate messages
* Navigation between form pages


## Changes Made After Guvi Comments

* Corrected class name typo `Connn` to `Conn` for database connection object creation.
* Fixed logic to correctly assign values for radio button selections for Senior Citizen and Existing Account options.
* Added null and empty input checks with proper error messages to ensure all required fields are filled.
* Improved combo box selections to retrieve selected values properly.
* Ensured next button navigates to the next form page (`Signup3`) after successful data submission.
* Adjusted GUI element placements and colors for better UI clarity and consistency.

## How to Run

1. Ensure you have Java JDK installed.
2. Import the project into an IDE like Eclipse or IntelliJ.
3. Set up the database and update the `Conn.java` file with your database credentials.
4. Run the `Signup1.java` (or your starting class) to begin the application.
5. Follow through the forms to input details and save data.

## Files Included

* Signup1.java – First page form for initial details
* Signup2.java – Second page form for additional details (focus of this submission)
* Signup3.java – Third page form for further details
* DBConn.java – Database connection class
* Other utility and resource files (icons, images)

## Screenshots
![IMG_20250524_222845](https://github.com/user-attachments/![IMG_20250524_222815](https://github.com/user-attachments/assets/4a02452d-85f8-43c0-913a-2b8f7c50a31a)
assets/8100be32-e0c9-43af-8ed8-738537449295)

![IMG_20250524_222957](https://github.com/user-attachments/assets/b33d9e5a-e011-4c07-a985-7cd7ab31aecd)

![IMG_20250524_222957](https://github.com/user-attachments/assets/c73844cf-0795-4a52-8fd3-c54faabd632b)

## Author

Ayush Raj Singh  
2nd Semester, B.Tech CSE  
Galgotias University
