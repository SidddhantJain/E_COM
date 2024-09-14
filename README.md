E-Commerce Website
Project Overview
This project is a custom e-commerce frontend built with HTML, CSS, and JavaScript. The main objective is to create a responsive, interactive shopping platform by integrating the Fake Store API to populate the product and cart pages. The website includes various features like a shopping cart, user authentication (via a limited API), and dynamic product/category displays.

Table of Contents
Features
Technologies Used
Folder Structure
Installation
Usage
API Integration
Future Enhancements
Contributing
License
Features
Responsive Design: Built with Bootstrap to ensure mobile-friendly interfaces.
Shopping Cart: Users can add/remove items from the cart, and the data is stored in local storage.
API Integration: Product data is fetched from the Fake Store API.
Dynamic Product Display: AJAX is used to fetch and display products and categories dynamically without page reloads.
User Authentication: Basic login/logout functionality using a limited external API.
Breadcrumb Navigation: Simplifies user navigation through product categories.
Hover Effects: Added hover effects on products to enhance interactivity.
Technologies Used
HTML5: Structure and layout of the website.
CSS3 / SCSS: Styling and layout. SCSS is used for better stylesheet management.
JavaScript (ES6): Core logic for handling dynamic content, API calls, and local storage.
AJAX: Fetching data from the Fake Store API asynchronously.
Bootstrap 5: For responsive and modern design components.
Fake Store API: Provides product data for the e-commerce platform.

Usage
Homepage: Displays product categories and featured products fetched via AJAX from the Fake Store API.
Product Page: Clicking on a product displays detailed information such as price, description, and an image.
Shopping Cart: Users can add items to their cart, which is stored in local storage.
Login/Logout: A basic login page allows users to authenticate using a limited external API.
Wishlist & Cart Pages: These pages are in development but have basic styling and structure implemented.
API Integration
Fake Store API: The site uses this API to fetch product details dynamically.

GET All Products: https://fakestoreapi.com/products
GET Product by ID: https://fakestoreapi.com/products/{id}
GET Categories: https://fakestoreapi.com/products/categories
User Authentication API: (Limited)

A basic API is used to manage user login/logout functionality. This can be expanded for more robust features in the future.
Future Enhancements
Full User Authentication: Implement a robust system for user sign-up, login, and session management.
Wishlist Functionality: Allow users to save products to a wishlist for future purchases.
Checkout System: Integrate payment gateway APIs for real-world e-commerce functionality.
Product Reviews: Enable users to submit reviews for products.
Admin Dashboard: Build a back-end for managing products and orders.
