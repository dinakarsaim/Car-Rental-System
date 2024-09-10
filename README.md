# Car Rental System

## Overview
This is a C++ based car rental system with MongoDB integration. The system provides functionalities for customers, employees, and managers to interact with the car rental database. Users can perform operations such as renting cars, returning cars, viewing profiles, and managing the database.

## Dependencies
- MongoDB C++ Driver
- C++11 compatible compiler
- pkg-config

## Installation
1. Install MongoDB C++ Driver. Instructions for installation can be found [here](https://www.mongodb.com/docs/manual/installation/).
2. Compile the main file Car_Rental.cpp using the following command: g++ Car_Rental.cpp -o Car_Rental $(pkg-config --cflags --libs libmongocxx) -std=c++11

## User Types and Functions

### Customer
- Show Profile: View customer profile information.
- Rent Car: Rent a car from the available inventory.
- Return Car: Return a rented car.
- Rented Cars: View the list of cars currently rented by the customer.
- Customer Record: View historical records of the customer's transactions.

### Employee
- Show Profile: View employee profile information.
- Rent Car: Rent a car on behalf of a customer.
- Return Car: Process car returns.
- Rented Cars: View the list of cars currently rented out.
- Employee Record: View historical records of the employee's transactions.

### Manager
- Show All Cars: Display all cars available in the inventory.
- Show All Customers: Display information about all customers.
- Show All Employees: Display information about all employees.
- Database Operations on Cars: Perform operations like adding, updating, or deleting cars from the database.
- Database Operations on Customers: Perform operations like adding, updating, or deleting customer records from the database.
- Database Operations on Employees: Perform operations like adding, updating, or deleting employee records from the database.

## Files
- Car_Rental.cpp: Main file containing the implementation of the car rental system.

## Contribution
- Dinakar Reddy
