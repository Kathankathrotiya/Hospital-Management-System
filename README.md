# Hospital Management System (HMS)

## Overview

This web application is a Hospital Management System (HMS) built using the Flask framework in Python. It provides functionalities for managing doctors, patients, appointments, and user authentication.

## Features

- **User Authentication**: Allow users to register, log in, and log out securely.
- **Doctor Management**: Add, view, and manage doctors, including their specialties and departments.
- **Patient Booking**: Patients can book appointments with doctors, providing details such as time, date, and department.
- **Appointment Management**: View, edit, and delete patient appointments.
- **Database Integration**: Utilizes SQLAlchemy for seamless interaction with the database.
- **Email Confirmation**: Confirmation emails are sent to patients upon booking appointments (email functionality is commented out and needs to be configured).

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/hospital-management-system.git
    cd hospital-management-system
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Configure the database:
   - Open `config.json` and update the database connection details.

4. Run the application:

    ```bash
    python app.py
    ```

5. Access the application in your web browser at [http://localhost:5000](http://localhost:5000).

## Configuration

- Edit the `config.json` file to configure parameters such as the database URI, email server details, etc.

## Usage

- Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the HMS application.
