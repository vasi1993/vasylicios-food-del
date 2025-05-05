# Vasylicious - Food Delivery Application

## Watch it -> https://vasylicious.netlify.app/

Demo Login Credentials

To quickly test the application, you can log in using the following demo account:
Email: user.vasy@gmail.com
Password: 12345678

Alternatively, you can register a new account directly from the application.

Vasylicious is a full-stack food delivery application that allows users to browse a variety of food items, add them to their cart, place orders, and view their order history. The application includes a powerful backend that manages user authentication, shopping cart management, and product management, while the frontend is interactive and easy to use.
Technologies Used
Frontend

    React.js - main library for building the user interface

    Vite - for fast configuration and optimization of the application

    CSS and Styled Components for styling the interface

Backend

    Node.js with Express.js - server that handles API requests

    MongoDB - for storing data about users, products, and orders

    JWT for user authentication

    Stripe for payment processing

Other Technologies

    Render.com for hosting the backend

    Netlify for hosting the frontend

Features
For Users

    Browse Products: Users can view a list of available food items.

    Add to Cart: Users can add products to their shopping cart.

    Place Orders: Users can place orders and view the status of their orders.

    View Order History: Users can view past orders placed on the platform.

For Admins

    Manage Products: Admins can add, update, or delete food items.

    Manage Orders: Admins can view and manage customer orders.

Setup and Installation
Prerequisites

    Node.js (v14 or higher)

    MongoDB account and database

    Stripe account for payment processing

Frontend Setup

    Clone the repository:

git clone https://github.com/your-username/vasylicious.git
cd vasylicious

Install the dependencies:

cd frontend
npm install

Create a .env file in the frontend directory and add the following:

VITE_API_URL=https://your-backend-url.com

Run the development server:

    npm run dev

    Visit http://localhost:3000 to view the app.

Backend Setup

    Clone the repository:

git clone https://github.com/your-username/vasylicious.git
cd vasylicious

Install the dependencies:

cd backend
npm install

Create a .env file in the backend directory and add the following:

JWT_SECRET=your-jwt-secret
STRIPE_SECRET_KEY=your-stripe-secret-key
MONGO_URI=your-mongo-uri

Start the backend server:

    npm run start

    Visit the backend at http://localhost:4000.

Deployment
Deploying Frontend on Netlify

    Go to Netlify and create an account if you haven't already.

    Click on "New Site from Git" and connect your GitHub repository.

    Set the build command to npm run build and the publish directory to dist.

    Deploy your site!

Deploying Backend on Render

    Create an account on Render.

    Create a new Web Service and choose the Node.js option.

    Set the environment variables in Render (such as JWT_SECRET, STRIPE_SECRET_KEY, etc.).

    Deploy your backend!

Once deployed, you will get a public URL for your backend, such as https://vasy-backend.onrender.com.
License

This project is licensed under the MIT License - see the LICENSE file for details.
