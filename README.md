# 🏛️ Smart Campus Navigator

A responsive **Smart Campus Dashboard** built as a BTech 2nd Year project that simulates real-time campus navigation, live occupancy tracking (IoT-based simulation), event updates, and an interactive campus assistant.

This project demonstrates frontend design, dynamic DOM manipulation, and simulated real-time data systems using vanilla JavaScript.

---

## 🚀 Project Overview

Smart Campus Navigator is a web-based dashboard that helps students:

- 📍 Explore campus buildings interactively  
- 👥 View real-time occupancy (simulated IoT sensors)  
- 📅 Check today's campus events  
- 🤖 Ask questions using a rule-based campus assistant  

The system simulates a **real-world smart campus environment** where buildings report live crowd data and students receive instant information.

---

## 🧠 Key Features

### 1️⃣ Interactive Building Explorer
- Grid-based building navigation
- Active building highlight
- Context-aware assistant response on click

### 2️⃣ Live Occupancy System (IoT Simulation)
- Each building has a base occupancy
- Random variance simulates real sensor fluctuation
- Auto-updates every 10 seconds
- Dynamic occupancy bars with percentage display

### 3️⃣ Campus Events Panel
- Displays today's scheduled events
- Time + location structured display
- Clean dashboard UI

### 4️⃣ Smart Campus Assistant
- Rule-based NLP logic
- Handles queries like:
  - Library timings
  - DBMS lab availability
  - Parking status
  - WiFi details
  - Today's events
- Enter key + button support

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3 (Responsive Design + Modern UI Styling)**
- **Vanilla JavaScript (DOM Manipulation + Data Simulation)**
- No external libraries or frameworks

---

## 📂 Project Structure
Smart-Campus-Navigator/
│
├── SmartCampusNavigator.html
└── README.md


This is a standalone frontend project and does not require a backend.

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Smart-Campus-Navigator.git
2. Open the file:
  SmartCampusNavigator.html
3. Run directly in your browser.

No installation required.

## 🔄 How the Real-Time Simulation Works

Each building has a predefined base occupancy.

Every 10 seconds:

A random variation is added.

Value is clamped between 4% and 98%.

UI updates dynamically.

This simulates IoT crowd sensors in a smart campus environment.

## 🎯 Learning Outcomes

Through this project, I practiced:

Responsive dashboard UI design

Grid & Flexbox layouts

DOM rendering from data arrays

Event listeners and dynamic updates

Simulated real-time systems

Basic assistant-style query handling

## 🚧 Future Improvements

Integrate real backend API

Replace rule-based assistant with ML/NLP model

Add Google Maps integration

User authentication system

Real database-driven event system

## 📌 Project Type

Academic Project · Smart Campus System Simulation · Frontend + IoT Concept

##⭐ If you found this interesting, feel free to star the repository!
