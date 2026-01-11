## 📌 Project Overview
Many pharmacies currently rely on manual processes for prescriptions and inventory, leading to inefficiencies and higher risks of medication errors. This project provides a structured digital solution to automate these workflows using a three-layer architecture (View, Controller, and Domain layers).

## Key Features
* **Prescription Management:** Secure online upload for customers and a digital review/approval interface for pharmacists.
* **Real-time Inventory Control:** Automated monitoring of stock levels with low-stock alerts and integrated supplier notification.
* **Order & Payment Integration:** Supports multi-channel order placement and secure payment gateway transactions.
* **Customer History Tracking:** Maintains detailed profiles and medicine usage history to support long-term treatment plans.

## System Architecture
The system is built on a **Three-Layer Design** to ensure scalability and maintainability:
* **View Layer:** Handles user interactions for Customers, Pharmacists, and Doctors.
* **Controller Layer:** Manages core business logic and workflow coordination (e.g., `PrescriptionHandler`, `InventoryManager`).
* **Domain Layer:** Manages data storage, automated notifications, and database interactions.

## Technical Artifacts
The project includes comprehensive documentation of the system design:
* **Use Case Diagrams:** Mapping interactions between Primary Actors (Customers, Pharmacists) and the system.
* **Sequence Diagrams:** Visualizing the step-by-step logic for "Upload Prescription" and "Preparing Medication".
* **CRC Cards:** Defining class responsibilities and collaborations.
* **Data Models:** Detailed Domain Model Class Diagrams and ER Diagrams.

## Risk & Compliance
* **Scalability:** Mitigation strategies for performance bottlenecks and infrastructure capacity.
* **Data Integrity:** Implementation of ACID principles and automated error-checking to protect sensitive health records.
* **Cultural Sensitivity:** Design informed by **Te Ao Māori** principles (*whanaungatanga*, *manaakitanga*, and *kaitiakitanga*) to ensure inclusive health data guardianship.

## Contributors (Group 5)
* **Jiajia Li (Claire Li):** System Vision, Event Decomposition, CRC Modeling.
* **Umanga Joshi:** Use Case Diagrams, Activity Diagrams, Risk Analysis.
* **Abirami:** Detailed Use Case Descriptions, System Sequence Diagrams.
* **Bryan Emmanuel Ferdinandus:** Domain Model Class Diagram, ER Diagram, Design Class Diagrams.
