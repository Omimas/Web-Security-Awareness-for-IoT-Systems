# Web Security Awareness for IoT Systems
![image](https://github.com/user-attachments/assets/8c06e552-eb49-48a6-8f8f-5db47cb283cf)

A professional front-end simulation focused on **UI cloning**, **dynamic internationalization (i18n)**, and **state-based interface simulation**. This project demonstrates how modern web interfaces handle localization, RTL (Right-to-Left) layouts, and secondary authentication flows.

## 🚀 Key Features

* **Dynamic Language Switching:** Seamless translation between English, Polish, and Arabic without page reloads.
* **RTL (Right-to-Left) Support:** Full layout restructuring for Arabic language support, including form alignment and device positioning.
* **Two-Step Verification Simulation:** A custom CSS-based mobile "IoT Device" overlay that triggers upon form submission to simulate secondary authentication.
* **Responsive Layout:** Built with a "Mobile-First" approach using CSS Flexbox for a clean, platform-agnostic experience.

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (Custom properties and Flexbox layout).
* **Scripting:** Vanilla JavaScript (ES6+) for DOM manipulation and localization logic.
* **Concepts:** Object-based translation mapping and event-driven UI state management.

## 📂 Technical Deep Dive

### **Logic Implementation**
* **Translation Engine:** Uses a centralized `translations` object to map UI strings across different languages (EN, PL, AR).
* **State Management:** Tracks the current language state to toggle CSS classes for **RTL** support, ensuring a seamless experience for diverse user groups.
* **Form Handling:** Intercepts default form submissions to trigger custom simulation events, such as the "Educational Warning" and the "IoT Device" authentication modal.

## 🔧 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Omimas/Web-Security-Awareness-for-IoT-Systems.git](https://github.com/Omimas/Web-Security-Awareness-for-IoT-Systems.git)
    ```
2.  **Run the project:**
    Simply open `index.html` in any modern web browser.

### 🔑 Simulation Credentials
To successfully pass the simulated IoT authentication layer and test the logical flow, use the following credentials:
* **Device ID:** `istanbul`
* **Security Code:** `imaro`

---

## ⚠️ Disclaimer
This project is developed strictly for **educational purposes** and **UI/UX research**. It is a simulation designed to demonstrate front-end logic and security awareness. It does not collect, store, or transmit any real user data.

---
*Developed by Omimas*
