# Login and Registration Backend

This project is a backend service for handling user authentication, including login, registration, and user data management. The service is built with **Node.js**, **Express**, and **MongoDB**. It is deployed on **Vercel** and offers secure user authentication and data management features.

## Features

- **User Registration:** Create new user accounts with secure password encryption.
- **User Login:** Authenticate users with email and password.
- **User Data Management:** CRUD operations for user profiles.
- **Middleware:** Custom middleware for error handling and request validation.
  
## Deployed Platform: Accessible at [Login & Registration Platform](https://test-login-bice.vercel.app/)

## Setup & Usage

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14+)
- **MongoDB**
- **Vercel CLI** (optional for deployment)

### Installation & Configuration

1. Clone the repository and navigate to the server folder:
   ```bash
   git clone <repository-url>
   cd server
  Install dependencies:

2.Install dependencies:
  npm install

3.Set up your environment variables by creating a .env file in the root directory:
  PORT=5000
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret
  
4.Start the server:
  npm start
