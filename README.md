# E-commerce Platform

## Overview

Developed a comprehensive E-commerce Platform database using SQLite, designed to manage various aspects of an online retail business. The project involved designing a normalized database schema, implementing complex queries, and ensuring data integrity and efficient data retrieval.

## Database Tables

The database contains the following six tables:

- **Users**: Information about the users of the platform.
- **Products**: Details of the products available for sale.
- **Categories**: Categories to which products belong.
- **Orders**: Information about orders placed by users.
- **OrderDetails**: Details of the products within an order.
- **Reviews**: Reviews provided by users for products.


## Key Features

### User Management

- Maintained detailed user profiles, including personal information and account creation date.
- Ensured unique user identification through email constraints.

### Product and Category Management

- Organized products with relevant details like name, description, price, and category.
- Implemented a category system to facilitate product classification and easy retrieval.

### Order Processing

- Tracked user orders with details such as order date, status, and associated user.
- Captured order-specific product details, including quantity and price, within order line items.

### Product Reviews

- Allowed users to rate and review products, storing ratings and comments along with review dates.
- Enforced rating constraints to maintain review quality and relevance.

## Technical Highlights

- Created a normalized database schema with multiple interconnected tables (Users, Products, Categories, Orders, OrderDetails, Reviews) to ensure data integrity and reduce redundancy.
- Utilized primary and foreign key constraints to establish and enforce relationships between tables.
- Inserted sample data across all tables to simulate real-world scenarios and enable comprehensive testing.
- Developed advanced queries to retrieve and analyze data, such as:
  - Listing all products and filtering by category.
  - Fetching detailed order information for specific users.
  - Calculating total revenue from orders.
  - Generating average product ratings and counting products per category.
- Indexed key columns to enhance query performance and ensured efficient data retrieval.

## Outcome

The E-commerce Platform serves as a robust model for managing an online retail business similar to companies like Amazon, with scalable and maintainable database structures.
