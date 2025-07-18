# 🚗 Car Rental MERN App

A comprehensive full-stack car rental application built with the MERN stack (MongoDB, Express, React, Node.js). This project features a complete user workflow for Browse and booking cars, alongside a powerful admin dashboard for managing vehicles, users, and bookings.

## ✨ Live Demo

View the deployed application here: [https://car-rental-puce-theta.vercel.app/](https://car-rental-puce-theta.vercel.app/)

***

## 🌟 Features

* **User Authentication**: Secure user registration and login system using JSON Web Tokens (JWT).
* **Car Listings**: View all available cars with details like image, model, capacity, and rent per hour.
* **Date-Based Booking**: Select booking slots with a calendar to check car availability and book for specific time periods.
* **My Bookings Page**: Users can view and manage their personal booking history.
* **Admin Dashboard**:
    * **Full CRUD on Cars**: Admins can add, update, and delete car listings.
    * **Booking Management**: View and manage all user bookings.
    * **User Management**: View a list of all registered users.
* **Image Handling**: Backend image uploads are handled using [ImageKit.io](https://imagekit.io/) for on-the-fly optimization and transformation.
* **Responsive UI**: Built with the Ant Design library for a clean, modern, and responsive user interface.
* **State Management**: Centralized state management on the client-side using Redux.

***

## 🛠️ Tech Stack

### Frontend
* **React.js**: A JavaScript library for building user interfaces.
* **Redux**: For predictable state management.
* **Ant Design (AntD)**: A React UI library for high-quality components.
* **React Router**: For declarative routing in React.
* **Axios**: For making HTTP requests from the browser.

### Backend
* **Node.js**: A JavaScript runtime environment.
* **Express.js**: A web application framework for Node.js.
* **MongoDB**: A NoSQL database for storing data.
* **Mongoose**: An ODM library for MongoDB and Node.js.
* **JSON Web Token (JWT)**: For secure user authentication.
* **ImageKit.io**: For real-time image optimization and storage.

***

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

* Node.js (v14 or later)
* npm & npx
* MongoDB (local or a cloud instance like MongoDB Atlas)

### Installation

1.  **Clone the repository**
    ```sh
    git clone [https://github.com/adityadubey98/CarRental.git](https://github.com/adityadubey98/CarRental.git)
    ```
2.  **Navigate to the project directory**
    ```sh
    cd CarRental
    ```
3.  **Install Backend Dependencies**
    ```sh
    cd server
    npm install
    ```
4.  **Install Frontend Dependencies**
    ```sh
    cd ../client
    npm install
    ```

### Environment Variables

Before running the server, you need to create a `.env` file in the `server` directory. Copy the contents of `.env.example` or create it from scratch with the following variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

# ImageKit.io Credentials
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
