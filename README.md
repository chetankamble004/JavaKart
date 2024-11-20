JavaKart - Online Shopping System
JavaKart is a simulated online shopping platform designed to provide an easy and user-friendly experience for shopping across various product categories such as laptops, smartphones, watches, and shoes. This project demonstrates key concepts of object-oriented programming in Java, including classes, methods, and data structures. It also covers fundamental concepts of authentication, user interaction, cart management, and payment processing.

Project Structure
This project consists of three main packages: com.service, com.model, and com.customer, each of which serves a specific purpose in the overall functioning of the system.

1. com.service.JavaKart:
Purpose: Handles the main business logic of the online shopping platform, including user registration, login, product management, cart management, and payment processing.
Key Features:
Registration: Allows new users to register with personal information such as name, mobile number, email, username, and password.
Login: Provides login functionality to registered users via username or email and password.
Product Management: Displays different product categories and product details for laptops, smartphones, watches, and shoes.
Shopping Cart: Allows users to add items to the cart, delete items, and proceed to checkout.
Payment Options: Supports multiple payment methods such as Net Banking and Cash on Delivery.
Price Management: Keeps track of product prices using lists and maps.

2. com.model.User:
Purpose: Represents the User model, which holds user information such as name, mobile number, email, username, and password.
Key Features:
Encapsulates user data with getter and setter methods.
Used by the JavaKart service class to store and retrieve user details.

3. com.customer.Test:
Purpose: Serves as the entry point of the application. It handles user interaction via the console, allowing the user to choose between registering, logging in, or exiting the application.
Key Features:
Displays the main menu with options for registration, login, or exit.
Interacts with the JavaKart service class to initialize products, manage user registration and login, and start the shopping process.
