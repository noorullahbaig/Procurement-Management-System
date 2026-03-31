# Procurement Management System

Java desktop procurement management system for handling requisitions, purchase orders, suppliers, inventory, and sales-related workflows. The project appears to be structured as a multi-role academic system with separate dashboards for administrators and operational staff.

## Features

- Purchase requisition and purchase order workflows
- Supplier and inventory management
- Sales tracking and stock monitoring
- Role-based modules for admin, finance, inventory, purchase, and sales users
- Text-file-backed records plus Java form-based desktop UI

## Tech Stack

- Java
- NetBeans form-based desktop UI (`.form`)
- Ant build (`build.xml`)
- File-based records (`*.txt`)

## Project Structure

- `src/main/` - application source, domain classes, and role-specific screens
- `build.xml` - Ant build configuration
- `users.txt`, `items.txt`, `POs.txt`, `PRs.txt`, `SPs.txt`, `sales.txt`, `suppliers.txt` - stored records
- `src/Icon/` - UI assets

## Run

1. Open the project in NetBeans or another Java IDE with Ant support.
2. Build the project using `build.xml`.
3. Run the main desktop application entry configured by the project.
