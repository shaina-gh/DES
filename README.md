# 🔐 DES Encryption & Decryption in Java

> **A full Java implementation of the DES (Data Encryption Standard) algorithm for secure communication using symmetric encryption.**

---

### 📌 Author
**Shaina**  

---

## 🧠 What is DES?

The **Data Encryption Standard (DES)** is a symmetric-key algorithm that operates on 64-bit blocks using a 64-bit key. It performs 16 rounds of transformation using substitution, permutation, and XOR operations on the plaintext and key to ensure confidentiality.

---

## 🎯 Objective

To implement DES encryption and decryption from scratch using:
- A 64-bit input block
- A 64-bit key
- Manually defined permutation tables and S-boxes
- No external cryptographic libraries

---


## ▶️ How to Compile & Run

```bash
javac DESCommunication.java
java DESCommunication
```

---

## 🧪 Sample Input/Output

### 🔑 Input
```text
Plaintext: ABCDEFGH  
Key:       133457799BBCDFF1 (in hexadecimal)
```

### 🔒 Encrypted Output
```text
Binary Input:     0100000101000010010000110100010001000101010001100100011101001000  
Encrypted Bits:   110100111000111000100101001011101001001011111010101001100100
```

### 🔓 Decrypted Output
```text
Decrypted: ABCDEFGH
```

---

## ✅ Result
The DES algorithm was successfully implemented. The encryption transformed the original message into an unreadable binary format, and the decryption process restored the original plaintext, proving the correctness of the implementation.

---

## ⚠️ Disclaimer
This implementation is designed for educational purposes only. It lacks padding, block chaining modes, and other security mechanisms necessary for real-world deployment.

---

## 🍴 How to Fork This Repository
Want to use or build upon this project? Follow these steps to fork and work with your own copy:

### 🔗 Repository URL
https://github.com/shaina-gh/DES

### 🔄 Step-by-Step Guide
1. Go to https://github.com/shaina-gh/DES

2. Click the "Fork" button in the top-right corner.

3. GitHub will create a copy under your account.

---

## 🧪 After Forking – Get Started Locally
```bash
# 1. Clone your forked repository
git clone https://github.com/YOUR-USERNAME/DES.git

# 2. Navigate into the project directory
cd DES

# 3. Compile and run
javac DESCommunication.java
java DESCommunication
```
---








