<div align="center">

# Classic Cryptography Algorithms

### Implementation of historical encryption ciphers for cryptanalysis study.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Security](https://img.shields.io/badge/Security-Cryptanalysis-red?style=for-the-badge)

[View Code] • [Report Bug] • [Request Feature]

</div>

---

## Overview

This repository contains the implementation and mathematical analysis of **Classic Encryption Algorithms**, developed to understand the foundations of modern information security.

The project explores symmetric encryption techniques, focusing on polyalphabetic and substitution ciphers. It serves as a practical study of how historical methods laid the groundwork for contemporary cryptosystems like AES and RSA.

**Key Concepts Applied:**
* **Modular Arithmetic:** fundamental for shift ciphers like Caesar and Vigenère.
* **Linear Algebra:** Matrix operations (determinants and modular inverses) applied in the Hill Cipher.
* **Bitwise Operations:** XOR logic implementation for the Vernam Cipher (One-Time Pad).

---

## Academic Context

This project was developed for the **Cryptography** course at the **National Autonomous University of Mexico (UNAM)**.

| **Course Information** | **Details** |
| :--- | :--- |
| **University** | Universidad Nacional Autónoma de México (UNAM) |
| **Faculty** | **Faculty of Engineering** |
| **Course** | Cryptography |
| **Professor** | Dr. Alfonso Francisco De Abiega L Eglisse |
| **Semester** | 2026-1 |

---

## 🛠️ Implemented Algorithms

The repository includes the source code for the following ciphers, using **Python** for high-level logic and **C** for memory-efficient processing:

| Algorithm | Language | Description | Type |
| :--- | :---: | :--- | :--- |
| **Caesar Cipher** | **C** | Shift cipher based on modular arithmetic `(x + k) mod 26`. | Substitution |
| **Vigenère Cipher** | **C** | Polyalphabetic substitution using a keyword to shift letters. | Polyalphabetic |
| **Hill Cipher** | **Python** | Matrix-based cipher using linear algebra `(K * P) mod 26`. | Block Cipher |
| **Playfair Cipher** | **Python** | Digraph substitution using a 5x5 key matrix. | Substitution |
| **Vernam Cipher** | **Python** | The theoretical "unbreakable" cipher using XOR operations. | Stream Cipher |

---

## Getting Started

### Prerequisites
* **Python 3.x** (for `.py` files)
* **GCC Compiler** (for `.c` files)
* **NumPy** (required for Hill Cipher matrix operations):
  ```bash
  pip install numpy
