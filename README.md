# SteganoS – Secure Data Hiding Web App

SteganoS is a simple and modern web application that hides secret data inside images using **LSB (Least Significant Bit) steganography**.
You can hide **text** or even a **small image** inside another image and later extract it using a password.

---

## Features

* Hide **text** inside an image
* Hide a **secret image** inside another image
* Password protection
* Download the processed image
* Extract hidden data from an image
* Clean and responsive UI (Tailwind CSS)

---

## How to Use

### Encryption (Hide Data)

1. Open the website.
2. Click **Get Started → Encrypt**.
3. Upload a **Carrier Image** (PNG recommended).
4. Choose:

   * *Hide Text* → Enter your secret message
   * *Hide Image* → Upload a secret image
5. Enter a **Password**.
6. Click **Process & Download**.
7. Download the generated **Stego-Image**.

### Decryption (Extract Data)

1. Click **Decrypt**.
2. Upload the image that contains hidden data.
3. Enter the **same password** used during encryption.
4. Click **Extract Data**.
5. View or download the hidden content.

---

## Important Notes

* Use **PNG images** for best results.
* JPEG compression may damage hidden data.
* The secret image is resized to **100×100** for embedding.
* Wrong password will not reveal data.

---

## Files Needed

* `index.html` (this file)
* `bg.png` (background image used in UI)

---

## Technologies Used

* HTML
* Tailwind CSS
* JavaScript
* Canvas API

---

SteganoS demonstrates how data can be hidden in plain sight using pixel-level manipulation in images.
