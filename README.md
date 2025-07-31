# 🏘️ Housing Community Management System

This project is a **web-based housing management system** designed to efficiently manage residential community data. It tracks house occupancy, rent payments, and available flats, offering organized interfaces for **admins, occupants, and clients**.

---

## 🔧 Tech Stack

### 🖥️ Frontend
- **HTML5**, **CSS3**, **JavaScript (Vanilla)**  
- **Jinja2 Templates** for dynamic HTML rendering

### 🧠 Backend
- **Python 3**
- **Flask** – Lightweight web framework

### 📦 Design Patterns Used
- **Module Pattern**: Isolates reusable logic (rendering, filtering, event handling)
- **Observer Pattern**: Tracks and reflects changes in rent status or occupancy dynamically
- **Factory Pattern**: Creates occupant objects with varying payment strategies based on flat type (1BHK, 2BHK, 3BHK)

### ⚙️ DSA Concepts Applied
- **2D Arrays**: Representing block-flat grid structures
- **HashMaps (Python dicts)**: Quick tenant/flat lookup and validation
- **Search Algorithms**: Efficiently locate flats, tenants, or statuses
- **Sorting**: List flats based on rent, availability, or other filters

---

## 🎯 Key Features

- **🏠 Occupancy Management**: Track flats by block, BHK type, and occupancy status  
- **💰 Rent Tracking**: View total dues, payment status, and collection history  
- **📊 Dynamic Grid View**: Visual layout of blocks with live data binding  
- **👤 Role-based Views**: Separate dashboards for Admin, Client, and Occupant  
- **📇 Tenant Details**: Store name, contact, ID, payment records  
- **🧾 Payment History**: View or make payments as an occupant

---

## 🚀 Potential Enhancements

- **🔐 Role-based authentication** (login restrictions per user type)
- **🗃️ Database integration** (e.g., **MongoDB**, **MySQL** for persistence)
- **🔔 Notifications** for due rent alerts
- **📄 PDF/Excel report generation** for admin records

---

## 📁 Project Structure

