
# SCATCH-MAIN

## Project Description

SCATCH-MAIN is an e-commerce website where users can browse different variants of bags. The platform requires users to create an account before they can check their bag. Users can log in or out of their accounts. For owners of the platform, there's an additional feature to add more bags by creating an owner account.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

SCATCH-MAIN is built using the Model-View-Controller (MVC) architectural pattern. It's a Node.js-based application utilizing Express.js for the backend, MongoDB as the database, and various packages for authentication and file upload functionality.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens), bcrypt, cookie-parser
- **File Upload**: Multer
- **Frontend Framework**: [Insert frontend framework if used]

## Features

1. User Account Creation and Management
2. Login and Logout Functionality
3. Bag Variant Browsing
4. Owner Account for Adding New Bags
5. Secure File Upload System
6. Authentication and Authorization



1. **GET /api/users**: Retrieve all users
2. **POST /api/register**: Create a new user account
3. **POST /api/login**: Authenticate user login
4. **GET /api/logout**: Log out current user
5. **GET /api/bags**: Retrieve all bag variants
6. **POST /api/bags**: Add a new bag variant (owner-only)
7. **GET /api/cart/:userId**: Get user's cart items
8. **POST /api/cart/add**: Add item to cart
9. **DELETE /api/cart/remove**: Remove item from cart
10. **POST /api/upload**: Upload files using Multer
11. **GET /api/auth/verify**: Verify JWT token
12. **POST /api/auth/refresh**: Refresh JWT token
