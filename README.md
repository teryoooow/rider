# 🍔 RockyGo Customer App - Automated Test Scripts

This repository contains automated UI test scripts for the **Food Delivery App**, created using [Maestro](https://maestro.mobile.dev). These tests help validate key user flows and ensure the reliability of the mobile application.

## ✅ Test Coverage
🔐 Authentication Flow
Login and logout functionality

Registration with validation for required fields

Error handling for invalid credentials

📦 Order Management
View assigned orders and order details

Accept, reject, or update delivery status

Real-time status updates and transitions (e.g., Picked Up, Delivered)

🗺️ Navigation and Delivery Flow
Access to delivery route/map view

Start and end delivery with location tracking

Handle delivery delays or address issues

🔔 Notifications & Alerts
Receive push/in-app notifications for new orders or changes

Display alerts for failed actions (e.g., location off, network issues)

⚠️ Error Handling & Edge Cases
Invalid order actions (e.g., accepting completed orders)

Offline scenarios and recovery behavior

Form validation and unexpected input cases

## 🛠️ Tools & Frameworks

- [Maestro](https://maestro.mobile.dev) – Mobile UI testing framework
- Android Emulator / iOS Simulator

## 📦 Installation

```bash
# Install Maestro CLI via Homebrew
brew install maestro

# Or via curl
curl -Ls "https://get.maestro.mobile.dev" | bash
