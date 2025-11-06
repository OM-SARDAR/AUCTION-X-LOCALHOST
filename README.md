# AUCTION-X-LOCALHOST

_Transforming Auctions Into Limitless Opportunities_

![License](https://img.shields.io/badge/license-MIT-blue)
![Language](https://img.shields.io/badge/language-JavaScript-blue)

Built with the rocks and technologies:

![MongoDB](https://img.shields.io/badge/DB-MongoDB-green)
![Node](https://img.shields.io/badge/Runtime-Node.js-lightgrey)
![Express](https://img.shields.io/badge/Framework-Express-yellow)
![Socket.io](https://img.shields.io/badge/Socket-io-black)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)
![Multer](https://img.shields.io/badge/Uploads-Multer-yellow)
![Cloudinary](https://img.shields.io/badge/Media-Cloudinary-blue)
![React](https://img.shields.io/badge/UI-React-blue)
![Redux](https://img.shields.io/badge/State-Redux-purple)
![Tailwind](https://img.shields.io/badge/CSS-TailwindCSS-blue)
![Chart.js](https://img.shields.io/badge/Charting-Chart.js-pink)

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

**AUCTION-X-LOCALHOST** is a full-stack developer toolkit for building dynamic online auction platforms with real-time bidding, user management, and comprehensive admin controls.  
It combines a robust backend with interactive frontend components to deliver seamless, engaging marketplace experiences. Whether you're managing products, orders, or user profiles, this project provides the essential features to develop scalable and secure auction applications.

### Why AUCTION-X-LOCALHOST?

This project streamlines the development of online auction systems with:

- ✅ **Real-Time Bidding:** Enable live auctions with WebSocket-powered updates.
- ✅ **User Authentication:** Secure login, profile management, and role-based access control.
- ✅ **Admin Dashboard:** Visualize revenue, orders, and customer data for efficient management.
- ✅ **Media Management:** Integrate Cloudinary for smooth image and video handling.
- ✅ **Secure Notifications:** OTP and email utilities for user verification and communication.
- ✅ **Modular Architecture:** Clear separation of backend, frontend, utilities, and middleware for scalability.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- 📦 **Programming Language:** JavaScript  
- 📦 **Package Manager:** NPM

---

## Installation

Build AUCTION-X-LOCALHOST from the source and install dependencies:

1. Clone the repository:

```
git clone https://github.com/OM-SARDAR/AUCTION-X-LOCALHOST
```

2. Go to project folder
```
cd AUCTION-X-LOCALHOST
```
3. FOR THE FRONTEND PART :----------------------------

A. Go to "client" folder for accessing frontend
```
cd client
```
B. Create a .env file inside "client" folder
```
# Step 1: Create a new .env file
# (This creates the file if it doesn’t exist)
touch .env

# Step 2: Open the .env file in your code editor (VS Code example)
code .env

# Step 3: Add your environment variable inside the file
# Example:
# REACT_APP_RAZORPAY_API_KEY=YOUR_RAZORPAY_API_KEY_HERE
```

C. Install dependencies along with node mofules
```
npm install
```

D. Start the server side
```
npm start
```

4. FOR THE BACKEND PART :----------------------------
A. Go to "server" folder for accessing backend
```
cd server
```
B. Create a .env file inside "server" folder
```
# Step 1: Create a new .env file
# (This creates the file if it doesn’t exist)
touch .env

# Step 2: Open the .env file in your code editor (VS Code example)
code .env

# Step 3: Add your environment variables inside the file
# Example:
# JWT_SECRETE=YOUR_JWT_SECRET_HERE
# PORT=5000
# MONGODB_URL=mongodb+srv://<YOUR_USERNAME:YOUR_PASSWORD@cluster0.tolhj.mongodb.net/YOUR_SCHEMA_NAME?retryWrites=true&w=majority&appName=Cluster0
# GOOGLE_CLIENT_ID=YOUR_GOOGLE_CLIENT_ID_HERE
# GOOGLE_CLIENT_SECRET=YOUR_GOOGLE_CLIENT_SECRET_HERE
# EMAIL_USER=YOUR_EMAIL_ADDRESS_HERE
# EMAIL_PASS=YOUR_EMAIL_PASSWORD_HERE
# CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_CLOUD_NAME_HERE
# CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY_HERE
# CLOUDINARY_API_SECRET=YOUR_CLOUDINARY_API_SECRET
```
C. Install dependencies along with node mofules
```
npm install
```

D. Start the client side
```
npm start
```
