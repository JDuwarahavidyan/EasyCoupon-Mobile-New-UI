<!-- ---------------------------------------------------------------- -->
<!-- 🌟 PROJECT HEADER -->
<!-- ---------------------------------------------------------------- -->

<h1 align="center">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/firebase/firebase.png" width="60" height="60" alt="Firebase Icon">
  <img src="https://raw.githubusercontent.com/github/explore/main/topics/flutter/flutter.png" width="60" height="60" alt="Flutter Logo">
  <br>
  🎉 <span style="color:#0088cc">Easy Coupon Mobile Application</span> 🎉  
</h1>

<h3 align="center">📱 A Mobile Platform for Welfare Food Coupon Reimbursement</h3>

<p align="center">
  <em>Developed for the Faculty of Engineering, University of Ruhuna</em>  
</p>


<p align="center">
  <img src="https://img.shields.io/badge/Flutter-v3.19+-blue?logo=flutter&logoColor=white">
  <img src="https://img.shields.io/badge/Firebase-Integrated-orange?logo=firebase&logoColor=white">
  <img src="https://img.shields.io/badge/Platform-Android-brightgreen?logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
</p>

---

<!-- ---------------------------------------------------------------- -->
<!-- 🌍 INTRODUCTION -->
<!-- ---------------------------------------------------------------- -->

## 🌟 Introduction  

At the **Faculty of Engineering, University of Ruhuna**, the **Welfare Society** runs a coupon reimbursement program to provide free meals 🍛 to financially unstable students.  

However, the previous **paper coupon system** was inefficient and prone to issues like loss, fraud, and time delays.  
To modernize this, our team developed **Easy Coupon**, a **mobile + web-based platform** that automates welfare food coupon distribution and redemption.

---

## 🔴 The Problem  

Originally, physical coupons were used, leading to:

- 📄 Inefficient distribution & manual tracking  
- ⏳ Long queues and delays at canteens  
- ❌ Risk of fraud, duplication, or lost coupons  
- 📉 Lack of real-time analytics for administrators

---

## 💡 The Solution – Easy Coupon  

**Easy Coupon** revolutionizes the coupon reimbursement system through a secure, efficient, and paperless digital platform.  

### 📱 *Mobile Application (Flutter + BLoC + Firebase) 🔥*  
- ⚙️ Powered by **Flutter + BLoC Architecture** for responsive and scalable UI state management.  
- 📸 Students **scan QR codes** at canteens to redeem meals instantly — no paper, no delay.  
- 🔐 All transactions are **encrypted with AES-256** for military-grade security.  
- 🔑 **Firebase Authentication** ensures safe, role-based access and activity logging.  
- ⚡ **Google Cloud Functions** automatically reset coupons each month — zero manual work.  
- 🔄 **Real-time sync** between student devices and canteen dashboards via Firebase Firestore.  
- 🎨 Clean, modern UI with smooth animations, designed for simplicity and speed.  

### 🖥️ **Admin Web Application – React.js + Node.js + Express.js**
- 🧩 **Student & Canteen Management** – Approve, reject, or update welfare program participants effortlessly.  
- ⚙️ **Full CRUD Operations** – Add, edit, or remove users, coupons, and canteens in real time.  
- 📊 **Dynamic Reports & Analytics** – Generate and download redemption reports for any selected date range.  
- 📈 **Live Dashboard Insights** – View real-time updates on coupon usage and canteen activity.  
- 🔒 **Secure Access Control** – Role-based authentication ensures only authorized administrators can modify data.

<h4 align="center">🌐 Explore the Easy Coupon Web Application</h4>

<p align="center">
  👉 <a href="https://github.com/JDuwarahavidyan/EasyCoupon-Web-Admin.git" target="_blank"><b>Visit the Web Application Repository on GitHub</b></a> 👈
</p>
 

---

### 💡 **Digital Revolution**
Transforming a manual welfare process into a **smart, mobile-first digital ecosystem** with automation and transparency.

---

## 📱 Mobile App Overview

### 🧠 Built With  

| Layer | Technology |
|-------|-------------|
| **Frontend** | Flutter (Dart) |
| **Backend** | Firebase Firestore, Authentication, Storage |
| **Architecture** | BLoC (Business Logic Component) Pattern |
| **Version Control** | Git + GitHub |
| **IDE** | Visual Studio Code |

