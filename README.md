# 🎬 Movie Ticket Booking Management Application

A full-stack Movie Ticket Booking Management Application that allows users to browse movies, check show availability, select seats, calculate booking costs, and confirm movie ticket bookings. Administrators can manage movies, cinemas, screens, and shows through the application.

## 📌 Project Overview

The Movie Ticket Booking Management Application is designed to simplify the movie ticket booking process by providing an interactive and user-friendly platform.

The system supports both regular users and administrators. Users can browse available movies, view shows, select seats, and make bookings, while administrators can manage movie and show-related information.

## ✨ Features

### 👤 User Features

- User registration and login
- Secure authentication using JWT
- Browse available movies
- View movie details
- Check available shows
- View available seats
- Select seats for booking
- Calculate total booking cost
- Confirm ticket booking
- View booking details
- Receive booking confirmation
- Real-time seat availability

### 🔐 Admin Features

- Admin authentication
- Manage movies
- Manage cinemas
- Manage screens
- Manage shows
- View booking information
- Maintain movie and show data

## 🛠️ Technologies Used

### Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- Vite

### Backend

- Node.js
- Express.js
- REST API
- Socket.IO
- JWT Authentication

### Database

- PostgreSQL
- Prisma ORM

### Development Tools

- Visual Studio Code
- Git
- GitHub
- npm

## 🏗️ Project Structure

```text
movie-ticket-booking-management/
│
├── backend/
│   ├── prisma/
│   │   ├── migrations/
│   │   ├── schema.prisma
│   │   └── seed.js
│   │
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── server.js
│   │
│   ├── package.json
│   └── .env.example
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── docs/
├── README.md
├── LICENSE
└── render.yaml
