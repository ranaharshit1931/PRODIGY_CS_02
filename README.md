# 🖼️ Image Encryption Using Pixel Manipulation  
### 🔐 Prodigy Cybersecurity Internship – Task 2

## 📌 Task Overview

This project is part of **Task 2** for the **Prodigy Cybersecurity Internship**. The objective is to implement a basic image encryption and decryption mechanism using pixel value manipulation.

The program works by shifting pixel values in an image using a user-defined key (shift value), applying **modular arithmetic** to ensure pixel values stay within the valid 0–255 range.

---

## 🚀 Features

- 🔐 **Encrypts** an image by shifting pixel values
- 🔓 **Decrypts** the image by reversing the shift
- 🧮 Uses **NumPy** for efficient pixel data manipulation
- 📷 Supports most standard image formats via **Pillow (PIL)**

---

## 🧠 How It Works

1. The image is loaded using `Pillow` and converted into a NumPy array.
2. Each pixel's RGB values are increased or decreased by a shift value.
3. The modified data is saved as a new image file.
4. Modular arithmetic (`% 256`) ensures values wrap around within valid bounds.