### 🗂️ Folder Structure

```
📦 easy_coupon_mobile_app/
│
├── 📁 lib/ # Main source directory
│ ├── 📁 bloc/ # State management (BLoC pattern)
│ │ ├── auth/ # Authentication logic (login, signup)
│ │ ├── canteen/ # Canteen state handlers
│ │ ├── home/ # Home page logic
│ │ ├── qr/ # QR scanning, validation & redemption
│ │ ├── report/ # Report generation logic
│ │ ├── user/ # Student data management
│ │ └── update_user_info/ # Profile & user info updates
│ │
│ ├── 📁 exception/ # Custom exception handling
│ │ ├── custom_exception.dart
│ │ └── exceptions.dart
│ │
│ ├── 📁 models/ # Data models (QR, user, etc.)
│ │ ├── qr/
│ │ │ └── qr_model.dart
│ │ ├── user/
│ │ │ └── user_model.dart
│ │ └── models.dart
│ │
│ ├── 📁 pages/ # All app UI pages
│ │ ├── canteen_a_pages/
│ │ ├── landing_pages/
│ │ │ └── components/
│ │ ├── login_pages/
│ │ ├── student_pages/
│ │ │ └── profile/
│ │ └── pages.dart
│ │
│ ├── 📁 repositories/ # Data access & repository logic
│ │ ├── auth/
│ │ ├── qrcode/
│ │ ├── user/
│ │ └── repositories.dart
│ │
│ ├── 📁 routes/ # App routing configurations
│ │ ├── app_routes.dart
│ │ ├── route_names.dart
│ │ └── routes.dart
│ │
│ ├── 📁 services/ # Firebase & core app services
│ │ ├── auth/
│ │ ├── qrcode/
│ │ ├── user/
│ │ └── services.dart
│ │
│ ├── 📁 widgets/ # Shared reusable UI components
│ │ ├── firebase_options.dart
│ │ └── main.dart
│ │
│ └── 📁 assets/ # Images, icons, and local resources
│
├── 📄 pubspec.yaml # Flutter dependencies & assets config
├── 📄 README.md # Project documentation
└── 📄 .gitignore # Git ignore rules
```
---

<!-- ---------------------------------------------------------------- -->
<!-- 🎬 APP PREVIEW SECTION -->
<!-- ---------------------------------------------------------------- -->

## 🎬 App Preview

### 🌀 Splash & Landing Pages  

<p align="center">
  <img src="assets/images/app_ss/Splash%20Screen.png" width="30%" alt="Splash Screen">
  <img src="assets/images/app_ss/1.%20Landing%20Page.png" width="30%" alt="Landing Page 1">
  <img src="assets/images/app_ss/2%20Landing%20Page.png" width="30%" alt="Landing Page 2">
</p>
<p align="center">
  <img src="assets/images/app_ss/3.%20Landing%20Page.png" width="30%" alt="Landing Page 3">
  <img src="assets/images/app_ss/4.Landing%20Page.png" width="30%" alt="Landing Page 4">
  <img src="assets/images/app_ss/5.Landing%20Page.png" width="30%" alt="Landing Page 5">
</p>

---

### 🔐 Login Page

> _When an admin creates a new user account, a **temporary password** and username are automatically sent to the registered email address.  
The user can then log in and securely configure their account credentials via the Easy Coupon mobile application._


<p align="center">
   <br>
  <img src="assets/images/app_ss//6.Login%20Page.png" width="30%" alt="Login Screen" style="margin-right: 20px;">
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/images/app_ss/AccountSetup.png" width="30%" alt="Account Configuration Screen">
</p>

---
### 🔑 Forgot Password Page

> _If a user forgets their password, they can easily initiate a password reset process.  
An email containing a **secure reset link** is sent to their registered address, allowing them to create a new password and regain access to their account._

<p align="center">
  <br>
  <img src="assets/images/app_ss/PW%20Reset%20Page.png" width="30%" alt="Forgot Password Screen">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/images/app_ss/ResetPW.png" width="30%" alt="Reset Password Confirmation Screen">
</p>

