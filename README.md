# React Webshop Application

This project is a fullstack webshop application with a React-based frontend and a Node.js backend built with Express and MongoDB.

The application allows users to browse products, manage a shopping cart, place orders, and manage their accounts through an authenticated workflow.

---

## Overview

The webshop provides a complete purchase flow, from product discovery to order submission. Certain functionality, such as placing orders and viewing order history, is restricted to authenticated users.

---

## Features

- User registration and authentication
- Browse products and view detailed product information
- Product search functionality
- Shopping cart with add and remove capabilities
- Order submission for authenticated users only
- View order history
- Change account password
- Secure logout

---

## Tech Stack

### Frontend
- React
- React Router
- Context API

### Backend
- Node.js
- Express
- MongoDB (MongoDB Atlas)

---

## Security Considerations

- Authentication and API protection using JSON Web Tokens (JWT)
- Protected routes secured with authentication middleware
- Passwords are hashed using bcrypt before being stored
- JWTs are sent via authorization headers rather than cookies, reducing CSRF exposure
- React’s built-in escaping in JSX helps mitigate XSS risks

---

## Architecture

The application follows a client–server architecture where the React frontend communicates with a RESTful API. The backend handles authentication, product management, user accounts, and order processing, with MongoDB used for persistent data storage.

---

## How to Run Locally

1. Clone the repository
2. Install dependencies for both frontend and backend
3. Configure environment variables for the backend (MongoDB connection, JWT secret)
4. Start the backend server
5. Start the frontend development server

---

## Project Context

This project was developed as part of a fullstack web development course, with a focus on building a complete e-commerce flow using React, Node.js, and MongoDB.
