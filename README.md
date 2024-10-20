# BUS-TICKET-BOOKING-SYSTEM

## Overview
The Bus Ticket Booking System is a web application designed to facilitate the online booking of bus tickets. It provides users with an easy-to-use interface for searching, booking, and managing bus tickets, along with an admin panel for managing bus schedules and user accounts.

## Features
- **User Registration & Login**: Users can register and log in to their accounts.
- **Search & Book Tickets**: Users can search for available buses based on their travel dates and destinations.
- **View Booking History**: Users can view their previous bookings.
- **Admin Panel**: Admins can manage bus schedules, view user information, and cancel bookings.
- **Responsive Design**: The application is designed to be mobile-friendly.

## Tech Stack
- **Frontend**: [React](https://reactjs.org/), [Vite](https://vitejs.dev/), [Tailwind CSS](https://tailwindcss.com/)
- **Backend**: [Node.js](https://nodejs.org/), [Express](https://expressjs.com/), [Prisma](https://www.prisma.io/), [PostgreSQL](https://www.postgresql.org/)
- **Containerization**: [Docker](https://www.docker.com/)

## Installation
### Prerequisites
- Node.js
- Docker
- Yarn (or npm)

### Steps to Run the Application
1. Clone the repository:
   git clone https://github.com/192121089/BUS-TICKET-BOOKING-SYSTEM.git
2.Navigate to the project directory:
   cd bus-ticket-booking-system

3.Set up the backend:
Navigate to the backend folder:  
   cd backend

4.Install dependencies:
   yarn install

5.Run the Prisma migrations:
   npx prisma migrate dev

6.Start the backend server:
    yarn dev

Set up the frontend:
Navigate to the frontend folder:

  cd ../frontend
Install dependencies:
     yarn install
Start the frontend server:
     yarn dev
Access the application:

Open your web browser and navigate to http://localhost:5173 for the frontend.
