# Pharmacy Database Management System

This project represents the design and implementation of a relational database system for managing pharmacy operations using MySQL.

##  Project Overview

The system manages:

- Medical products (name, unique ID, type, indication, price, expiration date, quantity)
- Pharmacy sections and product categorization
- Insurance companies and contract tracking
- Customer electronic cards and balance management
- Sales transactions (cash, installment, insurance card)
- Sales details and inventory tracking

##  Database Design

The project includes:

- Entity Relationship Diagram (ERD)
- Relational schema design
- Primary and foreign key constraints
- Business scenario documentation
- Data normalization

### Main Tables

- products
- sections
- companies
- cards
- sales
- salesdetails

##  Advanced SQL Features

### Stored Procedures
- Retrieve medication price and section location
- Detect out-of-stock medications
- Automatically update stock after sales
- Search for alternative medications
- Generate expiration alerts

### Functions
- Calculate monthly pharmacy sales
- Check insurance contract expiration dates

### Trigger
- Automatically decrease customer card balance after a sale transaction

##  Concepts Applied

- Relational Database Design
- Business Logic Implementation inside the Database
- Cursors
- Dynamic SQL (PREPARE / EXECUTE)
- Inventory Management Logic
- Sales Automation

##  Technologies Used

- MySQL
- SQL (Stored Procedures, Functions, Triggers)
- ERD Modeling
- Database Normalization
