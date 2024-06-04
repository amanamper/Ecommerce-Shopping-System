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


## Setup and Running

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Git
- 
1. **Cloning the repository:**
### Steps to Run the Application
git clone https://github.com/yourusername/Ecommerce-Shopping-System.git

cd Ecommerce-Shopping-System
   
2. **Compile the project:**
- Open your terminal or command prompt.
- Navigate to the project directory where the `src` folder is located.
- Run the following command to compile the Java files:
  ```
  javac -d bin src/*.java src/model/*.java src/model/user/*.java
  ```

3. **Run the application:**
- After successful compilation, run the following command to start the application:
  ```
  java -cp bin MainWebsiteApplication
  ```

4. **Using the Application:**
- Follow the on-screen instructions:
  - **Main Menu:**
    - Sign Up
    - Log In
    - Exit Application
  - **Admin Menu:**
    - Create Product
    - Show All Products
    - Read Product by Id
    - Delete Product by Id
    - Update Product by Id
    - Log Out
  - **Customer Menu:**
    - Search for Products
    - View Cart
    - Checkout
    - Log Out

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request for review.

## License

This project is licensed under the MIT License.

## Acknowledgements

- This project applies fundamental design principles and patterns taught in the course.
- Special thanks to the course instructors for their guidance and support.
