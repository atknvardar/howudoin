Howudoin Project

Overview

Howudoin is a mobile messaging application inspired by WhatsApp, designed to offer seamless communication through individual and group chats. The project is divided into two main phases: backend and frontend development.

Backend: Developed using Spring Boot, the backend handles user authentication, friend management, group creation, and real-time messaging functionalities. MongoDB is used for data storage.

Frontend: Built with React Native, the frontend provides a user-friendly interface for registration, friend management, and messaging, supporting both iOS and Android platforms.

Table of Contents

Features

Technologies Used

Installation

API Endpoints

Screens and UI

Contributing

License

Features

Backend

User Registration and Login: Secure registration and login with JWT-based authentication.

Friend Request System: Send, accept, and manage friend requests.

Messaging System: Real-time messaging between friends.

Group Management: Create groups, add members, and send group messages.

MongoDB Integration: Store users, groups, and messages using flexible document-based storage.

Frontend

User-Friendly Interface: Clean and simple design for smooth navigation.

Real-Time Messaging: Chat interfaces update in real-time for both individual and group messages.

Cross-Platform Support: Compatible with both Android and iOS devices.

Technologies Used

Backend

Spring Boot

MongoDB

JWT (JSON Web Tokens)

Frontend

React Native

JWT Authentication

Installation

Prerequisites

Java 11 or later

Node.js and npm

MongoDB

Backend Setup

Clone the repository:

git clone https://github.com/yourusername/howudoin-backend.git
cd howudoin-backend

Configure application.properties with your MongoDB connection details.

Run the Spring Boot application:

./mvnw spring-boot:run

Frontend Setup

Clone the repository:

git clone https://github.com/yourusername/howudoin-frontend.git
cd howudoin-frontend

Install dependencies:

npm install

Run the React Native app:

npx react-native run-android  # For Android
npx react-native run-ios      # For iOS

API Endpoints

Public Endpoints

POST /register: Register a new user (name, last name, email, password).

POST /login: Authenticate and login a user (email, password).

Secure Endpoints (Require JWT Token)

POST /friends/add: Send a friend request.

POST /friends/accept: Accept a friend request.

GET /friends: Retrieve friend list.

POST /messages/send: Send a message to a friend.

GET /messages: Retrieve conversation history.

POST /groups/create: Create a new group.

POST /groups/:groupId/add-member: Add a member to a group.

POST /groups/:groupId/send: Send a message to a group.

GET /groups/:groupId/messages: Retrieve group message history.

GET /groups/:groupId/members: Retrieve group members.

Screens and UI

User Registration and Login Screen

Register and login using email and password.

Friend Request and Friend List Screen

Search for users, send friend requests, and view friend list.

Messaging Screens

Chat with friends and groups in real-time.

View conversation history.

Group Management Screens

Create groups, add members, and view group details.

Group messaging with real-time updates.

Contributing

Contributions are welcome! Please fork the repository and create a pull request.

Fork the repository.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a pull request.

License

This project is licensed under the MIT License.

