# Order Management System

A modern and intuitive **Order Management System** designed to streamline operations for garment manufacturing businesses. This system allows seamless management of orders, garments, materials, machines, and users with role-based access control.

---

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Screenshots](#screenshots)
6. [Contributing](#contributing)
7. [License](#license)
8. [Support](#support)

---

## Features

### **Dashboard**

-   Overview of system activity, including order stats, user activity, and machine status.

    ![Dashboard Screenshot](screenshots/Dashboard.png)

### **Login**

-   The login page allows authorized users to securely access the Order Management System.

    ![Login Screenshot](screenshots/login-img.png)

### **Forgot Password**

-   The forgot password functionality allows users to securely reset their password via email if they forget their login credentials.

    ![Forgot Password Screenshot](screenshots/forgot-password.png)

### **User Management**

-   Role-based access control with predefined roles:
    -   **Super Admin**, **Manager**, **Inventory Manager**, **Garment Manager**, **Staff**.
-   Manage users, assign roles, and maintain user details.
-   Display active/inactive users with real-time statistics.

-   The users table provides a comprehensive view of all registered users, including their roles and management options.

    ![User Table Screenshot](screenshots/users.png)

-   The register user form allows administrators to add new users by providing their details and assigning roles.

    ![Add User Modal Screenshot](screenshots/register-user.png)

### **Customer Management**

-   Create, update, and delete customer records.
-   Maintain detailed customer profiles, including contact information and address.
-   Enable or disable customer accounts with status toggles.
-   Real-time updates to customer lists, ensuring up-to-date records.
-   Seamless integration with orders for streamlined management.

-   Displays a comprehensive list of customers, including their details such as name, email, phone, address, and account status.

    ![Customer Table Screenshot](screenshots/customer.png)

-   Provides a user-friendly form to quickly add new customer details, including name, email, phone, and address.

    ![Add Customer Modal Screenshot](screenshots/add-customer.png)

-   Enables seamless editing of existing customer information, allowing updates to their details without leaving the page.

    ![Edit Customer Modal Screenshot](screenshots/edit-customer.png)

### **Material Management**

-   Track and manage material stock levels.
-   Auto-update material quantities when orders are placed.

-   Displays a comprehensive list of all materials, including their names, unit costs, available stock, and measurement units for easy inventory management.

    ![Material Table Screenshot](screenshots/material.png)

-   Allows users to add new materials to the inventory with details such as name, unit cost, available quantity, and unit type.

    ![Edit Material Screenshot](screenshots/add-material.png)

-   Facilitates updates to material details, ensuring inventory information remains accurate and up-to-date.

    ![Edit Customer Screenshot](screenshots/edit-material.png)

### **Order Management**

-   Create, update, and delete orders.
-   Automatically update machine statuses based on order progress.
-   Material stock adjustments tied to order quantities.
-   Real-time updates to order statuses (e.g., Pending, In Progress, Completed, Cancelled).

### **Garment Management**

-   Assign materials and machines to garments.
-   View and manage garment details comprehensively.

### **Machine Management**

-   Dynamic machine status updates based on orders.
-   Assign machines to garments and orders seamlessly.

### **Reporting and Analytics**

-   Generate reports for order statuses, material usage, and machine availability.
-   Visual dashboards for active/inactive users, machines, and order insights.
-   Charts for visualizing trends (e.g., completed vs. canceled orders).

### **Email Notifications**

-   Notify users of critical updates using SMTP email integration (Gmail).

---

## Tech Stack

-   **Framework**: Laravel 10.x
-   **Frontend**: Tailwind CSS
-   **Database**: MySQL
-   **Charting**: Chart.js
-   **Authentication**: Laravel Breeze with role-based access control
-   **Deployment**: Docker-ready configuration

---

## Installation

### Prerequisites

-   PHP >= 8.0
-   Composer
-   Node.js & npm
-   MySQL or any compatible database

### Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/order-management-system.git
    cd order-management-system
    ```
