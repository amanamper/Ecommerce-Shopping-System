# Ecommerce-Shopping-System

This project is an implementation of a simplified e-commerce system. It allows customers to browse products, add items to their shopping cart, place orders, and simulate the payment process. The application applies fundamental principles and design patterns to ensure robustness and maintainability.

## Features

- **User Authentication:**
  - Secure login for Admin and Customer roles.
  - Association of cart data with user accounts.

- **Product Catalog:**
  - In-memory catalog of products with essential information.
  - Admin can add, update, delete, and view products.

- **Order Processing:**
  - Customers can add products to their cart and place orders.
  - Uses Singleton and Factory design patterns for cart management and product creation.

- **Payment Processing:**
  - Simulates a payment process using a mock payment gateway.
  - Keeps the payment module separate from core shopping functionality.

- **Logging:**
  - Records important events and transactions for auditing and debugging.

## Design Principles and Patterns

- **SOLID Principles:**
  - **Single Responsibility Principle (SRP):** Each class has a single responsibility.
  - **Open/Closed Principle (OCP):** Classes are open for extension but closed for modification.
  - **Liskov Substitution Principle (LSP):** Subclasses can replace base classes without affecting program correctness.
  - **Interface Segregation Principle (ISP):** Specific interfaces are created to avoid fat interfaces.
  - **Dependency Inversion Principle (DIP):** High-level modules do not depend on low-level modules; both depend on abstractions.

- **Design Patterns:**
  - **Singleton Pattern:** Ensures a single instance of the shopping cart.
  - **Factory Pattern:** Encapsulates product creation.
  - **Builder Pattern:** Provides a fluent interface to construct shopping carts.

## Project Structure
src
├── MainWebsiteApplication.java
├── model
│ ├── Product.java
│ ├── Website.java
│ ├── user
│ │ ├── Admin.java
│ │ ├── Credential.java
│ │ ├── Customer.java
│ │ ├── User.java
└── README.md
