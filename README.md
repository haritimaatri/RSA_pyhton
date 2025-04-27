# RSA_pyhton
RSA Encryption Fun Project
This project is a fun, educational implementation of the RSA cryptographic algorithm in Python!
**It includes:**
1. Manual prime number generation
2.Extended Euclidean Algorithm (recursive and iterative)
3.Modular Inverse calculation
4.RSA key generation (public and private keys)
5.Message encoding/decoding
6.RSA encryption and decryption
7.Message splitting when the message is too large

✨ Features
- RSA Key Generation: Generate public and private keys from random prime numbers.
- Encryption and Decryption: Encrypt and decrypt numerical messages based on RSA logic.
- Encoding and Decoding: Convert human-readable messages to numeric format and back.
- Handling Large Messages: If the encoded message is too big, it splits the message into smaller chunks for encryption.

📜 How It Works
Prime Generation:
Find two large prime numbers p and q below a given upper bound.

Key Generation:
Generate public and private keys (e, d) using the Extended Euclidean Algorithm.

Encoding:
Convert text messages into numbers using a simple encoding scheme (a=1, ..., z=26, space=27).

Encryption:
Encrypt the numeric message with the public key.

Decryption:
Decrypt the encrypted message with the private key.

Decoding:
Convert the decrypted number back into readable text.

