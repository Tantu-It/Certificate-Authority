Digital Certificate Management System (Certificate Authority)
This project is a web-based application designed to provide information about digital certificate systems, the role of Certificate Authorities (CA), and related security services. The system features a modern user interface with basic integrated authentication.

📌 Project Overview
Project Name: Certificate Authority.

Objective: To provide a platform for learning about information security, SSL/TLS certificates, and digital signatures.

Tech Stack:

Frontend: HTML5, CSS3 (Custom styles & Tailwind CSS).

Icons & Fonts: Font Awesome, Google Fonts (Roboto).

Scripting: JavaScript (ES6).

Storage: LocalStorage (used for maintaining login states).

✨ Key Features
User Authentication: The system requires a login to access the main content.

Home Page (Index): Introduces the concepts, roles, and operational processes of a CA.

About Page: Detailed information on the importance of digital certificates and offered services.

Contact Page: A form for users to send inquiries to the support team.

Responsive Design: The interface is optimized for both desktop and mobile devices.

🛠 Installation and Usage

Login Credentials:

Username: nhom15

Password: 123

(Note: The system validates login conditions via script.js and stores the session state in localStorage).

3. Folder Structure
Plaintext
├── index.html      # Home page (Core information)
├── about.html      # Detailed introduction page
├── contact.html    # Contact and support page
├── login.html      # Authentication page
├── style.css       # Custom UI styling
└── script.js       # Logic for Login/Logout
🛡 Security and Navigation
The project utilizes a window.onload mechanism to ensure that unauthenticated users are automatically redirected to login.html.

When clicking Logout, the system clears all data in localStorage to secure the session.

Developed by: Group 15 - UTH (University of Transport and Communications Ho Chi Minh City).
