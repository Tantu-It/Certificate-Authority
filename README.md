# Certificate Authority Management System
![UTH](https://img.shields.io/badge/University-UTH-blue) ![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview
This project is a web application providing insights into Digital Certificate Authorities. It is designed with a focus on information security and user authentication.

---

## ✨ Key Features
| Feature | Description |
| :--- | :--- |
| **Authentication** | Secure login using `localStorage` and `script.js`. |
| **Responsive UI** | Built with Tailwind CSS for mobile and desktop compatibility. |
| **Information** | Comprehensive guide on SSL/TLS and Digital Signatures. |

---

## 🛠 Usage Instructions

### 1. Credentials
To access the system, please use the following credentials:
* **Username:** `nhom15`
* **Password:** `123`

### 2. Execution
Simply open `login.html` in your favorite browser.

---

## 🛡 Business Logic (BA Perspective)
The application follows a strict authentication flow:
1. **Login Validation:** Checks input against predefined constants.
2. **Session Management:** Stores `isLoggedIn` flag in the browser's Local Storage.
3. **Route Guard:** Each page (`index`, `about`, `contact`) verifies the session on load.

---

**Developed by:** Group 15 - IT & Data Science - UTH
