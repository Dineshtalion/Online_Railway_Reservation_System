# Online Railway Reservation System

## Overview

- The Online Railway Reservation System is a web application that allows users to book railway tickets easily. It provides functionalities for searching trains, booking tickets, and managing reservations, all through a user-friendly interface.

## Features

- **User Registration and Login**: Users can create accounts and log in to access their profiles.
- **Train Search**: Search for trains based on source, destination, and date of travel.
- **Ticket Booking**: Users can book tickets for selected trains.
- **Cancellation**: Users can cancel their bookings if needed.
- **Admin Panel**: Admin users can manage train schedules, view bookings, and handle user accounts.

## Tech Stack

- **Frontend**:
  - HTML
  - CSS
  - JavaScript
  - Bootstrap (for responsive design)

- **Backend**:
  - PHP

- **Database**:
  - MySQL (managed via phpMyAdmin)


## Getting Started

### Prerequisites

- PHP (version 7.0 or higher)
- MySQL
- phpMyAdmin for database management

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Vishnu-Kumar127/Online-Railway-Reservation-System.git
2. Navigate to the project directory:
   ```bash
   cd Online-Railway-Reservation-System

3. Set up the database:

    - Open phpMyAdmin in your browser (usually at http://localhost/phpmyadmin).
    - Create a new database (e.g., railway_reservation).
    - Select the newly created database.
    - Go to the "Import" tab.
    - Choose the database/database.sql file from the repository and click "Go" to import it.
    - Update the db.php file with your database 
4. Start the web server and access the application in your browser:
    ```bash
    http://localhost/Online-Railway-Reservation-System/

## Usage
- Register for a new account or log in with your credentials.
- Use the search feature to find available trains.
- Select a train and book your tickets.
- Manage your bookings through your account dashboard.
  
## Contributing
- Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

  - Fork the repository.
    - Create a new branch:
     ```bash
     git checkout -b feature/YourFeature
  - Make your changes and commit them:
    ```bash
     git commit -m "Add some feature"
  - Push to the branch:
     ```bash
     git push origin feature/YourFeature
  - Open a pull request.

## Acknowledgements
- PHP - The programming language used for backend development.
- Bootstrap - Frontend framework for responsive design.
- phpMyAdmin - Tool for managing MySQL databases.
