🔐 Biometric-Based Exam Gate Authentication System using Blockchain
📌 Overview

This project is a secure authentication system designed for examination centers using Biometrics + Blockchain + OTP (SMS).

The system ensures that only authorized students can enter the exam hall by validating:

Fingerprint biometrics
Blockchain-stored encrypted data
OTP-based verification

This provides a multi-layered security system to prevent malpractice and identity fraud.

🚀 Key Features
Biometric authentication (Fingerprint-based)
Blockchain-based secure data storage
AES encryption for biometric templates
IPFS integration for decentralized storage
OTP (SMS) verification using GSM
Admin + Student authentication workflows
Tamper-proof and secure system
🎯 Problem Statement

Traditional exam authentication systems rely on:

Hall tickets
Manual verification

These methods are:

Time-consuming
Prone to impersonation
Vulnerable to data tampering

This project solves these issues using secure digital authentication mechanisms.

💡 Solution Approach

The system combines three major technologies:

1. Biometrics
Captures fingerprint data
Extracts minutiae features
Generates secure biometric templates
2. Blockchain
Stores hashed biometric data
Ensures immutability and transparency
Prevents unauthorized data modification
3. OTP Verification
Sends OTP via GSM network
Adds second layer authentication

Together, this creates a 2-factor authentication system with high security.

🏗️ System Architecture
The system works in two phases:

🔹 Registration Phase
User submits biometric + personal data
Data is encrypted using AES
Stored in IPFS + Blockchain
OTP generated for verification

🔹 Entry Phase
Student scans fingerprint
Data is matched with blockchain records
OTP sent for final verification
Access granted or denied

🛠️ Technologies Used
Blockchain (Ethereum)
IPFS (InterPlanetary File System)
Python (Flask)
Django (Web Application)
HTML, CSS, JavaScript
AES Encryption Algorithm
SHA-256 Hashing
GSM (OTP via SMS)

🔐 Security Implementation
AES encryption for biometric data
Hashing using SHA-256
Decentralized storage (IPFS + Blockchain)
No centralized database vulnerability
Multi-layer authentication

This ensures:
Data integrity
Privacy
Protection against cyber attacks

⚙️ How It Works
Admin registers student details
Biometric data is captured and encrypted
Data stored in blockchain securely
At exam gate:
Fingerprint is scanned
System verifies data
OTP is sent to user
Access is granted only after successful verification

📊 Advantages
Eliminates exam impersonation
High security with decentralization
Reduces manual verification time
Prevents data tampering
Scalable and reliable system

⚠️ Limitations
Requires biometric hardware
Blockchain setup complexity
Network dependency for OTP

🔮 Future Enhancements
Face recognition integration
Mobile app for authentication
Faster blockchain networks (e.g., Hyperledger)
AI-based anomaly detection

📄 Project Document
👉 [View Full Project Report](./docs/Biometric Authentication.pdf)

👥 Contributors
U. Bhargavi

📚 References
Based on research in blockchain security, biometrics, and distributed authentication systems.

⭐ Final Note
This project demonstrates how combining Blockchain + Biometrics + OTP can create a highly secure and tamper-proof authentication system for real-world applications like examinations.
