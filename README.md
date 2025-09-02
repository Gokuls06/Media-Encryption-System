📖 README – Media Encryptor System

🔒 Overview

The Media Encryptor System is a Python-based desktop application that allows users to securely encrypt and decrypt files using a password. It uses AES (Advanced Encryption Standard) in CBC mode with a unique salt and IV for each file, ensuring high security.

The application features a Tkinter GUI for ease of use, allowing users to:

Encrypt any file with a password.

Decrypt previously encrypted files with the same password.

Toggle password visibility.

Automatically open decrypted files after successful decryption.

⚡ Features

🔐 AES-256 Encryption (derived from password using PBKDF2-HMAC-SHA256).

🖥️ User-friendly GUI built with Tkinter.

👁️ Password visibility toggle (Show/Hide).

📂 File selection dialogs for both encryption and decryption.

📑 Error handling & alerts for missing files, incorrect passwords, or unexpected issues.

🚀 Cross-platform support (Windows, Linux, macOS).

🛠️ Requirements

Ensure you have the following installed:

Python 3.8+

Tkinter (usually pre-installed with Python)

Cryptography library