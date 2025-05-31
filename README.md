# 🔐 Image Encryptor & Decryptor App

Welcome to the **Image Encryptor & Decryptor Web App** — a beautifully designed, front-end only tool to **secure your images using XOR encryption** in your browser. Built with vanilla HTML, CSS, and JavaScript, this project is ideal for learners, privacy enthusiasts, and anyone curious about lightweight cryptography in web development.

## Encryptor Preview
![Image](https://github.com/DinukaRasanjana/Image-Encrypt-Decrypt-Web-Application/blob/fb62bb2101a59e4a6bc7acca902a8d3f9fe5e607/Screenshot%20(5).png)

## ✨ Features

- 🔒 **Encrypt any image** using a custom password.
- 🔓 **Decrypt encrypted data** using the same password.
- 📁 Client-side file handling (no uploads, 100% privacy).
- 🎨 Stylish frosted-glass UI with auto-changing backgrounds.
- 🧠 Simple XOR encryption logic — perfect for learning.

---

## 🖼️ App Previews

### 🔓 Decryption Page
![Image](https://github.com/DinukaRasanjana/Image-Encrypt-Decrypt-Web-Application/blob/dada2936b9c8f069cfba88a65281a9f48e8e8502/Screenshot%20(6).png)

---

## 🛠️ How It Works

### 🔐 Encryption Process

1. Upload any image (JPG, PNG, etc.).
2. Enter a custom **encryption key** (password).
3. The image is read as Base64 and encrypted character-by-character using **XOR logic**.
4. The encrypted string is saved as a `.txt` file.

> 💡 This basic XOR method is **not secure for production** but is great for understanding how encryption works at the byte level.

### 🔓 Decryption Process

1. Upload the encrypted `.txt` file.
2. Enter the **same key** used for encryption.
3. The encrypted Base64 string is decrypted and rendered as the original image.

---

## 🚀 Getting Started

### 🧩 Prerequisites

- A modern browser (Chrome, Firefox, Edge, etc.)
- No server, frameworks, or dependencies needed.

### 🛠️ Setup Instructions

```bash
git clone https://github.com/IT20056384/Image-Encrypt-Decrypt-Web-Application.git
cd image-encryptor-app

