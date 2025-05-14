# 🧾 QR-Based Billing System with Inventory Management

A React + Firebase powered **QR-based Billing System** designed to streamline billing and inventory for small-scale retail setups. This project includes both **user-side** and **admin-side** features, including real-time QR scanning, bill generation, inventory management, and low stock alerts.

---

## 🔍 Project Overview

### 👤 **User Side Features**
- 📷 QR Scanner to scan product QR codes
- 🛒 Auto-add scanned products to cart with quantity control
- 💰 Real-time bill calculation based on inventory data
- 📄 Download bill as PDF
- 💡 Simple, responsive UI for mobile and desktop users

### 🛠️ **Admin Side Features**
- 📷 QR Scanner with admin access
- 🧾 Inventory management for:
  - **GoVigyan Products**
  - **Medicinal Products**
- ➕ Add / Edit / Delete products with fields:
  - Product Name, Weight, Price, Stock, QR Code
- ⚠️ Low Stock Alert system (custom threshold)
- 🏬 Business Information Management:
  - GSTIN, Business Name, Address, etc.
- 👤 Add Admins for access control
- 📤 Upload & store dynamic UPI QR for payments

---
## 🎓 College Project

This project was developed as part of a college-level project under the B.Tech CSE (AI & ML) curriculum.This project was undertaken as part of a community engagement effort, using the power of technology to give back to society — blending innovation with tradition to make a meaningful impact.
It combines real-time QR-based interaction, Firebase database operations, and responsive design practices.

---

## 🌿 About Go Vigyan Anusandhan Kendra (GVAK)

> **Go Vigyan Anusandhan Kendra (GVAK)** is a Non-Government Organization on a mission to rekindle the age-old bond between humans and cows. Rooted in the rich heritage of Indian agriculture and traditional wisdom, our organization is dedicated to researching and promoting the multifaceted benefits of cows and their five essential products: **milk, curds, ghee, urine, and dung** – collectively known as **Panchgavya**.

This system supports **GoVigyan products** to help promote traditional Indian agricultural practices through modern technology.

---

## 🔧 Tech Stack

- **Frontend:** React.js, HTML, CSS
- **Backend:** Firebase (Firestore, Authentication, Hosting, Storage)
- **QR Scanner:** `react-qr-reader` / similar library
- **PDF Generation:** `jsPDF` / custom logic
- **State Management:** React useState / useEffect

---

## 🚀 Deployment

The project is deployed on **Firebase Hosting**. To run locally:

```bash
git clone <repo-url>
cd qr-billing-system
npm install
npm start
