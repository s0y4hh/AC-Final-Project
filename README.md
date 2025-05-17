# 🔐 CipherNest 🔐

#### BSCS 3A

#### May 2025

---

## 👥 Members:
1. Jayp Bazar *(Leader / Programmer)*
2. Mark Wayne Cleofe *(Programmer)*
3. Quennie Magno *(Designer / Documentation)*

---

## 📘 Introduction

CipherNest is an interactive project designed to allow users to explore and experiment with fundamental cryptographic algorithms. The purpose of CipherNest is to provide a hands-on learning experience for students and enthusiasts interested in cryptography, encryption, and security. Users can interact with different cryptographic methods, understand the process of encryption and decryption, and see how various algorithms function in real-time.

---

## 🎯 Project Objectives

1. To provide an educational platform for understanding the basics of cryptography.
2. To allow users to experiment with multiple cryptographic algorithms (symmetric, asymmetric, and hashing).
3. To demonstrate practical implementations of cryptographic techniques on both text and files.
4. To visualize the process and output of cryptographic operations for better comprehension.
5. To encourage further learning and experimentation in the field of cybersecurity.

---

## 🧠 Discussions

### Application Architecture & UI

CipherNest features a user-friendly graphical interface that allows seamless switching between different cryptographic algorithms. The application is built using Python Flask, ensuring cross-platform compatibility and ease of use.

### Implemented Cryptographic Algorithms

#### 1. Caesar Cipher (Symmetric)
- **Type:** Symmetric Key Encryption
- **Background:** One of the simplest and most widely known encryption techniques, where each letter in the plaintext is shifted a certain number of places down the alphabet.
- **How it Works:** Each letter of the input is replaced by a letter some fixed number of positions down the alphabet.
- **Libraries Used:**
- **Integration:** Allows user to set the shift value and encrypt/decrypt text.

#### 2. Vigenère Cipher (Symmetric)
- **Type:** Symmetric Key Encryption
- **Background:** Uses a keyword to shift letters of the plaintext, creating a polyalphabetic cipher.
- **How it Works:** Each letter of the plaintext is shifted by the corresponding letter of the keyword.
- **Integration:** User inputs a keyword to perform encryption/decryption.

#### 3. RSA (Asymmetric)
- **Type:** Asymmetric Key Encryption
- **Background:** A public-key cryptosystem widely used for secure data transmission.
- **How it Works:** Uses two keys (public and private) for encryption and decryption.
- **Integration:** Key generation, encryption, and decryption of text or files.

#### 4. SHA-256 (Hash)
- **Type:** Hash Function
- **Background:** Cryptographic hash function producing a 256-bit hash value, commonly used in security applications.
- **How it Works:** Converts input data into a fixed-size string of bytes.
- **Integration:** Users can hash text or files and compare hash outputs.

---

## 🧪 Sample Run / Outputs

### Caesar Cipher
- **Encryption Example:**  
  Plaintext: HELLO  
  Shift: 3  
  Ciphertext: KHOOR

### Vigenère Cipher
- **Encryption Example:**  
  Plaintext: HELLO  
  Keyword: KEY  
  Ciphertext: RIJVS

### RSA
- **Example:**  
  Plaintext: HELLO  
  Encrypted (public key): [ciphertext]  
  Decrypted (private key): HELLO

### SHA-256
- **Example:**  
  Input: HELLO  
  Hash Output: 2cf24dba5fb0a...
---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jaypbazar/AC-Final-Project.git
   cd AC-Final-Project
   ```

2. **Install dependencies:**  
   [`pip install -r requirements.txt` or `npm install`]

3. **Run the application:**  
   [`python main.py` or `npm start`]

---

## 🤝 Contributions

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss what you would like to change.

---

## 📜 License

[MIT License](LICENSE)

---

## 📧 Contact

For questions or suggestions, please open an issue or contact any of the members listed above.
