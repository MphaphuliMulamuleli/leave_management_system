# Leave Management System

This is a Leave Management System project that runs on a local server using XAMPP. It is developed using PHP, HTML, CSS, and JavaScript.

## Project Overview

This web application allows employees to request leaves and managers to approve or reject those requests. It also provides an admin panel for managing user roles and leave policies. The system includes a backed-up database for storing user information, leave requests, and other relevant data.

## Technologies Used

- **PHP**: The server-side scripting language used for building the backend logic.
- **HTML**: For creating the web pages and forms.
- **CSS**: Used for styling the user interface.
- **JavaScript**: Enhances user interactivity and functionality.

## Running the Project

To run this project on your local machine, follow these steps:

1. Install XAMPP on your computer if you haven't already. You can download it from [https://www.apachefriends.org/](https://www.apachefriends.org/).

2. Clone this repository to your local machine:
3. Copy the project files to the XAMPP htdocs directory. The default directory is `C:\xampp\htdocs` on Windows.

4. Import the attached backed-up database into your local MySQL server. You can do this using phpMyAdmin, which is included with XAMPP.

5. Start XAMPP and ensure that Apache and MySQL services are running.

6. Open a web browser and navigate to `http://localhost/leave_management_system` to access the application.

## Database Setup

To import the backed-up database, follow these steps:

1. Open phpMyAdmin by visiting `http://localhost/phpmyadmin` in your web browser.

2. Create a new database called `leave_management_system`.

3. Click on the newly created database and choose the "Import" tab.

4. Click the "Choose File" button and select the backed-up database file provided.

5. Click the "Go" button to import the database schema and data.

## Project Structure

Here is a brief overview of the project directory structure:

- `index.php`: The main entry point of the application.
- `db_connect.php`: Contains the database connection code.
- `config.php`: Configuration settings for the application.
- `assets/`: Contains CSS and JavaScript files.
- `includes/`: Includes PHP files for various functionalities.
- `admin/`: Admin panel files for managing roles and policies.

Feel free to explore the code and customize the application to meet your specific requirements.

---

**Note:** Please make sure that XAMPP is properly configured on your machine before running this project.

For any questions or issues, please [create an issue](https://github.com/MphaphuliMulamuleli/leave_management_system/issues) on this repository.


