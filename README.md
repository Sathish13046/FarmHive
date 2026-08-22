# VAYAL Backend

## Overview

VAYAL is an agricultural marketplace platform that helps farmers and buyers connect directly.

The backend provides APIs for authentication, user management, product listings, database operations, and other core functionalities of the application.

---

## Features

- User Registration
- User Login
- JWT Authentication
- User Management
- Farmer Management
- Buyer Management
- Product Management
- Listing Management
- My Listings
- PostgreSQL Database
- Prisma ORM
- REST API

---

## Technology Stack

| Technology | Purpose |
|---|---|
| **Node.js** | Backend runtime |
| **Express.js** | API development |
| **TypeScript** | Programming language |
| **Prisma** | Database ORM |
| **PostgreSQL** | Database |
| **JWT** | Authentication |
| **npm** | Package management |

---

## Project Structure

```text
vayal-backend/
│
├── src/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── services/
│   └── server.ts
│
├── prisma/
│   └── schema.prisma
│
├── .env
├── package.json
├── package-lock.json
└── README.md
```
## Prerequisites

Before setting up and running the VAYAL backend, make sure the following software and tools are installed on your system.

### Required Software

- **Node.js** – Version 18 or above
- **npm** – Comes with Node.js
- **PostgreSQL** – Version 14 or above
- **pgAdmin 4** – For managing the PostgreSQL database
- **Git** – For version control
- **Visual Studio Code** – Recommended code editor

### Required Knowledge

Basic knowledge of the following technologies is recommended:

- JavaScript / TypeScript
- Node.js
- Express.js
- REST APIs
- PostgreSQL
- SQL
- Prisma ORM
- JWT Authentication
- Git and GitHub

### System Requirements

The application can be developed and tested on:

- **Windows 10 / 11**
- **Linux**
- **macOS**

### Database Requirements

Before starting the backend, make sure:

1. PostgreSQL is installed.
2. PostgreSQL service is running.
3. PostgreSQL is running on port `5432`.
4. A database named `vayal` is created.
5. PostgreSQL username and password are configured correctly.
6. The `DATABASE_URL` in the `.env` file matches the PostgreSQL configuration.

### Environment Requirements

Create a `.env` file in the backend root directory:

```env
PORT=5000
NODE_ENV=development

DATABASE_URL="postgresql://postgres:postgres@localhost:5432/vayal?schema=public"

JWT_SECRET="vayal_super_secret_change_me"
JWT_EXPIRES_IN="7d"
```
# VAYAL Backend

## Database Configuration

VAYAL uses **PostgreSQL** as the primary database.

### Database Details

| Configuration | Value |
|---|---|
| **Host** | `localhost` |
| **Port** | `5432` |
| **Database** | `vayal` |
| **Username** | `postgres` |
| **Password** | `postgres` |

Make sure PostgreSQL is installed and running before starting the backend.

---

## Create Database

Create a PostgreSQL database named:

```text
vayal
```
## Project Information

### Project Name

**VAYAL**

### Project Type

**Farmers' Direct Produce Marketplace**

### Domain

**Agriculture / Supply Chain**

### Purpose

VAYAL is designed to help farmers sell agricultural products directly to buyers while providing a simple, efficient, and transparent digital marketplace.

---

## Future Enhancements

Future versions of the VAYAL backend may include:

- Online Payments
- Order Management
- Real-Time Notifications
- Advanced Search
- Product Recommendations
- Location-Based Services
- Image Upload
- Order Tracking
- Admin Dashboard
- Analytics
- Rating and Review System

---

## License

This project is developed as part of the **VAYAL Agricultural Marketplace Application**.

Copyright © 2026 VAYAL Development Team.

All rights reserved.

---

## Development Team

**VAYAL Development Team**

---

## Conclusion

VAYAL provides a reliable backend foundation for a direct farmer-to-buyer marketplace.

The backend combines **Node.js, Express.js, TypeScript, Prisma, PostgreSQL, and JWT Authentication** to provide a scalable, secure, and efficient application architecture.

The system enables secure user authentication, product listing management, database operations, and communication between the frontend and backend.
