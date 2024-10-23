
# Full Stack E-Commerce Website

## Overview

This project is a full stack e-commerce website built using the MERN stack (MongoDB, Express, React, Node.js). The website provides users with an interactive shopping experience, featuring various product categories, a user-friendly interface, and an admin panel for managing the inventory and product listings.

## Features

- **Responsive Design**: The website adapts seamlessly to different screen sizes, including mobile, tablet, and desktop views.
- **Category Navigation**: Users can navigate between different categories like Men's, Women's, and Kids' collections.
- **Product Listing**: Each product is displayed with detailed information, including size options and prices.
- **Search and Filter**: Users can search for products and apply filters for a more refined shopping experience.
- **Admin Panel**: The admin can manage products by adding, updating, or deleting items in the inventory, along with the ability to upload images.
- **User Authentication**: Sign-up and login functionality is provided, with authentication tokens stored securely.
- **Add to Cart**: Users can add products to their cart and proceed to checkout.
- **Responsive Layout**: The entire website is optimized for multiple devices with smooth transitions and display adjustments based on the screen size.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (using MongoDB Atlas)
- **Authentication**: JSON Web Token (JWT) for user authentication
- **File Uploads**: Multer for handling image uploads

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-repo-url.git
    ```

2. **Backend Setup**:
    - Navigate to the backend folder:
        ```bash
        cd backend
        ```
    - Install dependencies:
        ```bash
        npm install
        ```
    - Create a `.env` file for environment variables:
        ```
        MONGO_URI=your-mongodb-uri
        JWT_SECRET=your-jwt-secret
        PORT=4000
        ```
    - Run the server:
        ```bash
        node index.js
        ```

3. **Frontend Setup**:
    - Navigate to the frontend folder:
        ```bash
        cd frontend
        ```
    - Install dependencies:
        ```bash
        npm install
        ```
    - Run the React app:
        ```bash
        npm start
        ```

## Usage

- **Admin Panel**: To access the admin panel, login with the admin credentials and navigate to the admin page where products can be managed.
- **Product Display**: Users can browse the products, select different categories, and view detailed product information on individual product pages.
- **Checkout**: After adding products to the cart, users can proceed to checkout and review their order before confirming.

## Features in Progress

- **Payment Integration**: Work is in progress to integrate Stripe for payment processing.
- **Order History**: Users will be able to view their order history and track their purchases.

## Contribution

Feel free to fork this project and contribute by submitting pull requests. All kinds of contributions, such as bug fixes, feature enhancements, and new ideas, are welcome!
