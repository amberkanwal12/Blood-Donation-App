<div align="center">

<img src="screenshots/splash.jpeg" width="300" alt="Blood Donation App Banner"/>

# 🩸 Blood Donation App
### A Full-Featured Cross-Platform Blood Donation Android Application

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)

**Built by [Amber Kanwal](https://linkedin.com/in/amber-kanwal-088b22350) — MAD Subject Project | Contact me for project amberkanwal183@gmai.com**

</div>

---

## 🚀 About The Project

**Blood Donation App** is a full-stack Android application built with **Flutter, Dart, and Firebase** that connects blood donors with receivers in real time. Featuring **three role-based panels** (User/Receiver/Admin), the app provides a complete ecosystem for blood donation management — from submitting urgent requests to tracking donations and managing blood stock inventory.

> 💡 This project was developed as part of the **Mobile Application Development (MAD)** course. It solves a real-world problem — finding the right blood type at the right time can save a life. 🩸

---

## ✨ Features

### 👤 User (Donor) Panel
- 📝 **Registration & Login** — Name, email, password, phone, city, blood group, donor availability toggle
- 🔑 **Firebase Password Reset** — Email-based secure password reset link
- 🩸 **Blood Requests Feed** — Browse all active requests with blood type, hospital, urgency date, and compatible donor types
- ✅ **Donor Response** — Tap **"I CAN DONATE"** or **"NOT AVAILABLE"** — status tracked in real time
- 📍 **Get Directions** — Map-integrated navigation to hospital directly from request details
- 📤 **Share Request** — Share any blood request via WhatsApp, Facebook, Email to spread urgency fast
- 👤 **Profile** — View active requests, edit photo, name, email, blood type
- 📰 **News & Tips** — Blood donation health tips pushed by admin
- ❓ **Who Can Donate?** — Expandable eligibility guide with wait periods and restrictions

### 🩺 Receiver Panel
- 📋 **Submit Blood Request** — Patient name, contact, blood type, medical center, needed-by date, notes
- 📊 **Track Request Status** — Real-time updates: Pending → Accepted → Fulfilled
- 📞 **Contact Donors** — Directly contact donors who responded "I Can Donate"
- 🗺️ **Get Directions & Share** — Navigate to medical center or share request urgency

### 🛡️ Admin Panel (Red Cross Admin)
- 📊 **Live Dashboard** — Total Users, Requests, Donations, Blood Stock, Emergency count, Reports
- 👥 **Manage Users** — View all registered users with assigned roles
- 🩸 **Blood Requests Management** — View and delete all requests with blood type and deadline
- 💉 **Donations Tracker** — Complete donation history with donor city, phone, date, and notes
- 🏦 **Blood Stock Inventory** — Real-time tracking of all 8 blood types (A+, A−, B+, B−, AB+, AB−, O+, O−)
- 📰 **Add News** — Push health news and donation tips to all users
- 📈 **Reports** — Summary analytics: Total Users, Requests, Fulfilled, Donations, Blood Stock

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Dart |
| Framework | Flutter |
| Backend | Firebase Realtime Database |
| Authentication | Firebase Authentication |
| Storage | Firebase Storage |
| Maps | Google Maps API |
| IDE | Android Studio |
| Platform | Android |

---

## 📦 Requirements
```yaml
# pubspec.yaml dependencies
firebase_core: latest
firebase_auth: latest
firebase_database: latest
firebase_storage: latest
google_maps_flutter: latest
image_picker: latest
url_launcher: latest
share_plus: latest
```

---

## ▶️ How to Run
```bash
# Clone the repo
git clone https://github.com/amberkanwal12/Blood-Donation-App.git

# Go into the folder
cd Blood-Donation-App

# Install dependencies
flutter pub get

# Add your google-services.json in android/app/

# Run the app
flutter run
```

---

---

## 📸 Screenshots


<table>
  <tr>
    <td align="center"><b>Splash</b></td>
    <td align="center"><b>Home</b></td>
    <td align="center"><b>Register</b></td>
 
  </tr>
  <tr>
    <td><img src="screenshots/splash.jpeg" width="200"/></td>
    <td><img src="screenshots/h.jpeg" width="200"/></td>
    <td><img src="screenshots/register.jpeg" width="200"/></td>
  </tr>
    <tr>
    <td align="center"><b>Logout</b></td>
    <td align="center"><b>Admin Login</b></td>
    <td align="center"><b>Password Reset</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/logout.jpeg" width="200"/></td>
    <td><img src="screenshots/al.jpeg" width="200"/></td>
    <td><img src="screenshots/reset.jpeg" width="200"/></td>
  </tr>
    <tr>
    <td align="center"><b>Donor</b></td>
    <td align="center"><b>Donor Profile</b></td>
    <td align="center"><b>Donor Detail</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/dd.jpeg" width="200"/></td>
    <td><img src="screenshots/dp.jpeg" width="200"/></td>
    <td><img src="screenshots/dcon.jpeg" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><b>Location</b></td>
    <td align="center"><b>Phone</b></td>
    <td align="center"><b>Share</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/l.jpeg" width="200"/></td>
    <td><img src="screenshots/c.jpeg" width="200"/></td>
    <td><img src="screenshots/share.jpeg" width="200"/></td>
  </tr>
    <tr>
    <td align="center"><b>Reciever</b></td>
    <td align="center"><b>Reciever Profile</b></td>
    <td align="center"><b>Reciver Detail</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/rd.jpeg" width="200"/></td>
    <td><img src="screenshots/dp.jpeg" width="200"/></td>
    <td><img src="screenshots/rcon.jpeg" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><b>Submit Request</b></td>
    <td align="center"><b>News</b></td>
    <td align="center"><b>Edit Profile</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/sbr.jpeg" width="200"/></td>
    <td><img src="screenshots/news.jpeg" width="200"/></td>
    <td><img src="screenshots/ep.jpeg" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><b>Admin Dashboard</b></td>
     <td align="center"><b>Admin Control</b></td>
    <td align="center"><b>Admin Profile</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/ad.jpeg" width="200"/></td>
    <td><img src="screenshots/ac.jpeg" width="200"/></td>
    <td><img src="screenshots/ap.jpeg" width="200"/></td>
  </tr>
  <tr>
    <td align="center"><b>Manage Users</b></td>
    <td align="center"><b>Reports</b></td>
    <td align="center"><b>Who Can Donate?</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/mu.jpeg" width="200"/></td>
    <td><img src="screenshots/report.jpeg" width="200"/></td>
    <td><img src="screenshots/wd.jpeg" width="200"/></td>
  </tr>
    <tr>
    <td align="center"><b>Blood Stock</b></td>
    <td align="center"><b>Donations</b></td>
    <td align="center"><b>Add News</b></td>
  </tr>
  <tr>
    <td><img src="screenshots/bs.jpeg" width="200"/></td>
    <td><img src="screenshots/donations.jpeg" width="200"/></td>
    <td><img src="screenshots/addnews.jpeg" width="200"/></td>
  </tr>
</table>

---

## 🔄 App Flow
```
Open App
    │
    ▼
Login / Register
    │
    ├──── User (Donor)
    │         │
    │    Browse Requests
    │    Respond as Donor
    │    View Profile
    │
    ├──── Receiver
    │         │
    │    Submit Request
    │    Track Status
    │    Contact Donor
    │
    └──── Admin
              │
         Dashboard
    ┌─────────┴──────────┐
 Requests  Donations  Stock
 Users     News       Reports
```

--

## 👩‍💻 Developer

**Amber Kanwal**
BS Software Engineering 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/amber-kanwal-088b22350)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amberkanwal12)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ambar.nebulaxent.com)

---

<div align="center">
⭐ Star this repo if you found it helpful — it could help save a life! 🩸
</div>
