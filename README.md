# Automated Inventory and Point-of-Sale System

An all-in-one mobile application designed for bars and restaurants, combining Point-of-Sale (POS), inventory management, sales tracking, employee management, FOH/BOH communication, and inventory forecasting.

**Project Status:** Work in Progress

## Project Overview

The goal of this project is to develop a mobile application for the service industry, with a primary focus on bars and restaurants.

The application aims to combine multiple business operations into one platform that can be installed on smartphones and tablets.

Instead of relying on multiple applications and devices, employees will be able to manage orders, inventory, sales, and communication through a single system.

## Main Features

### 1. Point-of-Sale (POS)
- Employee login and authentication.
- Create customer orders.
- Select and modify menu items.
- Apply discounts and adjustments.
- Send orders to the kitchen or bar.
- Process customer payments.
- Generate receipts.
- Record completed sales.
- Process refunds and voids based on permissions.

### 2. Inventory Management
- Track current inventory levels.
- Automatically deduct inventory when sales are completed.
- Perform inventory counts.
- Track damaged and wasted products.
- Identify low-stock items.
- Record received inventory.
- Establish minimum inventory levels.

### 3. Sales Forecasting
- Analyze historical sales data.
- Identify sales trends and patterns.
- Recommend appropriate inventory levels.
- Use statistical forecasting methods initially.
- Explore machine-learning techniques in future versions.

For example, if historical data shows increased beer sales during hot summer evenings, the system could recommend stocking additional beer before the shift begins.

### 4. FOH/BOH Communication

Improve communication between Front-of-House (FOH) and Back-of-House (BOH) employees.

Planned order workflow:

`Server → Order → Kitchen/Bar → Preparing → Ready → Server`

This workflow will help employees track order progress and reduce unnecessary communication delays.

### 5. Employee Management

Role-based access control will provide different permissions depending on employee responsibilities.

Planned employee roles:
- Server
- Bartender
- Kitchen Employee
- Manager
- Administrator

### 6. Security

Security will be a major consideration throughout development.

Planned security features:
- Secure authentication.
- Password hashing.
- Role-based permissions.
- Encrypted communications.
- Secure API authentication.
- Audit logs.
- Secure data storage.
- Minimal collection of personally identifiable information (PII).
- Data retention policies.
- Secure deletion procedures.
- Secure backups.

Payment processing will use an appropriate payment processor and tokenization or payment references where applicable. The system will avoid storing unnecessary raw credit card information.

Applicable PCI DSS requirements will be investigated before implementing real payment processing.

## Technology Stack

The proposed technologies and resources include:

| Component | Technology |
|---|---|
| Mobile Framework | React Native |
| Backend | API Framework (TBD) |
| Database | Database for sales and inventory records |
| Hosting | Cloud Hosting |
| UI/UX | Design Software |
| Analytics | Analytics and Logging System |
| Authentication | Authentication Method (TBD) |

## Hardware Requirements

- Development computer.
- Wi-Fi connection.
- POS terminal or card reader.
- Smartphones and tablets.
- Optional kitchen printer.
- Optional cash drawer.

## Project Milestones

- [ ] M1: Project Definition
- [ ] M2: Installable Application Prototype
- [ ] M3: Database & Backend
- [ ] M4: Point-of-Sale System
- [ ] M5: Inventory Automation
- [ ] M6: Sales Prediction / Inventory Recommendations
- [ ] M7: FOH/BOH Communication
- [ ] M8: Payment & Security
- [ ] M9: Testing

## Project Schedule

**Project Period:** September 16, 2026 – December 13, 2026

Planned development activities:

1. Requirements and Research
2. Project Planning
3. UI/UX Design
4. System Architecture
5. Database Design
6. Backend/API Development
7. Authentication and User Roles
8. POS Development
9. FOH/BO
