# Procurement Management System

## Overview

Procurement Management System is a Java desktop application for handling requisitions, purchase orders, supplier records, stock views, payments, and sales activity. The codebase is organized around separate role-based screens for administrators, finance managers, inventory managers, purchase managers, and sales managers.

## Features

- Login-driven desktop workflow starting from `Assignment.java`
- Purchase requisition and purchase order management
- Supplier and item maintenance
- Stock viewing and payment tracking
- Sales entry, sales history, and dashboard-style reporting screens
- Text-file-backed records for users, suppliers, items, orders, and sales

## Tech Stack

- Java
- Swing / NetBeans form files (`.java` and `.form`)
- Ant build (`build.xml`)
- Flat-file persistence

## Project Structure

- `src/main/Assignment.java` - application entry point and initial login launch
- `src/main/Login.java` - login screen
- `src/main/Admin_*` - administrator screens
- `src/main/FM_*` - finance manager screens
- `src/main/IM_*` - inventory manager screens
- `src/main/PM_*` - purchase manager screens
- `src/main/SM_*` - sales manager screens
- `src/main/User.java`, `Item.java`, `Supplier.java`, `PO.java`, `PR.java`, `Sales.java` - core data classes
- `users.txt`, `items.txt`, `POs.txt`, `PRs.txt`, `sales.txt`, `suppliers.txt`, `SPs.txt` - persisted records

## How to Run

1. Open the project in NetBeans or another Java IDE with Ant support.
2. Build the project using `build.xml`.
3. Run `src/main/Assignment.java`, which opens the login window and applies the Nimbus look and feel when available.
