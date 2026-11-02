# 🏥 PulseCare - Hospital Patient Management System

PulseCare is a full-featured, single-file web application for managing hospital records, patient registrations, doctor schedules, medical diagnoses, billing invoices, and inpatient bed allocations. 

Designed to operate seamlessly on top of a relational Database Management System (DBMS) schema, this dashboard provides real-time state management, interactive modal dialogs, and instant search/filtering across all modules.

---

## 🚀 Features & Modules

- **📊 Dashboard Overview:** Quick metric cards tracking total patients, active doctors, daily pending appointments, and available hospital beds.
- **👥 Patients Directory:** Full patient registry supporting registration, real-time search (by name, ID, or phone), detailed profile view, and deletion with cascading bed release.
- **🩺 Doctors & Staff Roster:** Departmental directory with search and filtering by department (Cardiology, Neurology, Orthopedics, General Surgery).
- **📅 Appointments Scheduling:** Complete scheduling pipeline with instant status updates (Schedule, Complete, Cancel).
- **📋 Medical Records & Prescriptions:** Detailed clinical diagnostic logs paired with prescribed medications, dosages, and treatment durations.
- **💳 Billing & Invoicing:** Automated itemized invoice creation (room, consultation, and lab charges) with insurance coverage calculations and payment status tracking.
- **🛏️ Room & Bed Allocation Matrix:** Interactive bed grid supporting dynamic room allocation for outpatients, bed state management (Available, Occupied, Maintenance), and patient discharge workflows.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic architecture for application layout.
- **CSS3 / Tailwind CSS (CDN):** Modern utility-first dark-mode design system with responsive layouts.
- **JavaScript (ES6+):** Pure client-side state engine handling dynamic rendering, search filters, and modal interactions.
- **FontAwesome & Google Fonts (Inter):** Clean UI icons and typography.

---

## 📂 Project Structure

```text
├── index.html        # Single-file standalone web application (HTML + CSS + JS)
└── README.md         # Documentation file
```

---

## ⚡ Quick Start

1. **Clone or Download:** Clone the repository or download `index.html`.
2. **Open in Browser:** Simply double-click `index.html` or open it with any modern Web Browser (Chrome, Firefox, Edge, Safari). No server or build tools (`npm`/`node`) required!

---

## 💾 Data Persistence Note

This application runs as a frontend interface with an in-memory JavaScript data store. 
- Actions like registering patients, booking appointments, or deleting records will update the UI immediately during the active browser session.
- Refreshing the page resets the state to initial default data. For persistent data storage across sessions, connect a backend API (e.g., Node.js/Express) with a MySQL or PostgreSQL database.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).