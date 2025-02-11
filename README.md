# BookMyGas - A Gas Booking Website

## Project Description

BookMyGas is an online gas booking system designed to streamline the process of booking residential and commercial gas. The system provides a centralized platform for managing gas bookings, enabling customers to apply for new connections, update their profiles, view delivery details, and make secure online payments.

## Features

### Customer Management
- **Customer Registration**: Users can register using their email, password, and other relevant information.
- **Customer Login**: Registered customers can log in with their credentials.
- **Profile Update**: Users can update their information, such as address and phone number.
- **Apply for Connection**: Customers can apply for a new gas connection by providing necessary documents.
- **Book Gas**: Customers with an existing gas connection can book residential or commercial gas.
- **Cancel/Update Order**: Users can cancel orders or reschedule delivery dates and addresses.
- **View Order History**: Customers can view details of previous and recent orders.
- **Change Agency**: Customers have the option to change their gas agency.

### Admin Management
- **User Details**: Admins can view customer details, including addresses and phone numbers.
- **Staff Management**: Admins can manage staff information and roles.
- **Track Orders**: Admins have the ability to track all orders.
- **Stock Availability**: Admins can check the availability of gas stock.
- **Order from LPG Vendor**: Admins receive and manage gas orders from different vendors.

### Payment Management
- **Payment Gateway Integration**: Secure payment options for users to make online payments for gas bookings.
- **Payment Confirmation**: Users receive confirmation upon successful payment and gas booking.

## Technologies Used
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose for schema management
- **Frontend**: React
- **Payment Gateway**: WIP

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/tanaytelsinge/BookMyGas.git

2. Database setup:
   - Execute DB script as required.
   - For mySQL -> [here](https://github.com/tanayTelsinge/BookMyGas/blob/main/backend/main/config/mysql_queries.sql) , If you are using mySQL, you need to add alternative DB connection logic. (existing one [here](https://github.com/tanayTelsinge/BookMyGas/blob/main/backend/main/config/db.js) is specific to mongoDB).
   - For mongoDB -> [here](https://github.com/tanayTelsinge/BookMyGas/blob/main/backend/main/config/mongodb.js)
   ```bash
   git clone https://github.com/tanaytelsinge/BookMyGas.git

3. Steps to run:
   - Install packages
     ```bash
     npm init

   - For backend, add required variables in .env file (JWT_SECRET, PORT, MONGODB_URL to connect).
   - Run backend server
     ```bash
     npx nodemon server.js

   - Frontend
   ```bash
   npm start
