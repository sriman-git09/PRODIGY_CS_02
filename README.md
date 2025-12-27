# PRODIGY_CS_02
# 🖼️ Image Encryption Tool using Pixel Manipulation

## 📌 Overview
This project is a **GUI-based Image Encryption and Decryption Tool** developed using **Python**, **Tkinter**, and **Pillow**.  
It demonstrates how **basic pixel manipulation techniques** can be used to obscure image data for educational and learning purposes.

The tool allows users to:
- Select an image
- Encrypt the image using a numeric key
- Decrypt the image using the same key



---

## 🔐 How It Works
- Each image pixel contains RGB values (0–255)
- A simple **XOR operation** is applied to each pixel using a user-provided key
- The same operation reverses the encryption when the correct key is used

> XOR is used because it is **reversible**, making it suitable for learning encryption logic.

---

## 🖥️ Features
- User-friendly GUI (Tkinter)
- Supports PNG and JPG images
- Key-based encryption (0–255)
- Encrypt and decrypt functionality
- Lightweight and easy to run

---

## 🛠️ Technologies Used
- Python 3
- Tkinter (GUI)
- Pillow (Image Processing)

---

## 📦 Installation▶️ Usage

Run the Python file

Click Select Image

Enter an encryption key (0–255)

Click Encrypt Image

Use the same key to Decrypt Image

Encrypted and decrypted images are saved in the project directory.

⚠️ IMPORTANT CAUTION & AWARENESS NOTICE

🚨 This project is strictly for educational and awareness purposes only.

This is NOT secure encryption

It should NOT be used to protect sensitive, personal, or confidential data

Pixel manipulation and XOR-based encryption can be easily reversed

This project does NOT follow modern cryptographic standards (AES, RSA, etc.)

🔐 For real-world security, always use:

Industry-standard encryption algorithms

Proper key management

Proven cryptographic libraries

This project exists to raise awareness and build foundational understanding of how data can be manipulated at a low level.

🎯 Learning Outcomes

Understanding image pixel structure

Basic encryption & decryption logic

Hands-on experience with GUI development

Awareness of why simple encryption is insufficient for real security

📜 Disclaimer

The author is not responsible for misuse of this code.
Use responsibly and only for learning, demonstrations, or academic purposes.

🙌 Acknowledgment

Thanks to Prodigy Infotech for providing this learning opportunity.

👨‍💻 Author

Sriman Kundu
Cybersecurity Enthusiast | Ethical Hacking Learner
```bash
pip install pillow
