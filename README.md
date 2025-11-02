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

<h3 align="center">💚 “A Smarter, Greener, and Fairer Way to Serve Every Student.” 💚</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Automation-Enabled-blue?style=for-the-badge&logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Environment-Friendly-success?style=for-the-badge&logo=leaflet&logoColor=white">
  <img src="https://img.shields.io/badge/Security-AES%20256%20Encryption-critical?style=for-the-badge&logo=lock&logoColor=white">
  <img src="https://img.shields.io/badge/Cloud%20Integration-Google%20Cloud-orange?style=for-the-badge&logo=googlecloud&logoColor=white">
</p>

---

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

> _A real-world demonstration of how Easy Coupon brings automation, convenience, and transparency to the Faculty canteen._

---

### 🏪 **Step 1 – QR Code at the Canteen**
The **canteen operator** places a printed or digital **AES-encrypted QR code** near the counter. Students simply walk up and scan this QR using the Easy Coupon app — no paper coupons needed!

<p align="center">
  <img src="assets/images/EasyCouponLiveAction/1.%20QR%20code%20at%20the%20canteen.jpg" width="70%" alt="QR code displayed at canteen">
</p>

---

### 📲 **Step 2 – Scanning the QR Code**
Students open the app, choose how many coupons to redeem *(up to 3 per day)*, and scan the QR code to initiate the redemption securely.

<p align="center">
  <img src="assets/images/EasyCouponLiveAction/2.%20Scanning%20the%20QR%20code.jpg" width="70%" alt="Student scanning QR code">
</p>

---

### ✅ **Step 3 – Instant Confirmation**
The system instantly validates the scan and shows a **confirmation screen**. The redeemed amount is auto-deducted from the student’s monthly quota and reflected in the canteen dashboard in real time.

<p align="center">
  <img src="assets/images/EasyCouponLiveAction/3.%20Getting%20the%20confirmation.jpg" width="70%" alt="Redemption confirmation on app">
</p>

---

### 👩‍🍳 **Step 4 – Show Confirmation to the Canteen Operator**
The student presents the confirmation screen to the operator, verifying that the meal redemption is complete and recorded.

<p align="center">
  <img src="assets/images/EasyCouponLiveAction/4.%20Showing%20the%20confirmation%20to%20canteen%20operator.jpg" width="70%" alt="Showing confirmation to canteen operator">
</p>

---

### 🍱 **Step 5 – Receiving the Meal**
After verification, the canteen operator serves the meal 🍛 — completing a **secure, paper-free, end-to-end digital transaction** powered by Easy Coupon.

<p align="center">
  <img src="assets/images/EasyCouponLiveAction/5.%20Receiving%20the%20meal.jpg" width="70%" alt="Receiving the meal after confirmation">
</p>

---

---

## 🌟 The Impact of Easy Coupon

> _Transforming a simple idea into a digital revolution at the Faculty of Engineering, University of Ruhuna._

---

### 🎯 **Key Achievements**

| 🌱 | **Outcome** |
|:--:|:-------------|
| ⚙️ | **Reduced Manual Workload** – Automated the entire coupon reimbursement workflow, reducing manual effort for students and canteen operators by **over 90%**. |
| 🧾 | **Paperless Transformation** – Eliminated the need for printed coupons, saving **hundreds of sheets per month** and contributing to a greener campus 🌿. |
| 📊 | **Real-time Transparency** – Enabled the Welfare Society to **monitor coupon usage and canteen activity live**, with monthly report generation. |
| 🔐 | **Secure & Reliable** – Leveraged **AES-256 encryption**, Firebase authentication, and Google Cloud Functions for complete system security and automation. |
| 🚀 | **Scalable Foundation** – Built a framework that can be **replicated across universities** to modernize welfare food distribution systems nationwide. |

---

## 💬 Words of Appreciation

This project was completed under the supervision and guidance of **[Dr. Kushan Sudheera](https://www.eng.ruh.ac.lk/deie/team/kushan-sudheera/)**,  
_Senior Lecturer, Department of Electrical and Information Engineering,_  
_Faculty of Engineering, University of Ruhuna._

A special thanks to the **Welfare Society of the Faculty of Engineering** for their support, testing, and real-world feedback during deployment.

Gratitude also goes to all **canteen operators and students** who participated in pilot testing and helped us refine the system into a practical success. 🙏

---


## 👨‍💻 Project Contributors  

> _A passionate and dedicated team behind the Easy Coupon System_ 💚  


| 👨‍🎓 **Contributor** | 💼 **Role** | 🌐 **GitHub Profile** |
|:---------------------|:-------------------------------------|:----------------------------------------------------|
| **Duwarahavidyan Jeganathan** | 🧭 Project Manager & Fullstack Developer | [@JDuwarahavidyan](https://github.com/JDuwarahavidyan) |
| **Sachinthana Fernando** | 💻 Fullstack Developer | [@sfernando00](https://github.com/sfernando00) |
| **Deshan Dissanayake** | 🧩 Fullstack Developer | [@DeshanTD](https://github.com/DeshanTD) |
| **Tharuka Harshajith** | 🧠 Fullstack Developer | [@TharukaHarshajith](https://github.com/TharukaHarshajith) |


---

## 🔗 Explore More

### 🖥️ **Easy Coupon Web Application**
🌐 Explore the Admin Web Portal — built using **React.js**, **Node.js**, and **Express.js**  
👉 [View on GitHub](https://github.com/JDuwarahavidyan/EasyCoupon-Web-Admin)



### 🎬 **Easy Coupon Mobile App Demo**
📱 A hands-on walkthrough of the Flutter + Firebase powered mobile application.  
👉 [Watch the Full Demo](https://drive.google.com/file/d/15aHMUjwTxR9I2h3rzv2fBgldVgAmwlbH/view?usp=sharing)



### 🎥 **Coupon Redemption Live Demo**
🍽️ See the complete coupon redemption flow — from QR generation to meal confirmation.  
👉 [View Redemption Demo](https://drive.google.com/file/d/1-z_r3Jxu-lJzZORPqzC_APLQIEcK_52C/view?usp=sharing)



### 💼 **Full Project Story on LinkedIn**
🧠 Learn how our team built, tested, and deployed Easy Coupon for the Faculty of Engineering.  
👉 [Read the Full Post on LinkedIn](https://www.linkedin.com/posts/duwarahavidyan-jeganathan-763b6a192_flutter-firebase-reactjs-activity-7369382950934597679-Cmbt?utm_source=share&utm_medium=member_desktop&rcm=ACoAAC1g0bsBkCY5HOF6iQ3bbHqumfI0SOo0-Dk)



### 🏆 **Appreciation Post**
🙏 See how our project was recognized and appreciated by faculty members and the Welfare Society.  
👉 [View Appreciation Post](https://www.linkedin.com/posts/your-appreciation-post-link/)
  

---

<h4 align="center">🌟 Smart • Secure • Sustainable – The Easy Coupon Experience in Real Life 🌟</h4>


<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-Flutter%20%7C%20Firebase-blue?logo=flutter&logoColor=white">
  &nbsp;
  <img src="https://img.shields.io/badge/Database-Firestore-orange?logo=firebase&logoColor=white">
</p>

