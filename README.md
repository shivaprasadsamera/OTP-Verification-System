# 🔐 OTP Verification System – Python Capstone Project

This project is a secure and user-friendly **OTP (One-Time Password) Verification System** developed in Python as part of a capstone project. 
It demonstrates secure authentication practices and can be integrated into systems requiring identity verification for sensitive operations like account creation, password resets, and transaction validation.

---

## 🚀 Features

- 🔑 Generates time-based or random OTPs securely
- 📩 Sends OTP via email (SMTP integration)
- ⏱️ Includes OTP expiration time
- ❌ Limits the number of verification attempts
- 🛡️ Validates user input securely

---

## 🛠️ Tech Stack

- **Python 3.x**
- `smtplib` – for sending OTP emails
- `random`, `secrets`, or `pyotp` – for OTP generation
- `time` – for expiry handling

---

## 📂 Project Structure

otp-verification-system/
├── otp_verifier.ipynb # Jupyter Notebook (core implementation)
├── .env # Environment variables (email credentials) - optional
├── requirements.txt # List of required packages
└── README.md # Project documentation

## 🔧 Setup Instructions

### 1. Clone the Repository


**git clone https://github.com/yourusername/otp-verification-system.git
cd otp-verification-system**

## 2. Install Dependencies

pip install -r requirements.txt

## 3. Configure Environment
Create a .env file with your email credentials (recommended for security):

EMAIL_ADDRESS=your_email@example.com
EMAIL_PASSWORD=your_app_password
Note: Use an app password if you're using Gmail.

## 4. Run the Notebook
Launch the notebook and execute the cells:

jupyter notebook otp_verifier.ipynb

**💡 Use Cases**
User signup verification

Transaction approvals

Two-factor authentication

Password reset flows

**✅ Future Improvements**
Add GUI with Tkinter or PyQt

Integrate SMS gateway (e.g., Twilio) for mobile OTP

OTP via WhatsApp or Telegram Bot

Logging and database support

