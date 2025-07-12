# Codehub





---
## Live Link
[Visit Live App](https://code-hub-neon.vercel.app/)

## Demo Link
[Watch Demo](https://drive.google.com/file/d/1i9Qx4gtVTlDneg502FzalP0uIuluh032/view?usp=sharing)


## Built with the tools and technologies:

- Express
- JSON
- AWS
- npm
- Mongoose
- DotEnv
- JavaScript
- Nodemon
- MongoDB
- React
- Axios
- Docker
- Vite
- Talwind
  

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)

---

## Overview

CodeHub is an all-in-one platform that empowers developers to build scalable online judge systems with ease. It combines a robust backend API with a React-based frontend, enabling real-time code evaluation, user authentication, and problem management.

---

## Why CodeHub?

This project simplifies the creation of competitive programming platforms by providing essential features out-of-the-box:

-  **Problem & Contest Management**: Organize and manage coding challenges efficiently.
-  **Inbuilt Compiler**: Compiler built using nodejs_child process so no external API used.
-  **AI Review**: Uses AI to review your code.
-  **Real-Time Submission & Evaluation**: Seamlessly submit code and receive instant feedback.
-  **Secure Authentication**: Protect user data with JWT and MongoDB integration.
-  **Intuitive React Interface**: Navigate effortlessly through problem sets, leaderboards, and user dashboards.
-  **Activity & Leaderboard Tracking**: Foster engagement with real-time activity updates and rankings.
-  **Modular Architecture**: Easily extend and customize for your specific needs.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** JavaScript  
- **Package Manager:** Npm

---

##  Installation

Build **Online\_Codehub** from the source and install dependencies:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/piyu5h25/Project-Summer
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Project-Summer
   ```
3. **Navigate to the client directory**:

   ```bash
   cd client
   ```

4. **Install the dependencies**:

   ```bash
   npm install
   ```

5. **Navigate to the server directory**:

   ```bash
   cd server
   ```

6. **Install the dependencies**:

   ```bash
   npm install
   ```
7. **Navigate to the compiler directory**:

   ```bash
   cd compiler
   ```

8. **Install the dependencies and build docker image**:

   ```bash
   npm install
   docker build command 
   ```

9. **Usage**
   Run the client with:

   ```bash
   npm run dev
   ```

10. **Usage**
   Run the server with:

   ```bash
   nodemon index.js
   ```
11. ** env files for client**
   ```bash
   VITE_COMPILER_URL
   VITE_BACKEND_URL
   ```
12. ** env files for compiler**
   ```bash
   PORT  
   AI_API_KEY  
   MODEL_NAME  

   ```
13. ** env files for compiler**
   ```bash
   
    PORT 
    MONGO_URL  
    JWT_SECRET  
    CLIENT_URL  
    COMPILER_URL  
    ADMIN_EMAIL = 
    ADMIN_PASSWORD = 

   ```


>  *Made with* ❤️ *by [Piyush Trivedi](https://github.com/piyu5h25)*
