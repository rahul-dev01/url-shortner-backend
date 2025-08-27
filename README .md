# Shortify - URL Shortener

Shortify is a scalable URL shortener built using **Express.js** and **MongoDB**. The project provides an efficient way to shorten URLs while also offering features like custom encoding, geo-tracking, rate limiting, user authentication, and more.

[Shortify on GitHub](https://github.com/aman3255/Shortify)

## Features

- **Scalable URL Shortener**: Built using **Express.js** and **MongoDB** for handling large volumes of requests.
- **Custom Encoding**: 72-character entropy pool used to create unique short codes.
- **JWT Authentication**: Role-based access control (ORG_ADMIN/ORG_MEMBER) with JWT-based user authentication.
- **Geo-Tracking**: Integrated **geoip-lite** for collecting location-based analytics.
- **Rate Limiting**: Implemented a limit of 10 clicks per URL for free-tier users, preventing abuse.
- **7-Day Expiration Policy**: Free-tier links expire after 7 days.
- **Secure Password Hashing**: **bcrypt** is used for password hashing to ensure security.
- **HTTPS Redirect Middleware**: Redirects to the shortened URL using HTTPS.
- **Mongoose Schema Validation**: Custom error handling and validation with **Mongoose**.
- **Dashboard**: A user-specific dashboard to view and manage URL analytics.

## Tech Stack

- **Backend**: Express.js, Node.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT (JSON Web Tokens)
- **Password Encryption**: bcrypt
- **Geo-Tracking**: geoip-lite
- **Validation**: Zod, Mongoose Schema Validation

## Installation

To run this project locally, follow these steps:

### Prerequisites

- **Node.js** (version 14 or above)
- **MongoDB** (locally or use MongoDB Atlas)

### Steps

1. **Clone the repository**:
   Open a terminal and run the following command to clone the repository:
   ```bash
   git clone https://github.com/aman3255/Shortify.git
