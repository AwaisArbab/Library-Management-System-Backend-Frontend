# Library Management System

A full-stack Library Management System built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application helps manage books, users, and library operations through a modern web interface.

## Features

* User Authentication and Authorization
* Admin Dashboard
* Book Management (Add, Update, Delete, View)
* Member Management
* Book Issue and Return Tracking
* Search and Filter Books
* Responsive User Interface
* RESTful API Integration

## Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3

### Backend

* Node.js
* Express.js

### Database

* MongoDB

## Project Structure

```text
Library-Management-System/
│
├── frontend/
│   ├── src/
│   └── public/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/AwaisArbab/Library-Management-System-Backend-Frontend.git
cd Library-Management-System-Backend-Frontend
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

## Environment Variables

Create a `.env` file inside the backend directory and configure the required environment variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Run the Application

### Start Backend

```bash
cd backend
npm start
```

### Start Frontend

```bash
cd frontend
npm start
```

## Future Enhancements

* Email Notifications
* Fine Management System
* Book Reservation Feature
* Analytics Dashboard
* Cloud Deployment

## Author

Awais Arbab

## License

This project is intended for educational and learning purposes.