---

### 🏠 Home Page – Student & Canteen

> _The Home Page provides an instant overview of the daily and monthly coupon usage for both students and canteen operators._  
>  
> For **students**, the count shown as **“30”** represents the total number of welfare meal coupons available per month.  
Each day, a student can redeem a maximum of **3 coupons**.  
At the end of each month, this value automatically resets back to **30**.  
>  
> For **canteen operators**, the value **“0”** represents the total number of coupons redeemed by students for the current day.  
This count automatically resets to **0** at the start of each new day.  
>  
> These automated resets are managed using **Google Cloud Functions**, ensuring data consistency and zero manual intervention. ⚡

<p align="center">
  <br>
  <img src="assets/images/app_ss/Home%20Page.png" width="30%" alt="Student Home Page">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/images/app_ss/CanteenHomePage.png" width="30%" alt="Canteen Home Page">
</p>

<p align="center">
  <sub>🎓 Student Home Page</sub>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub>🍽️ Canteen Home Page</sub>
</p>

---
### 📷 QR Generator + QR Scanning + Confirmation Page

> _The Easy Coupon system enables fast, secure, and contactless coupon redemption using encrypted QR codes._

> **Canteen operators** can generate unique **QR codes** each day directly from the app.  
These QR codes can be **displayed digitally** or **printed and placed** near the canteen counter for student access.  
>
> Every generated QR code is **encrypted using AES (Advanced Encryption Standard)** 🔐, ensuring that sensitive data inside cannot be read or modified externally.  
These QR codes can **only be scanned via the official Easy Coupon mobile scanner**, guaranteeing security and preventing unauthorized use.  
>
> **Students** can open their app, select how many coupons they want to redeem (up to **3 per day**), and **scan the canteen’s QR code**.  
Once the QR is successfully scanned, a **confirmation screen** appears to verify a successful redemption.  
The student can then **show this confirmation** to the canteen operator to receive their meal.  
>
> This entire process ensures **data integrity, real-time synchronization**, and **end-to-end encryption** between students and canteen operators.

<p align="center">
  <br>
  <img src="assets/images/app_ss/QRCanteen.png" width="30%" alt="QR Generator – Canteen View">

  <img src="assets/images/app_ss/8.Scanning%20Page.png" width="30%" alt="QR Scanning – Student View">
  
  <img src="assets/images/app_ss/9.Confirmation%20Page.png" width="30%" alt="Confirmation Page">
</p>

<p align="center">
  <sub>🏪 QR Generator – Canteen View</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub>🎓 QR Scanning – Student View</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub>✅ Confirmation Page</sub>
</p>

---


### 📊 Report Page

> _The Report Page provides powerful insights into coupon redemptions for both students and canteen operators._

> Users can select a **custom date range** to view coupon redemption history with detailed tracking.  
>  
> - **Students** can view **which canteens** they have redeemed coupons from within the selected date range.  
> - **Canteen operators** can view **which students** redeemed coupons in their canteen, helping manage meal distribution efficiently.  
>  
> The report system supports real-time data updates and promotes **transparency**, **accountability**, and **data-driven decision-making** for the welfare program.

<p align="center">
  <br>
  <img src="assets/images/app_ss/10.Report.png" width="30%" alt="Common Report Page">

  <img src="assets/images/app_ss/11.%20Report.png" width="30%" alt="Student Report Page">
  
  <img src="assets/images/app_ss/CanteenReport.png" width="30%" alt="Canteen Report Page">
</p>

<p align="center">
  <sub>📋 Common Report Interface</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub>🎓 Student Report View</sub>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub>🏪 Canteen Report View</sub>
</p>

---
### ⚙️ Settings & About Page

<p align="center">
  <br>
  <img src="assets/images/app_ss/12.Settings.png" width="30%" alt="Settings Page">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/images/app_ss/About%20Us%20Page.png" width="30%" alt="About Page">
</p>

<p align="center">
  <sub>⚙️ Settings Page</sub>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <sub>ℹ️ About Page</sub>
</p>

---
## 🎬 Live Action with Easy Coupon



---

<h4 align="center">✨ “From Tap to Meal — Seamless, Secure, and Smart.” ✨</h4>


