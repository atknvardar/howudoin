# Howudoin Project

A mobile messaging application inspired by WhatsApp, offering seamless communication through both individual and group chats. The project is split into two primary parts: a Spring Boot backend and a React Native frontend.

---

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
   - [Backend](#backend-features)  
   - [Frontend](#frontend-features)  
3. [Technologies Used](#technologies-used)  
   - [Backend](#backend-technologies)  
   - [Frontend](#frontend-technologies)  
4. [Installation](#installation)  
   - [Backend Setup](#backend-setup)  
   - [Frontend Setup](#frontend-setup)  
5. [API Endpoints](#api-endpoints)  
   - [Public Endpoints](#public-endpoints)  
   - [Secure Endpoints](#secure-endpoints-require-jwt-token)  
6. [Screens and UI](#screens-and-ui)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## Overview

Howudoin is designed to provide a simple yet robust chat experience. Users can register, send friend requests, create chat groups, and exchange real-time messages. The backend is developed with Spring Boot and stores data in MongoDB, while the frontend is built with React Native to ensure a consistent experience across both Android and iOS devices.

---

## Features

### Backend Features

- **User Registration and Login**  
  Secure registration and login with JWT-based authentication.
- **Friend Request System**  
  Send, accept, and manage friend requests.
- **Messaging System**  
  Real-time messaging between friends.
- **Group Management**  
  Create groups, add members, and send group messages.
- **MongoDB Integration**  
  Store users, groups, and messages using flexible, document-based storage.

### Frontend Features

- **User-Friendly Interface**  
  Clean and simple design for smooth navigation.
- **Real-Time Messaging**  
  Chat interfaces that update in real time for both individual and group messages.
- **Cross-Platform Support**  
  Compatible with both Android and iOS devices.

---

## Technologies Used

### Backend Technologies

- Spring Boot
- MongoDB
- JWT (JSON Web Tokens)

### Frontend Technologies

- React Native
- JWT Authentication

---

## Installation

### Prerequisites

- Java 11 or later  
- Node.js and npm  
- MongoDB  

### Backend Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/howudoin-backend.git
   cd howudoin-backend
