# ENCO 🔐 - Advanced Encryption Tool

ENCO is a sleek, browser-based, real-time encryption and decryption tool built entirely in a single HTML file. With no dependencies, no backend, and no data sent to any servers, ENCO guarantees privacy and portability while supporting industry-standard encryption algorithms like AES-GCM and AES-CBC.

## 🔧 Features
- 🔐 **AES Encryption** (AES-GCM & AES-CBC)
- 🔑 **PBKDF2 key derivation with SHA-256 hashing**
- 💡 **Key strength meter** for password feedback
- 🎲 **Random secure key generation**
- 💾 **Export encrypted data as a text file**
- 📋 **Copy output to clipboard**
- 🛠️ **Adjustable settings** for iterations and algorithm choice
- 📎 **Completely offline capable**

## 🚀 Getting Started
1. Download or clone the repository.
2. Open `index.html` in any modern browser.
3. Type or paste the text you want to encrypt/decrypt.
4. Enter a secret key.
5. Choose options under ⚙️ **Advanced Settings** (optional).
6. Click **Encrypt 🔒** or **Decrypt 🔓**.

💡 **All operations are performed locally in your browser using the Web Crypto API.**

## 📦 File Structure
- `index.html` → Self-contained app with embedded CSS + JavaScript

## 🛡️ Security
- Utilizes **AES (256-bit)** for encryption.
- Encryption key is derived using **PBKDF2** with a configurable number of iterations.
- Encryption and decryption happen entirely **in-browser** using the Web Crypto API.
- No data is ever transmitted **outside your device**.

## 📋 FAQ Highlights
- **Can I use it offline?** Yes, ENCO works as a single HTML file.
- **Is it secure?** Yes, your data never leaves the browser.
- **What encryption modes are supported?** AES-GCM (default), AES-CBC.

## 🌐 Browser Compatibility
ENCO works best in modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## 🧪 Live Demo
You can try the online version of ENCO here: [ENCO Live Demo](https://enc0.neocities.org/)

Alternatively, open `index.html` directly in your browser!

## 🧑‍💻 Author
Built with ❤️ by Koray Öztürk

## 📜 License
This project is licensed under the MIT License.
