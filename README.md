# Railway Management System

## Overview
The Railway Management System is a comprehensive Java-based application designed to manage railway reservations, including booking tickets, managing trains, and handling customer and admin information. The system provides functionalities for both customers and administrators, allowing users to book tickets, manage train details, and handle user accounts.

## Features

### Admin Features
- **Admin Registration and Login**: Admins can register and log in to the system using their credentials.
- **Train Management**: Admins can add, edit, and remove trains, including setting train capacity and seat details.
- **Ticket Management**: Admins can add, edit, and remove tickets, including setting ticket prices, seat numbers, and trip details.
- **Customer Management**: Admins can remove customer accounts.
- **View Trains and Tickets**: Admins can view all available trains and tickets in the system.

### Customer Features
- **Customer Registration and Login**: Customers can register and log in to the system using their credentials.
- **Ticket Booking**: Customers can search for available tickets based on date, departure, and destination, and book tickets.
- **Ticket Details**: Customers can view ticket details and generate a PDF of their ticket information.
- **Logout**: Customers can log out of the system.

## Technologies Used
- **Java**: Core programming language used for the application.
- **Swing**: Used for building the graphical user interface (GUI).
- **MySQL**: Used for database management (as indicated by the MySQL connector dependency).
- **iTextPDF**: Used for generating PDFs of ticket details.
- **Jackson**: Used for JSON serialization and deserialization.
- **JCalendar**: Used for date picker functionality in the GUI.

## How to Run the Project
1. **Prerequisites**: Ensure you have Java JDK 17 installed on your system.
2. **Clone the Repository**: Clone the project repository to your local machine.
3. **Build the Project**: Use Maven to build the project. Run the following command in the project directory:
   ```bash
   mvn clean install
   ```
4. **Run the Application**: Execute the `Main.java` file to start the application.
   ```bash
   java -cp target/classes railway.Main
   ```
5. **Use the Application**: 
   - Admins can log in to manage trains, tickets, and customer accounts.
   - Customers can register, log in, and book tickets.

## Screenshots
![Customer Booking System](https://github.com/user-attachments/assets/1db1391f-e972-446f-ac3b-7702a9743168)
![Admin Management System](https://github.com/user-attachments/assets/2fdebd98-5196-41ac-bc9c-321d353c5edc)
![Admin Login](https://github.com/user-attachments/assets/191fdd45-e022-40e0-99ae-84ea06a2ff92)
![Customer Login](https://github.com/user-attachments/assets/19e0b8a8-7796-4ab5-b2fc-6803b6604216)

## Time for Development
- **3 Weeks**: The project was developed over a period of 3 weeks by a single developer.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or issues, please contact the developer at [fady@gmail.com](mailto:fady@gmail.com).
```

This `README.md` provides a comprehensive overview of the project, including its features, technologies used, project structure, and instructions on how to run the application. It also includes placeholders for screenshots and contact information.
