# eStore

Welcome to Investor_Store , a comprehensive and secure online store application built with Java Persistence API (JPA) and Spring Security. 
This project demonstrates a robust e-commerce platform with a variety of functionalities, including user authentication, product management, 
email notifications, and more.

## Features

- **User Authentication and Authorization:**
    - Secure login and registration using Spring Security.
    - Role-based access control (e.g., Admin, Customer) to manage permissions effectively.

- **Product Management:**
    - Add, edit, delete, and view products.
    - Product categorization and search functionality for easier navigation.
    - Inventory management to track stock levels.

- **Shopping Cart and Checkout:**
    - Add products to the shopping cart and proceed to checkout.
    - Order summary and payment processing.

- **Email Notifications:**
    - Automatic email notifications for order confirmations, password resets, and other key events.
    - Configurable email templates to customize notifications.

- **Secure Transactions:**
    - Integration with secure payment gateways (e.g., Stripe, PayPal).
    - Protection against common web vulnerabilities (e.g., CSRF, XSS).

- **User Profiles:**
    - View and update personal information.
    - Track order history and manage saved addresses.

- **Admin Dashboard:**
    - Manage products, categories, and users.
    - View sales reports and monitor system activities.

- **Advanced Search and Filtering:**
    - Search products by name, category, price range, and other attributes.
    - Sort products based on popularity, rating, or price.

- **Responsive Design:**
    - Fully responsive and mobile-friendly design for a seamless shopping experience across all devices.

## Technologies Used

- **Backend:**
    - Java with Spring Boot
    - JPA/Hibernate for ORM (Object-Relational Mapping)
    - Spring Security for authentication and authorization
    - MySQL/PostgreSQL as the database

- **Frontend:**
    - HTML, CSS, JavaScript
    - Thymeleaf for server-side rendering or React/Vue.js for a modern SPA experience

- **Email Service:**
    - Spring Mail for sending transactional emails
    - Configurable SMTP server integration (e.g., Gmail, SendGrid)

- **Testing:**
    - JUnit and Mockito for unit and integration testing
    - Postman for API testing

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6+
- MySQL/PostgreSQL database
- SMTP server credentials for email service

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Abolaji2K21/Estore.git
   cd Estore
