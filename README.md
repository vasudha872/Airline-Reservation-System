# Airline-Reservation-System
**Overview**

The Airline Reservation System is a database-driven application designed to manage airline operations effectively. It enables administrators and customers to interact with the system for managing flights, bookings, customer details, and payments. The system leverages structured database schemas, stored procedures, and triggers to ensure data consistency and integrity.

**How to Use**

Setup the Database

Create the Airline database using the provided schema.
Populate initial data for tables like Admin, Planes, and Payment.

Use Stored Procedures

Use the insert_cust procedure for adding customer data programmatically.
Trigger Integration

The Before_Insert_User trigger will automatically enforce data integrity during customer addition.
Maintain Referential Integrity

Ensure all foreign key dependencies are satisfied during operations.

**Technologies Used**

Database: MySQL

Triggers and Procedures: MySQL stored routines for automation and validation

Schema Design: Normalized tables with primary and foreign key relationships

Languages used:HTML/CSS, php

Local server: Apache

**Future Enhancements**

Integrate a user interface for better interaction with the system.
Add real-time flight status tracking.
Enhance security features with advanced password encryption.
