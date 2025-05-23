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
## Demonstration:

![Screenshot 2025-05-23 161342](https://github.com/user-attachments/assets/552b7b19-458d-4758-a973-677d8542ec26)


![Screenshot 2025-05-23 161541](https://github.com/user-attachments/assets/f017e190-2d9b-48cf-bb4d-e2779647cdd5)
![Screenshot 2025-05-23 161600](https://github.com/user-attachments/assets/9c07e85f-07a3-43e0-87f3-400a9ceeee3d)
![Screenshot 2025-05-23 161904](https://github.com/user-attachments/assets/fb03c54b-df42-43f6-b064-42dc443b9db6)
![Screenshot 2025-05-23 161914](https://github.com/user-attachments/assets/85b8813a-54ba-43a8-b01f-fb672c30e18e)
![Screenshot 2025-05-23 161932](https://github.com/user-attachments/assets/662215a8-0ea2-4c88-9f7d-a37415050052)
![Screenshot 2025-05-23 161945](https://github.com/user-attachments/assets/777ff016-5414-4956-8d55-f65985d7ab65)

![Screenshot 2025-05-23 162026](https://github.com/user-attachments/assets/ab5af08e-9051-4815-a1ac-5e130f5a897c)
![Screenshot 2025-05-23 162007](https://github.com/user-attachments/assets/b4c42c14-731b-4968-9434-b6f64c2109f4)
![Screenshot 2025-05-23 162038](https://github.com/user-attachments/assets/26beb8ae-7f33-4391-a298-1c631774c7df)
![Screenshot 2025-05-23 162047](https://github.com/user-attachments/assets/3e5757b0-c95b-4099-a7d4-3af9c5265d08)
![Screenshot 2025-05-23 162110](https://github.com/user-attachments/assets/186917e6-4353-486b-a99e-3664a30d11e7)
![Screenshot 2025-05-23 162127](https://github.com/user-attachments/assets/61c45956-f4d0-455f-84c9-44a825ed6a18)

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
## 🔗 Live Demo

Try it out here: [Billing System Live](https://qr-billing-system.web.app/)

---
## 🚀 Deployment

The project is deployed on **Firebase Hosting**. To run locally:

```bash
git clone <repo-url>
cd qr-billing-system
npm install
npm start
