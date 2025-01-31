# Shopping Project

This is a simple shopping project that includes both user and admin functionalities. Below are the instructions to set up and run the project on your local machine.

## Prerequisites

- Web Server (e.g., XAMPP, WAMP, or MAMP)
- PHP (version 8.x or higher)
- MySQL

## Installation

1. **Download the Project:**
   - Download the project files and unzip them into your web server's root directory (e.g., `htdocs` for XAMPP).

2. **Create Database:**
   - Open your MySQL database management tool (e.g., phpMyAdmin).
   - Create a new database named `shopping`.

3. **Import Database:**
   - Import the provided SQL file (`/database/shopping.sql`) into the `shopping` database. This file contains all the necessary tables and data.

4. **Run the Project:**
   - Start your local web server (e.g., Apache in XAMPP).
   - Open your browser and navigate to:
     - **User Interface:** [http://localhost/shopping](http://localhost/shopping)
     - **Admin Panel:** [http://localhost/shopping/admin](http://localhost/shopping/admin)

## Login Details

### User Login
- **Username:** johndeo@gmail.com
- **Password:** Test@123

### Admin Login
- **Username:** admin
- **Password:** Test@123

## Project Structure

- **`assets/`:** Contains CSS, JavaScript, images, and other static files.
- **`admin/`:** Contains files for the admin panel.
- **`config/`:** Contains configuration files (e.g., database connection).
- **`database/`:** Contains the SQL file for database setup.
- **`includes/`:** Contains reusable PHP files (e.g., header, footer, functions).
- **`index.php`:** Main entry point for the user interface.

## Troubleshooting

- **Database Connection Issues:**
  - Ensure MySQL is running.
  - Verify the database credentials in the configuration file.
  - Check if the `shopping` database and tables are properly imported.

- **Page Not Found:**
  - Ensure the project is placed in the correct directory (e.g., `htdocs/shopping`).
  - Check if the `.htaccess` file is properly configured (if using URL rewriting).

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the MIT License.

---
