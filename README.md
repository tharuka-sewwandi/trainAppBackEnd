# Train Booking System - Backend

This is the backend repository for the Train Booking System, a web application built with Node.js. It provides functionality to manage train details, book trains, and perform CRUD operations from the admin side.

## Features

- User (passenger) side:
  - View train details
  - Book a train
  - Receive booking confirmation via SMS (Twilio) and email (Nodemailer)

- Admin side:
  - Perform CRUD operations on train details
  - Manage passenger bookings

## Technologies Used

- Node.js: A JavaScript runtime environment
- Express.js: A web application framework for Node.js
- MongoDB: A NoSQL database for storing train and passenger information
- Twilio: A cloud communications platform for sending SMS
- Nodemailer: A module for sending emails
- Other dependencies: (list any additional libraries or packages used)

## Setup and Installation

1. Clone the repository: `git clone https://github.com/tharuka-sewwandi/trainAppBackEnd.git`
2. Install dependencies: `npm install`
3. Configure environment variables:
   - Rename the `.env.example` file to `.env`.
   - Update the necessary configuration variables (e.g., database connection, Twilio credentials, email settings, etc.).
4. Run the application: `npm start`

## API Endpoints

- `/api/trains`: (GET, POST) Get all trains or add a new train.
- `/api/trains/:id`: (GET, PUT, DELETE) Get, update, or delete a specific train.
- `/api/bookings`: (GET, POST) Get all bookings or create a new booking.
- `/api/bookings/:id`: (GET, PUT, DELETE) Get, update, or delete a specific booking.
- (Add any additional API endpoints as relevant)

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:
1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Commit your changes and push the branch to your forked repository
4. Open a pull request explaining the changes you have made
