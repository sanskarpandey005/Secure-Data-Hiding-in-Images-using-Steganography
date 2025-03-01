🖼️ Image Steganography (Encrypt & Decrypt Messages in Images)

📌 Project Overview

This project implements image-based steganography, allowing users to securely hide and retrieve secret messages inside an image using a password. The graphical user interface (GUI) is built with Tkinter, and image processing is handled using OpenCV.

🛠 Features

🔐 Encrypt a Secret Message

Hide messages inside an image without altering its appearance.

Protect hidden messages with a password.

🔓 Decrypt the Message

Extract the hidden message from the image.

Requires the correct password for successful decryption.

🖥️ User-Friendly GUI

Simple and intuitive interface for encryption and decryption.

Responsive and visually appealing design.

📂 Project Structure

📁 Image-Steganography-Project
│-- encrypt_image.py  # GUI for encrypting messages in an image
│-- decrypt_image.py  # GUI for decrypting messages from an image
│-- utils.py          # Helper functions for encryption and decryption
│-- README.md         # Project documentation

🚀 Installation & Setup

1️⃣ Install Dependencies

Ensure Python 3.6+ is installed, then install the required libraries:

pip install opencv-python pillow tkinter

2️⃣ Run the Encryption Script

To encrypt a message into an image:

python encrypt_image.py

Select an image.

Enter the secret message.

Enter a password.

Save the encrypted image.

3️⃣ Run the Decryption Script

To decrypt a message from an image:

python decrypt_image.py

Select the encrypted image.

Enter the correct password.

Retrieve the hidden message.

⚡ Usage Guide

🔹 Encrypting a Message

Launch the encryption tool.

Select an image file.

Enter your secret message.

Set a password for added security.

Click Encrypt → Save the encrypted image.

🔹 Decrypting a Message

Launch the decryption tool.

Select the encrypted image file.

Enter the correct password.

Click Decrypt → The hidden message is displayed.

🛡 Security Considerations

The message is hidden at the pixel level but not strongly encrypted.

For added security, encrypt messages using AES encryption before embedding them.

If an incorrect password is entered, decryption will fail.

📌 Future Enhancements

🔄 Support for multiple image formats (JPEG, PNG, BMP, etc.).

🔑 Stronger encryption methods (AES or RSA) for added security.

📱 Mobile app version using Python-Kivy or Flutter.

🏗 Batch processing for multiple images.

💡 Credits

Developed using:

Python 🐍

OpenCV 📷

Tkinter 🖥️

Pillow (PIL) 🖼️
