# 🧠 Expertz – Service Marketplace for Skilled Professionals

**Expertz** is a **Swift-based iOS application** connecting skilled professionals with clients. The platform provides a seamless, location-driven experience to discover, chat with, and securely pay verified experts across a range of services.

Built with **Apple MapKit**, **Google Firebase**, and **Core Location**, Expertz features a verified review system (restricted to paying clients only), unbiased search results, and an **AliExpress-style escrow** payment system. The app is currently in development with a working version and ongoing improvements.

> 🔍 **This project is posted for a demonstration of my coding ability, unauthorized reproduction, alteration is strictly prohibited.**

---

## 🚀 Project Highlights

* 🔒 **Verified Reviews** – Only paying clients can leave reviews, improving trust and authenticity
* 📍 **Location-Based Search** – Map-driven request system using Apple MapKit + Core Location
* 💬 **Real-Time Chat** – In-app direct messaging built with Firebase Firestore
* 💼 **Dual User Roles** – Supports both **clients** and **expertz** with distinct flows
* 💳 **Escrow Payments** – (Planned) Funds held until job completion for secure transactions
* 🧾 **Background Check System** – (Planned) Expert verification for trust and safety
* ☁️ **Scalable Firebase Storage** – Manages real-time data and large file uploads efficiently
* 🔍 **Unbiased Results** – No ads or promoted listings—everyone competes on merit

---

## 🔧 Technologies Used

| Layer        | Stack                                                   |
| ------------ | ------------------------------------------------------- |
| **Frontend** | Swift, SwiftUI, UIKit                                   |
| **Location** | Core Location, MapKit                                   |
| **Backend**  | Firebase Authentication, Firestore, Firebase Storage    |
| **Other**    | Cloud Functions (planned), Push Notifications (planned) |

---

## 📱 Core Features

| Feature                   | Description                                                               |
| ------------------------- | ------------------------------------------------------------------------- |
| 🧑‍💼 **Expert Profiles** | Verified professionals showcase skills and reviews                        |
| 👥 **Client Requests**    | Clients can post service requests on a live map                           |
| 💬 **Messaging**          | Built-in chat system with real-time updates using Firestore               |
| ⭐ **Review System**       | Only clients who have paid can leave a review                             |
| 📍 **Map-Based UI**       | Location-driven search and posting interface using Core Location + MapKit |
| 🔐 **Authentication**     | Firebase-powered sign-up and login system                                 |

---

## 📂 Requirements

* **Xcode 12.0** or later
* **iOS 14.0** or later
* **Swift 5.3** or later
* **Active Internet Connection**

---

## ⚙️ Installation & Setup

1. **Unzip the Project Folder**
   Extract the provided `.zip` file.

2. **Open in Xcode**
   Navigate to the extracted folder and open the `.xcodeproj`.

3. **Firebase Configuration**

   * A `GoogleService-Info.plist` is required to connect to a firebase backend, this file is not provided for security reasons, so if you want to test the app out you need to create your own firebase back end and include this file in the root directory.


4. **Run the App**

   * Select a simulator or physical device.
   * Press `⌘ + R` or click the **Run** button.

---

## 🔐 Authentication Instructions

To access most features, users must sign in.

### Option 1: Create a New Account

* Launch the app
* Tap **Sign Up Using Email** and complete the form

### Option 2: Use Test Credentials

| Role   | Email                | Password |
| ------ | -------------------- | -------- |
| Expert | `micheal@expert.com` | `123456` |
| Client | `c1@clients.com`     | `123456` |

> *Note: If test login fails, you may create a new account using the Sign-Up flow.*

---

## 🧪 In-Progress Development

✅ **Working Features**

* Map UI
* Firebase-based messaging
* User authentication
* Profile creation and browsing
* Posting/viewing requests

🛠️ **Planned Features**

* Escrow payments with Firebase/Stripe
* Push notifications
* Admin dashboard
* Background checks and badge system
* Improved UI for iPad/tablet support

---

## 🌍 Scalability Challenges Tackled

* Efficient management of **global map data**
* Handling of **large real-time datasets** in Firestore
* Support for **image-heavy profiles** and chat via Firebase Storage
* Designed with scalability and security in mind using **modular SwiftUI views** and **asynchronous data flows**

---

## 🧠 Learning Outcomes

* Gained experience with **SwiftUI and UIKit integration**
* Learned and applied **Firebase Authentication, Firestore, and Storage**
* Built reusable, testable Swift components for real-world user flows
* Implemented **real-time messaging** and dynamic map-based UI
* Designed with scalability, maintainability, and **clean architecture principles**

---

## 📸 Screenshots

Here are screenshots of the Program in action:

![Screenshot](https://imgur.com/sl0XEmO.png)


![Screenshot](https://imgur.com/oEHkg2s.png)


![Screenshot](https://imgur.com/3WZjpUN.png)


![Screenshot](https://imgur.com/2JzWo5X.png)



![Screenshot](https://imgur.com/OFA0JVi.png)



![Screenshot](https://imgur.com/du0D872.png)


![Screenshot](https://imgur.com/4xdsCPc.png)


![Screenshot](https://imgur.com/RMhx1c3.png)


![Screenshot](https://imgur.com/BEavRwN.png)


![Screenshot](https://imgur.com/SznMvMI.png)


![Screenshot](https://imgur.com/0yp139i.png)


![Screenshot](https://imgur.com/f3RrHHB.png)


![Screenshot](https://imgur.com/nkCGFGh.png)


![Screenshot](https://imgur.com/ST64gty.png)


![Screenshot](https://imgur.com/oBSUnBA.png)


![Screenshot](https://imgur.com/RL3wv1t.png)


![Screenshot](https://imgur.com/cEb2Ttf.png)


![Screenshot](https://imgur.com/xc4E1cI.png)


![Screenshot](https://imgur.com/1RB6yid.png)


![Screenshot](https://imgur.com/rxKBNTO.png)

---

## 🤝 Contact

**Developer:** Ryan Loi, Michelle Loi, Amirreza Pazira, Alan Huynh, Josh Davis
