# Library Management System Database

## Description
This project implements a comprehensive database for a Library Management System using MySQL. The database tracks books, authors, publishers, library members, loans, reservations, and fines. It's designed to support all core operations of a modern library.

## Features
- Tracks book inventory with multiple copies
- Manages author and publisher information
- Handles member registrations and memberships
- Processes book loans and returns
- Manages reservations and waitlists
- Tracks fines and payments
- Maintains staff information
- Includes audit logging

## Database Schema
The database consists of 12 main tables with appropriate relationships:
- Publisher, Author, Genre (reference data)
- Book, Book_Copy (inventory)
- Member, Loan, Fine, Reservation (patron services)
- Staff (personnel)
- Audit_Log (system tracking)

## Setup Instructions

1. Make sure you have MySQL installed
2. Clone this repository
3. Run the SQL script to create the database:

```bash
mysql -u username -p < library_db.sql
