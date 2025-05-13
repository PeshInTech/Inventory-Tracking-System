# Inventory Tracking System

## 📋 Project Description

This project is a complete **Database Management System (DBMS)** for an **Inventory Tracking System** built using **MySQL**. It manages products, categories, suppliers, orders, customers, and sales, ensuring a well-structured relational database with clear relationships and data integrity.

## 🚀 Features

* **Products**: Manage product information including stock levels and pricing.
* **Categories**: Categorize products for better organization.
* **Suppliers**: Track suppliers and their contact information.
* **Orders**: Manage incoming stock orders from suppliers.
* **Customers**: Store customer details for sales tracking.
* **Sales**: Record customer purchases and manage sales data.

## 🗂️ Database Structure

The database includes the following tables:

* **Products** - Stores product information.
* **Categories** - Manages product categories.
* **Suppliers** - Stores supplier contact information.
* **Orders** - Tracks incoming product orders.
* **Order\_Items** - Links orders to specific products (many-to-many).
* **Customers** - Stores customer information.
* **Sales** - Records customer purchases.
* **Sale\_Items** - Links sales to specific products (many-to-many).

## 🔗 ERD (Entity-Relationship Diagram)

![ERD](https://via.placeholder.com/600x400.png)

## 🛠️ Getting Started

### Prerequisites

* **MySQL Server**
* **MySQL Workbench** or any SQL editor

### Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/inventory-tracking-system.git
```

2. Import the **`inventory_tracking_system.sql`** file into your MySQL server.
3. Run the SQL script to create the database and tables.
4. (Optional) Add sample data if required.

## 📝 Usage

* Use SQL queries to insert, update, delete, and fetch data.
* Modify the schema as needed for specific business requirements.

## 📝 SQL File

Ensure you include the **`inventory_tracking_system.sql`** file in the root directory of this repository.

## 🤝 Contributing

Feel free to submit **Pull Requests** or **Issues** to improve this project.

## 📧 Contact

For questions or support, reach out at **[your-email@example.com](mailto:your-email@example.com)**.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Happy Coding! 💻✨
