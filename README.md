# AUCTION-X-LOCALHOST

_Transforming Auctions Into Limitless Opportunities_

![License](https://img.shields.io/badge/license-MIT-blue)
![Language](https://img.shields.io/badge/language-JavaScript-blue)

## Built with the rocks and technologies:

## Frontend Technologies:

![React](https://img.shields.io/badge/Frontend-React-blue)
![Redux Toolkit](https://img.shields.io/badge/State-Redux%20Toolkit-purple)
![React Router](https://img.shields.io/badge/Routing-React%20Router-orange)
![Axios](https://img.shields.io/badge/API-Axios-lightgrey)
![Socket.io Client](https://img.shields.io/badge/Realtime-Socket.io-black)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap-563d7c)
![Ant Design](https://img.shields.io/badge/UI-Ant%20Design-1890ff)
![MDB React UI Kit](https://img.shields.io/badge/UI-MDB%20React%20Kit-teal)
![Styled Components](https://img.shields.io/badge/Styling-Styled%20Components-pink)
![Chart.js](https://img.shields.io/badge/Charts-Chart.js-red)
![SweetAlert2](https://img.shields.io/badge/Alerts-SweetAlert2-ff69b4)
![React Hot Toast](https://img.shields.io/badge/Notifications-React%20Hot%20Toast-orange)
![React Icons](https://img.shields.io/badge/Icons-React%20Icons-blue)
![Font Awesome](https://img.shields.io/badge/Icons-Font%20Awesome-339AF0)
![React Phone Number Input](https://img.shields.io/badge/Form-Phone%20Input-lightblue)
![jsPDF](https://img.shields.io/badge/Export-jsPDF-lightgreen)
![JWT Decode](https://img.shields.io/badge/Auth-JWT%20Decode-yellow)
![Redux Persist](https://img.shields.io/badge/Persistence-Redux%20Persist-brightgreen)

## Backend Technologies:

![MongoDB](https://img.shields.io/badge/DB-MongoDB-green)
![Node](https://img.shields.io/badge/Runtime-Node.js-lightgrey)
![Express](https://img.shields.io/badge/Framework-Express-yellow)
![Socket.io](https://img.shields.io/badge/Socket-io-black)
![Mongoose](https://img.shields.io/badge/ODM-Mongoose-blue)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)
![Passport](https://img.shields.io/badge/Auth-Passport.js-brightgreen)
![Cloudinary](https://img.shields.io/badge/Image%20Storage-Cloudinary-lightblue)
![Dotenv](https://img.shields.io/badge/Config-Dotenv-purple)
![CORS](https://img.shields.io/badge/Security-CORS-red)
![Bcrypt](https://img.shields.io/badge/Encryption-Bcrypt-darkblue)
![Nodemailer](https://img.shields.io/badge/Email-Nodemailer-ff69b4)


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

### 1. Clone the repository:

```
git clone https://github.com/OM-SARDAR/AUCTION-X-LOCALHOST
```

### 2. Go to project folder
```
cd AUCTION-X-LOCALHOST
```
### 3. FOR THE FRONTEND PART :------------------------------------------------------------------------

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

### 4. FOR THE BACKEND PART :------------------------------------------------------------------------

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
---

## Usage
To run the project locally, follow these steps:

For Backend (Server)
  ```
  cd server
  npm install
  npm start
  ```
This starts the backend server using Express and Socket.io on the configured port (default: http://localhost:5000).

For Frontend (Client)
 ```
 cd client
 npm install
 npm start
 ```
This runs the React frontend on http://localhost:3000.

Access the App

Once both servers are running, open your browser and go to:
```
 http://localhost:3000
```
You can now:

• Register or log in with Google or email  
• Create, join, and participate in live auctions  
• Place bids in real time (powered by Socket.io)  
• View and update products dynamically through the API  

---

## Testing

Steps:

Start both backend and frontend servers
```
cd server
npm start
```
```
cd client
npm start
```

✓ Backend runs on http://localhost:5000
✓ Frontend runs on http://localhost:3000

Open your browser → go to http://localhost:3000

Create a test account or log in using Google.

Try out the main features:

• Add a product for auction  
• Join a product’s live auction  
• Place bids  
• See if the bids update instantly (real-time using Socket.io)  
• Check if notifications appear when someone outbids you  
• Check MongoDB (optional)  
• Open your MongoDB database  
• Make sure the new product, bids, and users are being saved correctly  

That’s all for manual testing — it’s about making sure everything feels and works right.
