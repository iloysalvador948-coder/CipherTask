# CipherTask - Secure Encrypted To-Do System

A highly secure, enterprise-grade task management application built with Flutter, strictly adhering to the MVVM architectural pattern. 

## 🛡️ Security Features Implemented
* **Data at Rest:** AES-256 field-level encryption for highly sensitive notes (via `encrypt` package).
* **Encrypted Database:** Secure local storage using an encrypted Hive box.
* **Hardware Key Storage:** Database encryption keys are generated and stored securely using `flutter_secure_storage`.
* **Biometric Authentication:** Fingerprint/FaceID login (requires a password login first).
* **Session Management:** Automatic app lock after 2 minutes of user inactivity.
* **🌟 BONUS (+5 pts):** Multi-Factor Authentication (MFA) simulated via a 6-digit OTP during registration.
* **🌟 BONUS (+5 pts):** Screenshot prevention implemented via `flutter_windowmanager`.

## 👥 Team Members & Roles
* **[Student 1 Name]** - Team Lead (M1) / Architecture Setup
* **[Student 2 Name]** - Security & Encryption Integration
* **[Student 3 Name]** - UI/UX & MVVM Implementation
* **[Student 4 Name]** - Session Management & Biometrics
*(Note: Adjust the names and roles based on your actual group!)*

## 📂 Architecture
This project strictly follows the required MVVM structure, separating the View (UI), ViewModel (State/Logic), and Services (Data/Security).