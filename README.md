## The continuation will be "Web_Security_Awareness_V1.06" (in progress)
![image](https://github.com/user-attachments/assets/8c06e552-eb49-48a6-8f8f-5db47cb283cf)

# Multi-Language UI & Authentication Simulation

A professional front-end project focused on **UI cloning**, **dynamic internationalization (i18n)**, and **state-based interface simulation** developed with Vanilla JavaScript and modern CSS.

## 🚀 Key Features

* **Dynamic Language Switching:** Instant translation between English, Polish, and Arabic without page reloads.
* **RTL (Right-to-Left) Support:** Automatic layout restructuring for Arabic language support, including form alignment and device positioning.
* **Two-Step Verification Simulation:** A CSS-based mobile "IoT Device" overlay that triggers upon form submission to simulate secondary authentication.
* **Responsive Layout:** Built with a "Mobile-First" mindset using CSS Flexbox for a clean, platform-agnostic experience.

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (Custom properties and Flexbox layout).
* **Scripting:** Vanilla JavaScript (ES6+) for DOM manipulation and localization logic.
* **Concepts:** Object-based translation mapping and event-driven UI state management.

## 📂 Technical Deep Dive

### **Logic Implementation**
* **Translation Engine:** Uses a centralized `translations` object to map UI strings across different languages (EN, PL, AR).
* **State Management:** Tracks the current language state to toggle CSS classes for **RTL (Right-to-Left)** support, ensuring a seamless experience for Arabic-speaking users.
* **Form Handling:** Intercepts default form submissions to trigger custom simulation events, such as the appearance of the "Educational Warning" and the "IoT Device" authentication modal.

## 🔧 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/ui-simulation-project.git](https://github.com/yourusername/ui-simulation-project.git)
    ```
2.  **Open the project:**
    Simply open `index.html` in any modern web browser.

### 🔑 Simulation Credentials
To successfully pass the simulated IoT authentication layer and test the logical flow, use the following credentials:
* **Device ID:** `istanbul`
* **Security Code:** `imaro`

---

## ⚠️ Disclaimer
This project is developed strictly for **educational purposes** and **UI/UX research**. It is a simulation designed to demonstrate front-end logic and security awareness. It does not collect, store, or transmit any user data.

---
*Created by Omimas - 2025/2026*
