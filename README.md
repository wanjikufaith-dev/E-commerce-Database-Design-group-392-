# 📦 E-commerce Database Design Group-392

## 🚀 Project Overview
This project is a **collaborative group assignment** to design and implement a robust database for an e-commerce platform. The database is structured to handle product details, variations, categories, and attributes efficiently, while supporting scalability for real-world e-commerce applications.

---

## 🎯 Objectives
1. Design and document an **Entity-Relationship Diagram (ERD)**.
2. Implement the database schema using **MySQL**.
3. Ensure the database supports key e-commerce functionalities like product variations, attributes, and categories.
4. Enable a collaborative workflow using **GitHub** for version control and teamwork.

---

## 🗃️ Database Features
The e-commerce database includes the following tables and features:

### **Core Tables**
- **`brand`**: Stores brand-related information.
- **`product_category`**: Categorizes products into types (e.g., clothing, electronics).
- **`product`**: Manages general product details like name, brand, and base price.
- **`product_image`**: Links products to their images using URLs.

### **Variation and Attribute Tables**
- **`color`**: Defines available color options for products.
- **`size_category`** and **`size_option`**: Handles product size variations.
- **`product_variation`**: Links products to their size and color variations.
- **`product_attribute`**: Stores custom attributes such as material or weight.
- **`attribute_category`** and **`attribute_type`**: Categorize and define attribute types (e.g., text, number, boolean).
