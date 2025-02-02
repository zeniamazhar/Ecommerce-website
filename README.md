# Spectacles E-commerce Store

This repository is for showcasing a fully functional spectacles e-commerce platform built using **React**, **Node.js**, and **MongoDB**, it includes both a customer-facing storefront and an admin interface to manage products, orders, and users. The source code has been redacted for security reasons.

---
![](https://www.youtube.com/watch?v=U__G38iXxmM)

## Features

### Customer Interface:
1. **Product Browsing**:
   - Browse products by category.
   - Search and sort products by name, description, price, or popularity.
   - View detailed product descriptions, prices, and stock availability.

2. **Shopping Cart**:
   - Add, update, or remove items in the cart.
   - View cart summary and total price before checkout.

3. **User Accounts**:
   - Register and log in to make purchases.
   - View order history and order statuses (Processing, In-Transit, Delivered).

4. **Reviews and Ratings**:
   - Leave reviews and ratings for purchased products.
   - Reviews require admin approval before publication.

5. **Secure Checkout**:
   - Mock credit card processing for orders.
   - Invoice generation and email delivery in PDF format.

### Admin Interface:
1. **Product Management**:
   - Add, edit, or remove products and categories.
   - Update stock levels.

2. **Order Management**:
   - View and process orders.
   - Update order statuses.

3. **Customer Feedback**:
   - Approve or reject product reviews.

4. **Analytics**:
   - View revenue and profit/loss reports for specific date ranges.
   - Visualize sales data with charts.

---

## Tech Stack

### Frontend:
- **React**: For building the customer-facing interface and admin dashboard.
- **React Router**: For seamless navigation between pages.

### Backend:
- **Node.js**: Server-side application.
- **Express.js**: Backend framework for creating RESTful APIs.

### Database:
- **MongoDB**: NoSQL database for storing products, orders, and user data.

### Additional Tools:
- **JWT**: For secure user authentication.
- **Nodemailer**: To send order invoices via email.
- **Mongoose**: For MongoDB object modeling.

