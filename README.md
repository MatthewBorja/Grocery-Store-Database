# Grocery Store Database
A MySQL database tailored for grocery store management, featuring normalized tables for inventory, transactions, employee roles, store locations, and customer rewards tracking to ensure organized and efficient operations.

## Table of Contents
- About the Project
- Features
- Built With
- Detailed Report

### About the Project
This project is a comprehensive MySQL database tailored to support the needs of a grocery store. Essential data is organized into normalized tables, including Products, Orders, Store locations, Employees, Clerks, Managers, Register Privileges, and Rewards Members. The database efficiently handles inventory management, transaction tracking, employee roles and access, multi-store location data, and customer rewards information. By applying normalization rules, the design reduces redundancy and improves data integrity, ensuring the database is well-optimized for scalability and reliable performance in a retail environment.

### Features
1. Inventory Management
   - Stores comprehensive information on all products, including UPC, descriptions, quantities, and pricing.
   - Supports quick updates and retrieval of product details for efficient stock management.
2. Transaction Tracking
   - Records detailed transaction data, including date, time, items purchased, and clerk who processed the transaction.
   - Incorporates Rewards number into each transaction.
4. Employee Management
   - Organizes employee records, including names, contact information, hire dates, positions, salaries, and assigned store locations.
   - Classifies employees into roles (i.e. clerks and managers), with separate tables for role-based data segmentation.
6. Access Control for Register Operations
   - Provides secure register access by storing passwords for clerks with register privileges
   - Ensures only authorized clerks can process transactions, interoperable with register software to ensure access is authorized.
8. Scalable for Multiple Stores
   - Tracks information for each store location, including addresses and phone numbers, supporting business with multiple locations.
10. Customer Rewards
    - Manages rewards member data, including names, contact information, preferred store, and email.
    - Supports loyalty programs by linking transactions to customer accounts, enabling targeted promotions and personalized marketing.

### Built With
- MySQL - The Relational Database System

### Detailed Report
For a detailed breakdown of the business rules, methodology, schemas, designs, normalization processes, and more please refer to my report:
[Database Report](https://github.com/MatthewBorja/Grocery-Store-Database/blob/07346c78fd1be30876df7c9634c5f89329959795/Database%20Report.pdf)
