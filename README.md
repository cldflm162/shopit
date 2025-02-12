# ShopIt - E-commerce Application

## Overview
ShopIt is a full-stack e-commerce platform built using the MERN (MongoDB, Express.js, React, Node.js) stack. It provides a seamless shopping experience for users, along with a dedicated portal for retailers to manage their products.

## Features
- **User Authentication & Authorization**: Secure login and registration system with JWT authentication.
- **Product Management**: Retailers can add, update, and delete products, while customers can browse and purchase them.
- **Shopping Cart & Checkout**: Users can add items to their cart and proceed to checkout with secure payment integration.
- **Order Tracking**: Customers can view order history and track order status.
- **Admin Dashboard**: Admins can manage users, products, and orders efficiently.

## Technologies Used
- **Backend**: Node.js, Express.js, MongoDB
- **Frontend**: React.js, JavaScript, Redux
- **Authentication**: JWT, bcrypt.js
- **Payment Integration**: Stripe/PayPal
- **Deployment**: AWS/Heroku

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/cldflm162/shopit.git
   cd shopit
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   STRIPE_SECRET=your_stripe_secret
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## Contribution
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

## Contact
For any queries, reach out via email or create an issue in the repository.

