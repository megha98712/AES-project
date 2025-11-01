# AES-project

🔐 Data Security Using AES (Advanced Encryption Standard)
📘 Overview

This project demonstrates the implementation of AES (Advanced Encryption Standard) encryption algorithm to secure sensitive data.
It ensures confidentiality and integrity of the data during transmission or storage by converting plaintext into ciphertext using a symmetric key.

AES is a block cipher that operates on 128-bit data blocks with key sizes of 128, 192, or 256 bits.
It is widely used in network security, cloud data protection, and secure communication systems.

🧩 Features

🔒 Secure AES encryption & decryption (128/192/256-bit keys)

🧠 Symmetric key cryptography

⚡ Fast and efficient encryption process

📁 Supports both text and file encryption

💻 Simple and clean user interface (CLI or GUI)

⚙️ How It Works

User Input: Enter text or upload a file to encrypt.

Secret Key: Provide a secret key shared between sender and receiver.

Encryption: Data is encrypted using AES algorithm and converted into unreadable ciphertext.

Decryption: Using the same key, ciphertext is converted back to readable plaintext.

🔁 AES Process Steps

SubBytes → ShiftRows → MixColumns → AddRoundKey (Encryption)

Inverse operations (for Decryption)


Depending on key length:
1.AES-128 → 10 Rounds
2.AES-192 → 12 Rounds
3.AES-256 → 14 Rounds
