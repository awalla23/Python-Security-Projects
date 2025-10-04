🔒 Python File Encryptor / Decryptor

A simple Python-based file encryption and decryption tool with a GUI built using Tkinter.
This project demonstrates how to apply AES encryption (via Fernet from the cryptography library) to securely protect files with an easy-to-use interface.

🚀 Features

Generate Key → Creates a new Fernet AES key (fernet.key) for encryption/decryption.

Encrypt File → Select any file, and the tool will generate an encrypted version (filename.ext.enc).

Decrypt File → Select an encrypted file and recover the original (filename.ext.dec).

User-Friendly Interface → Simple Tkinter UI for non-technical users.

Secure Encryption → Uses Fernet (AES + HMAC) ensuring confidentiality & integrity.
