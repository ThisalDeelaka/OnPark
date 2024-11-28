# Onpark - Smart Parking Management System

**Onpark** is a revolutionary web-based **Smart Parking Management System** designed to optimize parking in urban areas. With its user-friendly interface and powerful features, Onpark transforms the parking experience by offering seamless parking reservations, efficient space allocation, and integrated valet and service center management. By addressing the complexities of parking in bustling cities, Onpark provides a comprehensive solution that enhances the overall parking experience for both users and parking administrators.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Features](#key-features)
  - [Reservation System](#reservation-system)
  - [Place Management](#place-management)
  - [Staff Oversight](#staff-oversight)
  - [Valet Service Integration](#valet-service-integration)
  - [Service Center Management](#service-center-management)
  - [Inventory Management](#inventory-management)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Project Overview

Onpark is designed to simplify and streamline the parking management process for both users and administrators. It offers a range of advanced features that address the need for efficient space utilization, user convenience, and staff management. The system empowers users to reserve parking spaces in advance, while administrators can manage parking inventory, monitor staff performance, and integrate additional services like valet parking.

Onpark is built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) and is designed to be scalable, efficient, and easy to use.

## Key Features

### Reservation System
- **What it Does**: Users can easily reserve parking spaces in advance, guaranteeing a spot upon arrival. This feature eliminates the frustration of searching for available parking spaces in crowded urban areas.
- **Key Features**:
  - **Advanced Reservations**: Users can book parking spots before their arrival, ensuring convenience and saving time.
  - **Real-Time Availability**: The system provides up-to-date information about available parking spaces, showing users which spots are open.

### Place Management
- **What it Does**: The system efficiently organizes and allocates parking spots, optimizing space utilization across parking areas.
- **Key Features**:
  - **Dynamic Allocation**: Parking spaces are automatically allocated based on demand, ensuring maximum space utilization.
  - **Admin Control**: Parking administrators can manually adjust space allocations and oversee usage patterns for improved operational efficiency.

### Staff Oversight
- **What it Does**: Onpark provides a dashboard for monitoring parking attendants and staff performance to maintain high service quality.
- **Key Features**:
  - **Staff Monitoring**: Track staff assignments, performance, and parking operations in real time.

### Valet Service Integration
- **What it Does**: Onpark integrates valet services for a smoother and more efficient parking process, allowing users to hand over their vehicles to a valet attendant upon arrival.
- **Key Features**:
  - **Valet Booking**: Users can opt for valet service during their reservation process, ensuring seamless parking without having to find a space themselves.
  - **Valet Management**: Track and manage valet services in real-time for improved coordination and efficiency.

### Service Center Management
- **What it Does**: Onpark streamlines the maintenance and customer support operations through an integrated service center management system.
- **Key Features**:
  - **Maintenance Tracking**: Manage parking space maintenance and repairs, ensuring optimal conditions for users.

### Inventory Management
- **What it Does**: Onpark includes an inventory management system for both parking resources and service center items (e.g., oils, tools, and other maintenance items).
- **Key Features**:
  - **Car Park Inventory**: Admins can track parking lot items, including barriers, lighting, signage, and other essential equipment.
  - **Service Center Inventory**: Manage and track items like oils, tires, tools, and other maintenance supplies for vehicles.
  - **Real-Time Stock Updates**: Keep inventory levels updated in real time to ensure adequate supplies for both parking and maintenance operations.
  - **Color Indicators**: Inventory items are visually indicated with color codes for stock levels:
    - **Low Stock**: Red indicator
    - **Medium Stock**: Yellow indicator
    - **High Stock**: Green indicator

## Technologies Used

- **Frontend**: React.js for building the user interface, ensuring a dynamic and responsive design.
- **Backend**: Node.js with Express.js for the server-side logic, handling requests and database operations.
- **Database**: MongoDB for storing data related to parking spots, reservations, users, staff, and services.
- **State Management**: Redux for managing application state across components, ensuring smooth user interactions.
- **Authentication**: JSON Web Tokens (JWT) for secure authentication and user management.
- **Real-Time Features**: WebSockets for real-time updates such as reservation confirmations, valet status, and space availability.


## Installation

To run the project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/onpark.git
cd onpark
```

### 2. Install Dependencies

#### Frontend (React)

```bash
cd frontend
npm install
```

#### Backend (Node.js with Express)

```bash
cd backend
npm install
```

### 3. Set up Environment Variables

Create a `.env` file in both the frontend and backend directories, and configure the necessary environment variables. Example:
- `MONGO_URI` for the database connection.
- `SECRET_KEY` for JWT authentication.
- `API_URL` for backend API endpoints.

### 4. Run the Project

#### Frontend:

```bash
cd frontend
npm start
```

The frontend will be accessible at [http://localhost:3000](http://localhost:3000).

#### Backend:

```bash
cd backend
npm start
```


## Usage

### For Users:
- **Reserve a Parking Spot**: Reserve a parking space in advance to guarantee availability.
- **Track Your Reservations**: View upcoming and past reservations in your user dashboard.
- **Opt for Valet Services**: Easily choose valet service for a smooth parking experience.
  
### For Parking Administrators:
- **Manage Parking Spaces**: Allocate and optimize parking spots for maximum efficiency.
- **Monitor Staff Performance**: Oversee parking attendants and ensure consistent service quality.
- **Track Reservations**: View and manage all user reservations, including details on valet services.
