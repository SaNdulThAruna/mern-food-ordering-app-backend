# 🍔 MERN Food Ordering Platform -- Backend

## 📌 Overview

This is the backend service for a full-stack Food Ordering Platform
built using the MERN stack.\
It provides RESTful APIs for authentication, restaurant management,
search & filtering, cart operations, order processing, Stripe payments,
image uploads, and real-time order updates.

The backend is built with scalability, modularity, and maintainability
in mind using a structured MVC architecture.

------------------------------------------------------------------------

## 🚀 Features

-   🔐 User Authentication & Authorization (JWT-based)
-   🍽 Restaurant Management (Create, Update, Delete, Search)
-   🔎 Advanced Search & Filtering
-   🛒 Cart Management
-   💳 Stripe Payment Integration
-   🖼 Image Uploads via Cloudinary
-   📦 Order Management
-   🔄 Real-time Order Status Updates
-   ☁️ Deployed on Render

------------------------------------------------------------------------

## 🛠 Tech Stack

-   **MongoDB** -- NoSQL Database
-   **Express.js** -- Backend Framework
-   **Node.js** -- Runtime Environment
-   **Stripe** -- Payment Processing
-   **Cloudinary** -- Image Storage
-   **Render** -- Deployment Platform
-   **TypeScript** -- Type Safety

------------------------------------------------------------------------

## 📂 Project Structure

    src/
     ├── controllers/     # Request handling logic
     ├── middleware/      # Authentication & validation middleware
     ├── models/          # Mongoose schemas
     ├── routes/          # API route definitions
     └── index.ts         # Application entry point

------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

    git clone <your-repo-url>
    cd mern-food-ordering-app-backend

### 2️⃣ Install Dependencies

    npm install

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

    PORT=5000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret

### 4️⃣ Run the Application

Development mode:

    npm run dev

Production mode:

    npm run build
    npm start

------------------------------------------------------------------------

## 💳 Stripe Payment Flow

1.  User places an order.
2.  Backend creates a Stripe payment intent.
3.  Client confirms payment using Stripe.
4.  Order status updates in real-time upon successful payment.

------------------------------------------------------------------------

## 🔐 Authentication Flow

-   JWT-based authentication
-   Protected routes using middleware
-   Role-based access for restaurant owners

------------------------------------------------------------------------

## 🌍 Deployment

The backend is deployed on **Render**. Ensure environment variables are
configured in the Render dashboard before deployment.

------------------------------------------------------------------------

## 📈 Future Improvements

-   Add Redis caching for performance
-   Implement WebSocket-based real-time tracking
-   Add unit & integration tests
-   API documentation using Swagger

------------------------------------------------------------------------

## 👨‍💻 Author

Developed by Sandul Tharuna\
Full-Stack Software Engineer \| MERN Stack Developer

------------------------------------------------------------------------

## 📄 License

This project is licensed under the MIT License.
