# 🧹 GoClean – Home Service Booking App (Flutter)

A multi-role mobile application that connects customers with professional cleaning staff, supporting booking, real-time chat, and QR-based payment.

---

## 🚀 Features

### 👤 Customer
- Browse cleaning services (home cleaning, sofa cleaning, deep cleaning)
- Multi-step booking form (service, date/time, address)
- Dynamic pricing with discount codes
- QR-based payment with status tracking
- Real-time chat with staff (text & image)
- Booking history with status (pending / paid / completed)
- Reviews and ratings

### 👷 Staff
- View assigned bookings
- Access customer details
- Chat with customers
- Manage profile

### 🛠 Admin
- Manage bookings and assign staff
- Manage users (enable/disable accounts)
- Manage staff and service areas
- Real-time system monitoring

---

## ⚡ Advanced Features

- Auto staff assignment based on location
- Real-time data synchronization (Firestore Streams)
- Multi-role access control
- Image upload & compression
- Chat system with media support

---

## 🛠 Tech Stack

- **Flutter, Dart**
- **Firebase (Authentication, Cloud Firestore, Storage, Cloud Messaging - FCM)**
- **State Management:** Provider
- **Architecture:** Repository Pattern
- **Networking:** RESTful API (HTTP, JSON)
- **Real-time System:** Firestore Streams
- **Image Handling:** Firebase Storage
- **Local Storage:** SharedPreferences
- **Tools:** Git, Postman, Android Studio, VS Code

---

## ⚙️ Installation

```bash
git clone https://github.com/bikey0511/GoClean-app.git
cd GoClean-app
flutter pub get
flutter run
