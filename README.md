## Food Delivery Web Application (Frontend)

A modern and responsive food delivery web application inspired by Swiggy and Zomato, built using React.js and Bootstrap.
Users can browse food items, add them to the cart, manage quantity, and proceed to checkout after signing in.

## Features
## Home Banner

Attractive banner displayed on the homepage

Highlights offers or featured items

Fully responsive UI

## Product List

Displays all available food items

Each product contains:

Image

Name

Price

Add to Cart button

## Add to Cart

Adds selected products to the cart

Automatically updates:

Total items

Total price

## Cart Management

Increase or decrease item quantity

Remove items from the cart

Real-time price calculation

## Sign-in Required for Checkout

Only logged-in users can place an order

Provides basic authentication flow

Shows “Place Order” button only after signing in

## Responsive Design

UI built with Bootstrap

Works smoothly on mobile, tablet, and desktop

## Tech Stack

React.js

Bootstrap

React Router

React Hooks (useState, useEffect)

LocalStorage / Context API (for storing cart data)

## Project Structure

src/
 ├── components/
 │    ├── Banner.jsx
 │    ├── ProductList.jsx
 │    ├── Cart.jsx
 │    ├── Navbar.jsx
 │    ├── Login.jsx
 │
 ├── assets/
 │    └── images/
 │
 ├── App.js
 └── index.js

 ## Installation & Setup
 ## Clone this repository
 git clone https://github.com/vikashvicky7575/food-website.git

 ## Go inside project folder
 cd food-website

 ## Run the project
 npm start

 ## Future Enhancements

Backend API integration (Node.js + MongoDB)

Payment gateway

Admin panel for product management

User order history page

Product categories and filters
