Book4Me
Overview
Book4Me is a mobile commerce (M-commerce) platform designed to facilitate the buying, selling, and exchanging of books through a secure, user-friendly, and efficient multi-vendor e-commerce system. Developed as part of the Handheld Device Programming II module at the Java Institute for Advanced Technology, Book4Me aims to provide a modern, scalable marketplace for book enthusiasts, individual sellers, bookstores, and distributors worldwide. The platform addresses challenges in existing book trading platforms, such as high commission fees and lack of structured inventory management, by offering a centralized and intuitive solution.
The project comprises three core components: a Customer App for browsing and purchasing books, a Seller App for managing inventory and orders, and a Backend API for handling business logic and data operations. These components work together to deliver a seamless experience for users, ensuring high standards of security, performance, and usability.
Project Goals

Create a user-friendly and secure platform for book transactions, enabling customers to discover and purchase books while providing sellers with robust inventory management tools.
Bridge the gap in digital book marketplaces by offering free listings for sellers and a centralized book database to avoid duplicate entries.
Ensure scalability, reliability, and real-time synchronization for a global user base.
Enhance the book trading experience with features like secure payments, real-time notifications, and intuitive interfaces.

Components
Customer App
The Customer App is a mobile application designed for book enthusiasts to browse, search, and purchase books from multiple vendors.

Key Features:

Search and browse books by title, author, category, or tags.
View detailed book information, including descriptions, prices, conditions, and seller contact details.
Add books to a shopping cart and complete purchases via secure PayPal integration.
Track order history and receive real-time notifications for order updates and promotions.
Support for Google Sign-In for easy and secure user authentication.


Repository: [Book4Me-Customer](https://github.com/sheronfdo/Books-For-Me-Customer)


Seller App
The Seller App is a mobile application tailored for sellers to manage their book listings, inventory, and orders efficiently.

Key Features:

Add, update, or delete book listings with details like title, author, ISBN, category, price, and stock availability.
Search for existing books in the centralized database before adding new listings.
Manage orders, update order statuses (e.g., processing, shipped), and track sales performance.
Receive notifications for new orders and low stock alerts.
Secure seller registration and profile management.


Repository: [Book4Me-Seller](https://github.com/sheronfdo/Books-For-Me-Seller)


Backend API
The Backend API serves as the core of the platform, managing data operations, user authentication, and communication between the Customer and Seller Apps.

Key Features:

RESTful endpoints for user management, book inventory, order processing, and payment integration.
Centralized book database to ensure consistent data across sellers and customers.
Secure user authentication and authorization using Firebase Authentication.
Real-time data synchronization for book listings and order updates.
Integration with PayPal for secure transaction processing.


Repository: [Book4Me-API](https://github.com/sheronfdo/Books-For-Me-API)


Target Audience

Customers: Book enthusiasts, students, and professionals seeking an accessible platform to discover and purchase books.
Sellers: Individual sellers, bookstores, and distributors looking to manage and sell books efficiently.
Administrators: System administrators monitoring platform activity and managing user interactions.
Developers: Contributors interested in building scalable mobile and backend applications.

Key Features

User Management: Secure registration and login for customers (via Google Sign-In) and sellers (via email/password), with profile management and password reset capabilities.
Book Management: Sellers can add, update, or delete books with comprehensive details (e.g., title, author, ISBN, category, condition, images).
Book Discovery: Customers can browse featured books, new arrivals, or search by title/category, with detailed book information and seller contact options.
Shopping Cart & Checkout: Intuitive cart management and secure checkout process with PayPal integration.
Order Management: Customers can track orders, while sellers can update order statuses and manage inventory.
Notifications: Real-time updates for order statuses, new book arrivals, and promotional offers via Firebase Cloud Messaging.
Multimedia and Location: Support for book cover images, seller profile pictures, and location-based features using Google Maps for address verification.

Technology Overview
Book4Me leverages modern technologies to ensure scalability, security, and usability:

Frontend: Android apps for customers and sellers, built using Java and Android SDK, with XML for UI layouts and LiveData/ViewModel for state management.
Backend: Spring Boot for handling write operations and business logic, ensuring efficient data management.
Database: Firebase Firestore for real-time NoSQL data storage and retrieval.
Authentication: Firebase Authentication for secure user login and role-based access control.
Notifications: Firebase Cloud Messaging for real-time push notifications.
Payment Gateway: PayPal SDK for secure transactions.
Development Tools: Android Studio, IntelliJ IDEA, Postman, and Firebase Console for development and testing.

Non-Functional Requirements

Performance: System response times under 3 seconds for major operations (e.g., login, search, checkout) and support for at least 100 concurrent users.
Security: Encrypted data storage and communication via HTTPS, with Firebase Authentication and Firestore security rules to prevent unauthorized access.
Usability: Simple and mobile-friendly UI supporting Android devices (API level 34 or higher).
Scalability: Capable of handling over 10,000 book listings with dynamic scaling via Firebase Firestore.

Comparative Advantage
Book4Me stands out compared to platforms like Amazon and eBay by offering:

Free listings for sellers, reducing barriers for small-scale vendors.
Centralized book data management to streamline inventory across sellers.
Book exchange options, fostering a community-driven marketplace.
Lightweight and mobile-first design optimized for Android users.

Future Enhancements

JWT Authentication: Implement JSON Web Token-based authentication for enhanced security between mobile apps and the Spring Boot backend.
Super Admin Panel: Develop an administrative interface for system monitoring, user management, and analytics.
Advanced Analytics: Provide sellers with detailed sales trends, customer behavior insights, and competitor analysis.
Expanded Payment Options: Add support for credit/debit cards and mobile wallets like Google Pay.
Multi-Vendor Support: Enable book distributors and publishers to manage bulk inventory and integrate via APIs.

Contributing
We welcome contributions to Book4Me! To contribute:

Visit the component repositories for specific details:
Customer App: [Book4Me-Customer](https://github.com/sheronfdo/Books-For-Me-Customer)
Seller App: [Book4Me-Seller](https://github.com/sheronfdo/Books-For-Me-Seller)
Backend API: [Book4Me-API](https://github.com/sheronfdo/Books-For-Me-API)


Review open issues and tasks in each repository.
Fork the relevant repository, make changes, and submit a pull request.
Follow the contribution guidelines outlined in each repository.

For general feedback or suggestions about the project, open an issue in this repository.
License
This project is licensed under the MIT License. See the respective repositories for detailed licensing information.
Contact
For questions or inquiries, contact the project maintainer at sheronfdo@example.com or open an issue in this repository.

Note: This repository serves as the central hub for project documentation. All code and implementation details are maintained in the following repositories:

Customer App: [Book4Me-Customer](https://github.com/sheronfdo/Books-For-Me-Customer)
Seller App: [Book4Me-Seller](https://github.com/sheronfdo/Books-For-Me-Seller)
Backend API: [Book4Me-API](https://github.com/sheronfdo/Books-For-Me-API)

