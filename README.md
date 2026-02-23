# HandsMen Threads: Elevating the Art of Sophistication in Men's Fashion

## 📌 Project Overview

HandsMen Threads is a premium fashion platform designed to streamline bespoke tailoring services and enhance customer experience through personalized styling and seamless order management.

This Salesforce implementation focuses on scalable data modeling, automation, and data integrity to support efficient business operations.

---

## 🎯 Business Objectives

- Maintain high data accuracy and consistency.
- Automate order confirmations and stock alerts.
- Implement a dynamic loyalty program.
- Enable scheduled bulk order processing.
- Improve operational efficiency and customer engagement.

---

## 🗂 Data Model

### Core Objects:
- Customer
- Order
- Tailoring Request
- Inventory
- Loyalty Program

### Relationships:
- One Customer can have multiple Orders.
- Each Order is linked to Inventory.
- Tailoring Requests are associated with Orders.
- Loyalty status is maintained per Customer.

---

## ⚡ Automation Strategy

### 1️⃣ Automated Order Confirmation
- Record-Triggered Flow sends email after order confirmation.

### 2️⃣ Dynamic Loyalty Update
- Loyalty Status auto-updated based on purchase history.

### 3️⃣ Proactive Stock Alerts
- Email alert triggered when inventory drops below 5 units.

### 4️⃣ Scheduled Bulk Order Processing
- Batch Apex scheduled at midnight.
- Updates financial records.
- Adjusts inventory automatically.

---

## 🛠 Tools & Technologies Used

- Lightning App Builder
- Record-Triggered Flows
- Apex Triggers
- Batch Apex (Asynchronous Processing)
- Validation Rules
- Sharing Rules & Security Model

---

## 🏗 Project Phases

### Phase 1: Architecture & Planning
- Defined object model and ERD.
- Designed validation rules and automation.
- Planned batch processing and email templates.

### Phase 2: Development
- Created custom objects and fields.
- Implemented flows and Apex logic.
- Configured security and sharing rules.

### Phase 3: Testing & QA
- Unit testing of automation.
- End-to-end testing with sample data.
- Security and performance validation.

### Phase 4: Deployment & Training
- Production deployment.
- User training sessions.
- Post-go-live monitoring.

---

## 📦 Deliverables

- Solution Design Document (SDD)
- Object Model Documentation
- ER Diagram
- Automation Architecture

---

## 📊 ER Diagram

(ER1.png)
