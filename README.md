---
### Bus Ticket Booking System

Welcome to the Bus Ticket Booking System project! This repository serves as the central hub for our project, which is split into backend and frontend components managed via GitHub submodules.

### Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Setup Instructions](#setup-instructions)
4. [Usage](#usage)
5. [Repositories](#repositories)

### Introduction

This project is designed to provide a comprehensive solution for bus ticket booking, including features for managing stations, routes, buses, and user bookings. The system is built using modern web development technologies and follows best practices for microservices architecture.

### Project Structure

The project is organized into two main submodules:
- **Backend**: Contains all server-side code, APIs, and business logic.
- **Frontend**: Contains the client-side application, providing a user interface for interacting with the system.

### Setup Instructions

To get started with this project, follow the steps below:

1. **Clone the Main Repository**:
    ```sh
    git clone --recurse-submodules https://github.com/Aravind-SL/Bus_ticket_booking.git
)
    cd <repository-directory>
    ```

2. **Initialize and Update Submodules**:
    If you cloned the repository without the `--recurse-submodules` flag, you need to initialize and update the submodules manually:
    ```sh
    git submodule init
    git submodule update
    ```

3. **Navigate to Backend and Frontend Repositories**:
    Each submodule has its own README with specific setup instructions.
    - For backend setup, navigate to the backend directory:
      ```sh
      cd backend
      ```
    - For frontend setup, navigate to the frontend directory:
      ```sh
      cd frontend
      ```

4. **Follow the Setup Instructions in Each Submodule**:
    Each submodule repository has detailed setup instructions. Ensure you follow them to install dependencies and configure the development environment.

### Usage

Once the setup is complete, you can start both the backend and frontend services. Typically, you will need to run the backend server first, followed by the frontend application.

- **Running the Backend**:
    Follow the instructions in the backend repository to start the backend server.

- **Running the Frontend**:
    Follow the instructions in the frontend repository to start the frontend application.

### Repositories

- **Backend Repository**: [Backend Repository Link](https://github.com/Aravind-SL/Bus_ticket_booking_backend)
- **Frontend Repository**: [Frontend Repository Link](https://github.com/Aravind-SL/Bus_ticket_booking_frontend)

Each repository contains detailed documentation about the specific services, APIs, and components it handles. Please refer to the respective READMEs for more information.

---

Thank you for using the Bus Ticket Booking System! If you encounter any issues or have any questions, please feel free to open an issue or contribute to the project.
