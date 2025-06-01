# 🛒 COMPRIFY - INTELLIGENT SHOPPING SYSTEM

## 🔖 Project Title

**COMPRIFY (To Buy)** - Intelligent Shopping System with IoT, Computer Vision, and Integrated Shopping Zone

## 👨‍💻 Team Members

- **Baskaran M S**
- **Yeeswanth P L**
- **Thamizh T L**

> Final Year B.E Project | Dept. of CSE, Parisutham Institute of Technology and Science, Thanjavur

---

## 🚀 Overview

COMPRIFY is a next-gen smart shopping platform combining **IoT**, **Computer Vision**, and **real-time intelligence** to deliver seamless retail experiences across **online**, **in-store**, and **smart shopping trolleys**. It supports multi-language, multi-theme, cross-platform presence, and powerful admin tools via POS.

---

## 🌐 Live Demo

- 🔗 [Live Link - COMPRIFY Homepage](#)

---

## 🔗 Repositories

- 🖥️ [Frontend GitHub](#)
- 🛒 [POS Web GitHub](#)
- 💻 [POS Desktop GitHub](#)
- 📱 [Mobile App GitHub](#)
- 🔙 [Backend GitHub](#)
- 🔌 [IoT Server GitHub](#)
- 📡 [IoT Hardware GitHub](#)

---

## 🔐 Demo Credentials

### 👑 Admin

- **Username**: `admin@demo.com`
- **Password**: `Admin@123`

### 🧑‍🏫 Staff

- **Username**: `staff@demo.com`
- **Password**: `Staff@123`

### 🧑‍🎓 Student / Customer

- **Username**: `parent@demo.com`
- **Password**: `Parent@123`

---

## 🧩 Features

### 🛍️ Online Shopping

- Store-specific login & shopping
- Add/Remove items from cart & favorites
- In-app payments with **Razorpay**
- View all stores & their products
- Order history per store

### 🛒 In-store Shopping

- Browse & pin nearby stores
- Check real-time product availability & pricing
- Create smart shopping lists
- Bill history per store

### 🤖 Smart Shopping

- Scan QR to connect smart trolley
- View live cart feed (Computer Vision)
- Secure checkout via Razorpay
- Fraud detection with POS-side verification

### 🔑 Key Functionalities

- 🗣️ 30+ regional language support
- 🎨 5+ app themes
- 💳 Secure payments
- 🔄 Seamless switching between shopping modes

---

## 🧾 POS System (Web + Desktop)

- 🌍 Register stores to make them globally discoverable
- 🧾 Manage: Bills, Employees, Customers, Products, Categories
- 🛒 Handle: Online, In-Store, Smart Trolley bills
- 🧠 Real-time trolley monitoring and sessions
- 🚨 Smart fraud detection alerts with sync option
- 💡 Theme Switcher (Light / Dark), View Switch (Grid / Table)

---

## 📡 Live Updates Architecture

- **IoT → IoT Server** via **WebSocket**
- **IoT Server → Backend** via **Socket.IO**
- **Backend → POS / App** via **Socket.IO**
- **Redis Cloud** to manage live user-socket sessions
- **AWS S3** for product and store images

---

## 🧠 Computer Vision

- **YOLOv11** used for product recognition
- **Roboflow** for dataset labeling and training

### Recognized Products:

- Cococola
- Pepsi
- Kitkat
- Oreo
- Redbull
- Dairy Milk
- Kurkure
- Lays

---

## 🖥️ POS Web Dependencies

> Built with React + Tailwind + Radix UI + Redux + Vite

## 💻 POS Desktop Dependencies

> Electron-based with NSIS Installer support

---

## 🧰 Tech Stack

| Module         | Tech Used                                   |
| -------------- | ------------------------------------------- |
| **IoT**        | ESP32, ESP32-CAM, PIR Sensor, Arduino IDE   |
| **CV**         | YOLOv11 + Roboflow                          |
| **IoT Server** | Python + WebSocket + Socket.IO              |
| **Backend**    | Node.js, Express.js, MongoDB, Redis, AWS S3 |
| **POS**        | React.js, TailwindCSS, Electron.js          |
| **Frontend**   | React.js + Tailwind                         |
| **Mobile App** | Flutter (Android/iOS)                       |

---

## 🌍 Mobile App - Language Support

Supports 30+ languages like Hindi, Tamil, Telugu, Marathi, Bengali, Kannada, Malayalam, Urdu, Punjabi, Assamese, and global languages like Spanish, French, Chinese, etc.

---

## 🎨 App Themes

- Light Theme
- Dark Mode
- Midnight Blue
- Deep Emerald
- Royal Amethyst
- Sunset Orange
- Slate Grey
- Rose Gold

---

## 📦 Pending Work / Future Scope

- Integrate **weight sensors** for smart trolley
- Add **price history** and **comparison chatbot**
- Full integration for all mobile UI screens
- Add **delivery** & **supplier** modules
- Expand POS to support advanced billing features

---

## 💬 Final Thoughts

COMPRIFY proved that it’s possible to revolutionize the retail ecosystem using a combination of **IoT**, **AI**, and **modern software engineering**. With further investments in **hardware**, this project is **market-ready** and can disrupt conventional shopping models.

> ⚠️ All data & tech are deployed only for academic, non-commercial use.

---

## 📸 Screenshots

![User Management](assets/screenshots/31.png)
