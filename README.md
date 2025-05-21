# Inventory Tracking System

## 📘 Description

The Inventory Tracking System is a MySQL-based relational database designed to help organizations manage stock efficiently. It tracks products, suppliers, stock inflows (deliveries), stock outflows (issuances), and real-time inventory levels.

This system is ideal for businesses that need to monitor inventory movement and maintain accurate stock records.

---

## 🛠️ Features

- Manage supplier details
- Store and track product information
- Record stock received from suppliers
- Record stock issued to internal or external recipients
- Monitor real-time inventory levels with timestamps

---

## 🗂️ Database Entities

- **Suppliers**: Stores information about suppliers
- **Products**: Holds data on inventory items
- **StockIn**: Tracks all incoming stock
- **StockOut**: Tracks all outgoing stock
- **Inventory**: Maintains current quantity for each product

---
## 📁 File Structure

InventoryTrackingSystem/
│
├── inventory_tracking.sql     # SQL script with all table definitions
├── README.md                  # This file
└── inventory_erd.png          # ERD diagram


## 💾 How to Run/Setup the Project

1. Open your MySQL client.
2. Create the database:
   ```sql
   CREATE DATABASE inventory_db;
   USE inventory_db;

![image](https://github.com/user-attachments/assets/1e362c86-3d61-4e39-b34b-c224338d158b)
