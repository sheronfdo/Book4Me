# Book4Me

## Overview

**Book4Me** is a mobile commerce (M-commerce) platform designed to facilitate the buying, selling, and exchanging of books through a secure, user-friendly, and efficient multi-vendor e-commerce system. Developed as part of the Handheld Device Programming II module at the Java Institute for Advanced Technology, Book4Me aims to provide a modern, scalable marketplace for book enthusiasts, individual sellers, bookstores, and distributors worldwide.

The platform addresses challenges in existing book trading platforms, such as high commission fees and lack of structured inventory management, by offering a centralized and intuitive solution.

The project comprises three core components:

- **Customer App** for browsing and purchasing books
- **Seller App** for managing inventory and orders
- **Backend API** for handling business logic and data operations

These components work together to deliver a seamless experience for users, ensuring high standards of security, performance, and usability.

---

## Project Goals

- Create a user-friendly and secure platform for book transactions, enabling customers to discover and purchase books while providing sellers with robust inventory management tools.
- Bridge the gap in digital book marketplaces by offering free listings for sellers and a centralized book database to avoid duplicate entries.
- Ensure scalability, reliability, and real-time synchronization for a global user base.
- Enhance the book trading experience with features like secure payments, real-time notifications, and intuitive interfaces.

---

## Components

### Customer App

A mobile application designed for book enthusiasts to browse, search, and purchase books from multiple vendors.

**Key Features:**

- Search and browse books by title, author, category, or tags
- View detailed book information, including descriptions, prices, conditions, and seller contact details
- Add books to a shopping cart and complete purchases via secure PayPal integration
- Track order history and receive real-time notifications for order updates and promotions
- Support for Google Sign-In for easy and secure user authentication

**Repository:** [Book4Me-Customer](https://github.com/sheronfdo/Books-For-Me-Customer)

---

### Seller App

A mobile application tailored for sellers to manage their book listings, inventory, and orders efficiently.

**Key Features:**

- Add, update, or delete book listings with details like title, author, ISBN, category, price, and stock availability
- Search for existing books in the centralized database before adding new listings
- Manage orders, update order statuses (e.g., processing, shipped), and track sales performance
- Receive notifications for new orders and low stock alerts
- Secure seller registration and profile management

**Repository:** [Book4Me-Seller](https://github.com/sheronfdo/Books-For-Me-Seller)

---

### Backend API

The core of the platform, managing data operations, user authentication, and communication between the Customer and Seller Apps.

**Key Features:**

- RESTful endpoints for user management, book inventory, order processing, and payment integration
- Centralized book database to ensure consistent data across sellers and customers
- Secure user authentication and authorization using Firebase Authentication
- Real-time data synchronization for book listings and order updates
- Integration with PayPal for secure transaction processing

**Repository:** [Book4Me-API](https://github.com/sheronfdo/Books-For-Me-API)

---

## Target Audience

- **Customers:** Book enthusiasts, students, and professionals seeking an accessible platform to discover and purchase books
- **Sellers:** Individual sellers, bookstores, and distributors looking to manage and sell books efficiently
- **Administrators:** System administrators monitoring platform activity and managing user interactions
- **Developers:** Contributors interested in building scalable mobile and backend applications

---

## Key Features

- **User Management:** Secure registration and login for customers (Google Sign-In) and sellers (email/password)
- **Book Management:** Sellers can add, update, or delete books with detailed metadata
- **Book Discovery:** Customers can browse featured books or search with advanced filters
- **Shopping Cart & Checkout:** Cart management and secure PayPal checkout
- **Order Management:** Track and update order statuses
- **Notifications:** Real-time updates via Firebase Cloud Messaging
- **Multimedia & Location:** Image upload and Google Maps integration for location verification

---

## Technology Overview

- **Frontend:** Android apps (Java, Android SDK, XML, LiveData, ViewModel)
- **Backend:** Spring Boot for business logic
- **Database:** Firebase Firestore (NoSQL, real-time sync)
- **Authentication:** Firebase Authentication
- **Notifications:** Firebase Cloud Messaging
- **Payment Gateway:** PayPal SDK
- **Dev Tools:** Android Studio, IntelliJ IDEA, Postman, Firebase Console

---

## Non-Functional Requirements

- **Performance:** <3s response time for critical operations; 100+ concurrent users supported
- **Security:** HTTPS, Firebase Auth, Firestore security rules
- **Usability:** Clean, responsive UI for Android (API level 34+)
- **Scalability:** >10,000 listings supported with dynamic scaling

---

## Comparative Advantage

- Free listings for sellers
- Centralized book data management
- Book exchange features
- Lightweight, mobile-first Android design

---

## Future Enhancements

- **JWT Authentication:** Secure token-based access control
- **Super Admin Panel:** Admin dashboard for monitoring and analytics
- **Advanced Analytics:** Seller insights and behavior trends
- **Expanded Payment Options:** Support for cards and mobile wallets
- **Multi-Vendor Support:** API integration for large-scale distributors

---

## Contributing

We welcome contributions to Book4Me!

1. Visit the component repositories:
   - [Book4Me-Customer](https://github.com/sheronfdo/Books-For-Me-Customer)
   - [Book4Me-Seller](https://github.com/sheronfdo/Books-For-Me-Seller)
   - [Book4Me-API](https://github.com/sheronfdo/Books-For-Me-API)
2. Review open issues and tasks.
3. Fork the repo, make changes, and submit a pull request.
4. Follow the contribution guidelines outlined in each repository.

---

## License

This project is licensed under the MIT License. See individual repositories for license files.

---

## Contact

For questions or inquiries, contact the project maintainer at:

**Email:** sheronfdo@example.com  
**Issues:** Open an issue in the respective repository.

---

> **Note:** This repository serves as the central hub for project documentation. All code and implementation details are maintained in the following repositories:
>
> - [Book4Me-Customer](https://github.com/sheronfdo/Books-For-Me-Customer)
> - [Book4Me-Seller](https://github.com/sheronfdo/Books-For-Me-Seller)
> - [Book4Me-API](https://github.com/sheronfdo/Books-For-Me-API)
