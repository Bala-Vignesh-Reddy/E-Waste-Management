
# E-Waste Management Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Payment Gateway Integration](#payment-gateway-integration)
- [Contact](#contact)

## Introduction
The E-Waste Management Project is a web application designed to facilitate the efficient disposal and recycling of electronic waste. The platform allows users to sell their e-waste to vendors, who can then manage their inventory and track payment history. The application integrates with the Stripe payment gateway to ensure secure and seamless financial transactions.

## Features
- **User Registration and Authentication**: Users can sign up, log in, and manage their profiles.
- **Vendor Dashboard**: Vendors can view orders, manage inventory, and track payment history.
- **E-Waste Listing**: Users can list e-waste items for sale with detailed descriptions and pricing.
- **Order Management**: Vendors can manage incoming orders and update their status.
- **Payment Integration**: Secure payment processing using Stripe.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: Sql
- **Payment Gateway**: Stripe
- **Version Control**: Git

## Payment Gateway Integration
The project uses Stripe to handle all payment transactions. Stripe ensures secure and reliable payment processing.

### Stripe Setup
1. **Create a Stripe Account**:
    - Sign up at [Stripe](https://stripe.com/).

2. **Obtain API Keys**:
    - Navigate to the Developers section in the Stripe Dashboard.
    - Obtain your Secret Key and Publishable Key.

3. **Environment Variables**:
    - Add the keys to your `.env` file:
    ```
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. **Integrate Stripe in Code**:
    - Use the Stripe API to handle payment processing in the backend and frontend of your application.

## Contact
If you have any questions or feedback, please feel free to contact us at [reddybalavignesh9979@gmail.com](mailto:your-email@example.com).

