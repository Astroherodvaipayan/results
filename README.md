# Student Management System

A robust web-based application designed to streamline educational institution operations, optimize student management, and facilitate effective communication among stakeholders.

## Overview
The Student Management System is a comprehensive solution that provides a centralized platform for efficiently managing students, faculty, classes, and subjects. Leveraging the power of the MERN stack (MongoDB, Express.js, React.js, Node.js), this application offers a multitude of features designed to enhance administrative efficiency and academic excellence.

## Features
- **User Roles**: Three distinct user roles—Admin, Teacher, and Student—with specialized functionalities and access permissions.
- **Admin Dashboard**: Comprehensive dashboard for managing students, teachers, classes, and subjects.
- **Attendance Tracking**: Enables teachers to mark attendance and view attendance history.
- **Data Visualization**: Interactive charts and graphs offer students insights into their academic performance, fostering self-awareness and continuous improvement.
- **Notice and Complaints**: Dedicated section for posting notices and complaints, facilitating effective communication between students, teachers, and administrators.

## Technologies Used
### Server
- **Node.js**: Powerful JavaScript runtime environment.
- **Express.js**: Lightweight and flexible web application framework.
- **MongoDB**: NoSQL database for efficient data storage and retrieval.

### UI
- **React.js**: JavaScript library for building user interfaces.
- **Material UI**: Popular front-end framework for building responsive and intuitive interfaces.
- **Redux**: State management library for predictable and efficient state management.

## Installation

### Prerequisites
- Node.js (including npm)
- MongoDB

### Installation Steps

#### Clone the repository:
```bash
https://github.com/Astroherodvaipayan/results.git
```
2. **Navigate to the Project Directory:**
    ```bash
    cd results
    ```

#### Backend Setup

1. **Navigate to the Backend Directory:**
    ```bash
    cd SERVER
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**
    Create a `.env` file in the backend directory and add your MongoDB connection string:
    ```plaintext
    MONGO_URL=your_mongodb_connection_string
    ```

4. **Start the Backend Server:**
    ```bash
    npm start
    ```

#### Frontend Setup

1. **Navigate to the Frontend Directory:**
    ```bash
    cd UI
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Set Up Environment Variables:**
    Create a `.env` file in the frontend directory and specify the base URL for the backend server:
    ```plaintext
    REACT_APP_BASE_URL=http://localhost:5000
    ```

4. **Start the Frontend Application:**
    ```bash
    npm start
    ```
