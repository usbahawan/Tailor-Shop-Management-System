# Tailor Shop Management System - Database Project

A comprehensive desktop application designed to streamline the operations of a tailor shop. This system manages customers, employees, measurements, and orders, providing an efficient workflow for tailoring businesses.

## 🚀 Key Features

- **Admin Authentication**: Secure login for administrative access.
- **Customer Management**: Add, view, and delete customer records.
- **Employee Tracking**: Manage employee details and view staff information.
- **Measurement Management**: 
  - Store detailed measurements for Kameez (Length, Width) and Shalwar (Length, Waist).
  - Track Sleeves length and other custom fitting details.
- **Order Processing**: Book and manage customer orders seamlessly.
- **Comprehensive Dashboard**: Centralized hub to access all management modules.

## 🛠️ Technology Stack

- **Language**: Java
- **Framework**: Java Swing (GUI)
- **Database**: Microsoft SQL Server
- **Connectivity**: JDBC (Java Database Connectivity)

## 📋 Prerequisites

Before running the application, ensure you have the following installed:
- **JDK (Java Development Kit)**: Version 8 or higher.
- **Microsoft SQL Server**: To host the management database.
- **JDBC Driver**: `mssql-jdbc` for SQL Server connection.

## ⚙️ Database Configuration

The application connects to a database named `TailorShopManagementSystem`. 

### Connection Details (Default):
- **Database Name**: `TailorShopManagementSystem`
- **Port**: `1433`
- **Username**: `sa`
- **Password**: `12345`

> [!IMPORTANT]
> Ensure that the SQL Server Browser service is running and TCP/IP protocol is enabled in SQL Server Configuration Manager.

## 🚀 Getting Started

1. **Clone the project**:
   ```bash
   git clone <repository-url>
   ```
2. **Setup Database**:
   - Create a database named `TailorShopManagementSystem` in SQL Server.
   - Run the necessary SQL scripts to create tables (CustomerDetails, MeasurementDetails, EmployeeDetails, etc.).
3. **Configure Connection**:
   - Update `ConnectionProvider.java` if your SQL Server credentials differ from the defaults.
4. **Compile and Run**:
   - Run `AdminLogin.java` to start the application with the login screen.

## 📸 Project Structure

- `AdminLogin.java`: Entry point for the application.
- `Dashboard.java`: Main navigation hub.
- `ConnectionProvider.java`: Database connection logic.
- `*.form`: NetBeans GUI Designer files for the interface.

---
---
**Note:** This project was created as a part of the **3rd Semester Database Course Semester Project**.
