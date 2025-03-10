# Wassalni Ride-Sharing App(this is only a description, the app source code is not allowed to be shared)

## Overview
Wassalni is a full-stack ride-sharing application designed to connect drivers and passengers seamlessly. Built with a robust backend and a user-friendly frontend, this app provides secure authentication, user profiles, trip management, and real-time communication. 

## Features
- **User Authentication**: Secure signup and login using JWT tokens.
- **User Profiles**: Update profile information, manage privacy and security settings.
- **Trip Management**: Create, search, and book trips. View trip history and manage trip status.
- **Real-Time Messaging**: Send and receive messages between users.
- **Custom Components**: Reusable UI components for consistent design and functionality.

## Tech Stack
### Frontend
- **React Native**: For building cross-platform mobile applications.
- **Expo**: Facilitates development and testing.
- **Async Storage**: For storing user tokens securely on the device.
- **Custom Components**: Created using `react-native` and `react-native-vector-icons`.

### Backend
- **Node.js & Express.js**: For building the server and handling API requests.
- **MongoDB**: Database for storing user, trip, and message data.
- **Mongoose**: ODM for MongoDB to manage database schemas.
- **JWT**: For secure authentication.

### Middleware
- **CORS**: To handle Cross-Origin Resource Sharing.
- **Helmet**: To enhance API security.
- **Rate Limiting**: To prevent abuse by limiting repeated requests.

## Project Structure
- **backend**: Contains server, routes, models, and middleware.
  - `db.js`: Connects to MongoDB.
  - `server.js`: Sets up the Express server and middleware.
  - `routes/`: Contains all the route handlers.
  - `models/`: Contains Mongoose schemas for User and Trip.
  - `middleware/`: Includes authentication middleware.

- **frontend**: Contains React Native screens, components, and utilities.
  - `App.js`: Main entry point of the React Native app.
  - `screens/`: Contains screens for Login, Signup, Profile, etc.
  - `components/`: Contains reusable UI components like CustomButton and CustomInput.
  - `utils/`: Contains utility functions for token management and storage.

## Getting Started
### Prerequisites
- Node.js and npm
- MongoDB

### Installation
1. **Backend**:
   ```bash
   cd backend
   npm install
   
2. **Frontend**:
   ```bash
   cd frontennd
   npm install

## Running the App
### Start the Backend:
1. **Backend**:
   ```bash
   cd backend
   node server.js
   
### Start the Frontend:

2. **Frontend**:
   ```bash
   cd frontennd
   npx expo
   
# DONT FORGET TO CHANGE THE IP
