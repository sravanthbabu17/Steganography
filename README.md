# Steganography
📷 Text-to-Image Steganography with AES Encryption
A web application that hides encrypted text inside an image using AES-256 encryption and simple steganography techniques (pixel-level data embedding).
Built with HTML5, Canvas API, CryptoJS, and pure JavaScript.

Live Demo ✨: (https://sravanthbabu17.github.io/Steganography/)

🔥 Features
Encrypt any text with a user-defined key (AES encryption).

Hide the encrypted text into an image (your uploaded one or a generated background).

Download the steganographically altered image (.png).

Load the image back to extract and decrypt the hidden text.

Matrix background effect (cool hacker-style animation).

Mobile-friendly responsive UI.

Custom styled scrollbars and polished dark theme.

🚀 Getting Started
Prerequisites
A modern web browser (Chrome, Firefox, Edge, Safari).

No installation required — everything runs client-side.

Usage
Hide Text into Image

Enter the text you want to hide.

Enter an encryption key (keep it secret! 🔑).

Choose:

Use your own image (upload any image file), or

Use a generated background.

Click "Hide Text in Image".

Download the new image with hidden text.

Extract Hidden Text

Upload the previously saved .png image.

Enter the correct decryption key.

Click "OK" to extract and decrypt the hidden text.

🎨 Screenshots

![Screenshot 2025-04-28 233035](https://github.com/user-attachments/assets/61ac7c3a-cdda-4d76-be04-beccd33eeec9)
![Screenshot 2025-04-28 233104](https://github.com/user-attachments/assets/ba783bc8-b7b6-4300-9050-3642b3f9d4fa)
![Screenshot 2025-04-28 233136](https://github.com/user-attachments/assets/75ebe37b-9042-4543-9116-ee57382e2e3d)



🛡️ Security Notes
AES encryption protects the text before embedding into the image.

However, remember:

Anyone with the image can try brute-forcing if they guess the key easily.

For more serious use, consider stronger key derivation (like PBKDF2, bcrypt).

💡 Future Improvements (Ideas)
Support hiding files, not just text.

Embed encrypted data into JPEG metadata.

Add password strength indicator.

Drag-and-drop image upload.

Animated download success notification.

📜 License
This project is open-source under the MIT License.

✨ Author
Sravanth Babu K
Lokesh A
GitHub:sravanthbabu17
GitHub:lokesh-000

