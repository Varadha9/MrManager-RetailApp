# 🧾 MrManager - Retail Inventory Management App

MrManager is a modern and user-friendly Android application designed for small retailers to manage inventory, track sales, and get smart alerts. Built using **Java** and **Room Database** in **Android Studio**, this app aims to simplify retail management with a clean UI and powerful features.

## 📱 Features

- 🔐 **User Authentication**
  - Email/Password Sign-up and Login
  - Google Sign-In (coming soon)
  
- 📊 **Dashboard**
  - Total Inventory Overview
  - Today’s Sales
  - Low Stock Alerts
  - Best-Selling Products

- 📦 **Product Management**
  - Add/Edit/Delete Products
  - Barcode Scanning Support
  - Stock Level and Expiry Alerts

- 📈 **Sales & Reports**
  - Visual Charts: Sales, Profit/Loss
  - Export to PDF/Excel (coming soon)

- 🔔 **Smart Notifications**
  - Low Stock, Expiry Alerts
  - Supplier Follow-ups

- ⚙️ **Settings**
  - Multi-store Support
  - Light/Dark Theme
  - Role-Based Access Control

## 🖼️ Screenshots

| Dashboard | Product List | Add Item | Dark Mode |
|----------|--------------|----------|-----------|
| (Add your app screenshots here) |

## 🛠️ Tech Stack

- **Language:** Java
- **Database:** Room (SQLite ORM)
- **UI:** Material Design Components, Custom Bottom Navigation
- **Tools:** Android Studio, Git, XML Layouts

## 📁 Project Structure

com.example.v2
│
├── activities/
│ ├── LoginActivity.java
│ ├── DashboardActivity.java
│ └── InventoryActivity.java
│
├── database/
│ ├── InventoryDatabase.java
│ ├── InventoryDao.java
│ └── InventoryItem.java
│
├── adapters/
│ └── InventoryAdapter.java
│
└── utils/
└── Constants.java

bash
Copy
Edit

## 🔧 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MrManager.git
Open the project in Android Studio.

Sync Gradle and build the project.

Run the app on an emulator or physical device.

Note: Barcode scanning and Google Sign-In may require API keys or permissions.

🧑‍💻 Developed By
Varad Vikas Mandhare
📧 varadmandhare924@gmail.com
🔗 LinkedIn

📄 License
This project is licensed under the MIT License.
