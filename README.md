
# TasteHub - Multi-Vendor Food Order Platform

Welcome to TasteHub, TasteHub is a full-stack multi-vendor food ordering platform built on the MERN stack. It implements Role-Based Access Control (RBAC) to provide tailored features and access for different types of users: User, Vendor, and Admin. The platform includes secure authentication using bcrypt for password hashing and JWT for user account activation.

## Features
User Roles and Permissions
## User:
- View and track orders.
- Update profile information.
- Access personal order history on the dashboard.
## Vendor (Seller):
Create and manage products.
Create promotional events.
Manage user orders for their products.
## Admin:
Manage both users and vendors.
Oversee and maintain the platform.
## Authentication and Security
Password Hashing: User passwords are securely hashed using bcrypt.
## JWT Tokens:
Used for account activation links.
Ensure secure API communication and session management.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Admin Dashboard](#admin-dashboard)
  
## Features

### For Users
- **Browse and Order**: Discover a wide range of cuisines from various vendors.
- **Real-Time Tracking**: Track your orders in real-time from preparation to delivery.
- **Secure Payments**: Multiple secure payment options for a smooth checkout experience.
- **Personalized Recommendations**: Get food suggestions based on your preferences and order history.

### For Vendors
- **Shop Management**: Add and manage your shop, including menu items, prices, and availability.
- **Order Management**: Receive and manage orders efficiently with real-time notifications.
- **Marketing Tools**: Promote your shop with featured listings and promotions.
- **Customer Insights**: Access valuable data about customer preferences and behavior.

### For Admins
- **User Management**: View, edit, and delete user accounts.
- **Vendor Management**: Approve, edit, and remove vendor accounts and manage their shops.
- **Order Monitoring**: Monitor orders across the platform to ensure smooth operations.
- **Analytics and Reports**: Access detailed analytics and generate reports on platform usage, sales, and more.

## Installation

### Prerequisites
- Node.js
- MongoDB

## Usage

- **Users**: Register, browse shops, order food, and enjoy!
- **Vendors**: Register, set up your shop, add menu items, and start receiving orders.
- **Admins**: Log in to the admin dashboard to manage users, vendors, and monitor platform activities.

## Technologies

- **MongoDB**: Database for storing application data.
- **Express.js**: Backend framework for building RESTful APIs.
- **React**: Frontend library for building the user interface.
- **Node.js**: JavaScript runtime for server-side programming.

## Admin Dashboard

The admin dashboard provides powerful tools for managing the platform:

- **User Management**: View and manage all user accounts, including the ability to edit user details or remove accounts if necessary.
- **Vendor Management**: Oversee vendor registrations, approve new vendors, manage existing vendor details, and ensure compliance with platform policies.
- **Order Monitoring**: Keep track of all orders placed on the platform to ensure timely processing and delivery.
- **Analytics and Reports**: Access comprehensive analytics and generate reports to understand platform performance, user engagement, and sales trends.
