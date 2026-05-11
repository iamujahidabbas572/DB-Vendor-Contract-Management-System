# Vendor Contract Management System

This is a web-based **Vendor Contract Management System** built with **Node.js, Express, and MySQL**. The project is designed to facilitate the management of contracts, vendors, and purchase orders between departments and external vendors.

## 🚀 Features

- **User Authentication:** Registration and Login for two roles: **Department** and **Vendor**.
- **Department Dashboard:**
  - Create and assign contracts to vendors.
  - Track budget details and remaining amounts.
  - Submit vendor performance ratings.
  - Create and monitor purchase orders.
  - Check for contract renewals (contracts expiring within 30 days).
- **Vendor Dashboard:**
  - View assigned contracts.
  - View and manage purchase orders.
  - Track performance ratings.
- **Notifications system:** Send and receive messages with deadlines.
- **Database Architecture:** Relational schemas with constraints and triggers implemented in MySQL.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Database:** MySQL
- **Other Tools:** Draw.io (for ERD and Relational Schemas)

## 📂 Project Structure

- `server.js` - Main backend server application routing and database connection logic.
- `public/` - Contains all HTML pages and client-side assets.
- `ddlscript.sql` - Database schema definitions (Tables, Relations).
- `Triggers.sql` - SQL triggers for database automation.
- `DB REPORT.docx` - Complete project report.
- `*.drawio` & `*.png` - ER Diagrams and Relational Schemas.

## ⚙️ Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Database Setup:**
   - Install MySQL Server and ensure it is running.
   - Run the scripts in `ddlscript.sql` to create the `VendorContractManagement` database and all required tables.
   - Run the scripts in `Triggers.sql` to set up database triggers.
   - *Note: Update the database connection credentials in `server.js` (Lines 12-17) to match your local MySQL configuration (e.g., `user: 'root'`, `password: 'your_password'`).*

3. **Install Dependencies:**
   Ensure you have Node.js installed, then run:
   ```bash
   npm init -y
   npm install express body-parser mysql2
   ```

4. **Run the Server:**
   ```bash
   node server.js
   ```

5. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000`.

## 👥 Authors
Mujahid Abbas & Talha kayani

