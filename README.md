![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)
![Last Commit](https://img.shields.io/badge/last%20commit-recent-success?style=flat-square)
![License: MIT](https://img.shields.io/badge/license-MIT-yellowgreen?style=flat-square)
![Made With](https://img.shields.io/badge/Made%20with-Flask-blue?style=flat-square&logo=flask)
![🔐 Encrypted](https://img.shields.io/badge/%F0%9F%94%90-AES_Encrypted-444444?style=flat-square)
![📤 Uploads](https://img.shields.io/badge/Supports-Uploads-007bff?style=flat-square)
![📥 Downloads](https://img.shields.io/badge/Supports-Downloads-007bff?style=flat-square)
![💻 Flask](https://img.shields.io/badge/Backend-Flask-000000?style=flat-square&logo=flask)
![🧠 Client-Side](https://img.shields.io/badge/Client-Side_Encryption-purple?style=flat-square)
![🧬 AES](https://img.shields.io/badge/Algorithm-AES_256-orange?style=flat-square)


<p align="center">
  <img src="DecryptMikeLogo.png" alt="DecryptMike Logo" style="max-width: 100%; height: auto;"/>
</p>

<h3 align="center">
  🛡️ Secure File Transfer Tool
</h3>

<h5 align="center">
   A secure, client-side encrypted file transfer web app built with Python and Flask.
Think “mini WeTransfer” but with<br>hacker-grade protection: every file is encrypted using AES before upload and decrypted only after download.
</h5>

---

## ⚙ Features

- 🔐 Client-side AES encryption using cryptography.fernet

- 📤 Upload & encrypt any file (images, PDFs, docs, zips, etc.)

- 📥 Decrypt & download encrypted .enc files back to their original form

- 🧠 Stylish hacker-inspired UI with Matrix aesthetics

- 💾 File integrity via .key file + Flask routes

- 🔐 Secure folder storage for original, encrypted, and decrypted assets

## ⚡️ Local, fast, and easy to run

---

## 🧪 Tech Stack

| Layer       | Tech Used                          |
|-------------|------------------------------------|
| **Backend** | Python 3.11, Flask                 |
| **Encryption** | AES (Fernet - `cryptography`)  |
| **Frontend** | HTML, inline CSS                  |
| **UI Theme** | Hacker/Cyberpunk Matrix style     |

--- 

## 📁 Folder Structure
```
secure-file-transfer/
│
├── static/                # Logo assets, CSS if needed
├── templates/             # HTML (index.html)
├── uploads/               # Raw uploaded files
├── encrypted/             # AES encrypted versions
├── decrypted/             # Final decrypted files
├── encryption_utils.py    # Core AES logic
├── generate_key.py        # One-time key generation
├── app.py                 # Flask server logic
├── filekey.key            # 🔐 Auto .gitignored
├── requirements.txt       # Dependencies
└── README.md              # This file
```
--- 

## 🚀 Getting Started

 - Clone & Activate Environment
```
git clone https://github.com/DecryptMike/Secure-File-Transfer.git
cd Secure-File-Transfer
python3 -m venv venv
source venv/bin/activate
```
-  Install Requirements
```
pip install -r requirements.txt
```
-  Generate Encryption Key (Run Once)
```
python generate_key.py
```
This creates a filekey.key (auto .gitignored) — keep this safe!

- Launch the Web App
```
python app.py
```
- Then visit: http://127.0.0.1:5000
  
---

## 🌐 How It Works

1. User uploads a file → it’s encrypted client-side with AES.
2. App stores .enc version in /encrypted
3. Download & send .enc file
4. Recipient uploads it back → file is decrypted only with matching key

---

## 💡 Why I Built It

To demonstrate real-world cybersecurity fundamentals — encryption, secure file transfer, and web-based automation.
It’s also a perfect portfolio piece for recruiters to showcase Flask + encryption + frontend integration in a clean, branded UI.

---

## 🖼️ Preview

(Optional — upload your screenshot and rename it to preview.png)

---

## ⚠️ Disclaimer

This project is for educational use only.
Do not use this in production without enhancements such as:

- Authenticated sessions
- Key rotation
- Secure HTTPS hosting

## 🧠 Skills Demonstrated

- Flask web routing
- AES encryption (Fernet)
- File I/O in Python
- Secure file handling logic
- Frontend + backend integration
- Cyber-themed UI/UX

---

## 💻 Built by [@DecryptMike](https://github.com/DecryptMike)

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20for-Cybersecurity-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Made%20By-DecryptMike-limegreen?style=for-the-badge&logo=github"/>
</p>
