# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion

## 📌 Project Overview
HandsMen Threads is a premium fashion platform designed to streamline bespoke tailoring services and enhance customer experience through personalized styling and seamless order management.

This Salesforce implementation focuses on building a scalable data model, maintaining data integrity, and automating key business processes.

---

## 🗂 Data Modeling

Custom Objects:
- Orders
- Tailoring Requests
- Loyalty Program
- Inventory

Relationships:
- Master-Detail between Customer and Orders
- Lookup between Orders and Inventory

---

## ✅ Data Quality Implementation

- Validation Rules to prevent incorrect entries
- Required Fields for essential information
- Duplicate Rules for customer records
- Field-level security for controlled access

---

## ⚡ Automation Implemented

### 1️⃣ Automated Order Confirmations
- Record-Triggered Flow sends email after order confirmation.

### 2️⃣ Dynamic Loyalty Program
- Loyalty status auto-updates based on purchase history.

### 3️⃣ Proactive Stock Alerts
- Email notification to warehouse team when stock < 5 units.

### 4️⃣ Scheduled Bulk Order Processing
- Batch Apex runs daily at midnight.
- Updates financial records.
- Adjusts inventory automatically.

---

## 🛠 Tools & Technologies Used

- Lightning App Builder
- Record-Triggered Flows
- Apex Triggers
- Batch Apex (Asynchronous Apex)
- Validation Rules

---

## 🎯 Outcome

- Improved operational efficiency
- Enhanced customer engagement
- Real-time inventory management
- Scalable and maintainable Salesforce architecture
