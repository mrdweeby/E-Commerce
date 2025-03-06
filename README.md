# Database Project - E-Commerce Platform

## Project Enhanced Entity-Relationship Diagram
![Image](https://github.com/user-attachments/assets/6cb4b587-3245-4f05-af42-593fcd2ed56a)

## Project Overview
This project is a database implementation for an e-commerce platform inspired by Amazon, Hepsiburada, and Trendyol. It includes user management, shop management, order processing, inventory tracking, and various triggers and constraints to ensure data integrity.

## Database Features
- **User Management**: Customers and shop owners with different attributes.
- **Shop & Product Management**: Shops can list multiple products, manage stock, and apply discounts.
- **Order Processing**: Customers can place orders, use coupons, and make payments.
- **Triggers & Constraints**:
  - Auto-update customer type based on membership expiration.
  - Automatically transfer cart items to orders and update stock.
  - Ensure valid email formats, ZIP codes, and other constraints.

## Setup Instructions
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/Database-Project.git
cd Database-Project
```

### 2. Import Database Schema
Use a database management system (PostgreSQL)

### 3. Load Sample Data 

### 4. Add Triggers

## Usage
- Modify `CreateTables.sql` to match your database engine.
- Use `Triggers.sql` to enforce business rules.
- Load sample date 'Populater.txt'.
- Run SELECT queries to analyze the data.

## Authors
- **Emir Kahraman**
- **Bülent Yıldırım**
- **Alp Kutay Köksal**
- **Tuğrul Akgül**

## License
This project is for educational purposes only.

