---


# 🕵‍♂ Image-Based Steganography using OpenCV

This project implements **image-based steganography** using OpenCV in Python. It allows users to **hide secret messages inside an image** and later **retrieve them with a passcode**.

---

## 🔐 Features

- 🔏 Encrypt secret messages into images (Steganography)
- 🔓 Decrypt hidden messages using a secure passcode
- 🖼 Uses **lossless PNG** format to prevent data loss
- 🧩 Simple CLI interface using Python

---

## 🛠 Prerequisites

Make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2`)
- `os` module (included in Python standard library)

### 📦 Install OpenCV

bash
pip install opencv-python
`

---

## 📁 File Structure


├── encrypt.py              
├── decrypt.py              
├── photo.png               
├── encryptedImage.png      
├── README.md               


---

## 🚀 Usage

### 🔐 Encryption (Hiding a Message)

1. Place your **image file** (preferably `.png`) in the project directory.
2. Run the encryption script:

bash
python encrypt.py


3. Enter the **secret message** and **passcode** when prompted.
4. The output will be saved as `encryptedImage.png`.

---

### 🔓 Decryption (Retrieving the Message)

1. Run the decryption script:

bash
python decrypt.py


2. Enter the **correct passcode** when prompted.
3. The **hidden message** will be displayed if the passcode matches.

---

## 🌐 Deployment to GitHub

bash
# Initialize Git repository
git init

# Add files
git add .

# Commit
git commit -m "Initial commit: Steganography project"

# Add remote (replace with your GitHub URL)
git remote add origin https://github.com/yourusername/steganography-opencv.git

# Push to GitHub
git push -u origin main


---

## ⚠ Notes

* Use **PNG images** to avoid compression artifacts (JPG may corrupt hidden data).
* Make sure your message is not too large for the image resolution.
* This project is intended for **educational** and **development** use only.


---

## ⭐ Star the Repo

If you find this useful, feel free to star ⭐ the repository and share!



---
