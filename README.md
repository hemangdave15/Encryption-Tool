# Encryption Tool

## Overview
This Python project implements various encryption techniques and provides a graphical user interface (GUI) using Tkinter. Users can input text and choose from multiple encryption methods to see the encrypted result.

## Features
- **Caesar Cipher**
- **SHA-256 Hashing**
- **Rail Fence Cipher**
- **Vigenere Cipher**
- **Playfair Cipher**
- **Hill Cipher**

## Requirements
- Python 3.x
- NumPy (`pip install numpy`)
- Tkinter (included with Python)

## Installation
1. Clone the repository or download the script.
2. Install NumPy if not already installed:
   ```bash
   pip install numpy
   ```
3. Run the script:
   ```bash
   python encryption_tool.py
   ```

## Usage
1. Enter the text you want to encrypt.
2. Provide a key or shift value where required.
3. Select the encryption method from the dropdown menu.
4. Click "Encrypt" to view the encrypted text in a pop-up message.

## Encryption Methods Explained
### 1. Caesar Cipher
A simple substitution cipher that shifts characters by a fixed number.

### 2. SHA-256 Hashing
A cryptographic hashing algorithm that generates a fixed-size hash value.

### 3. Rail Fence Cipher
A transposition cipher that arranges text in a zigzag pattern and reads it row-wise.

### 4. Vigenere Cipher
A polyalphabetic substitution cipher using a repeating key to shift letters.

### 5. Playfair Cipher
A digraph substitution cipher using a 5x5 matrix for encryption.

### 6. Hill Cipher
A cipher that uses matrix multiplication for encryption.

## Example Usage
### Caesar Cipher Example
**Input:** `HELLO`, Shift: `3`  
**Output:** `KHOOR`  

### SHA-256 Example
**Input:** `HELLO`  
**Output:** `2cf24dba5fb0a30e26e83b2ac5b9e29e1b161e5c1fa7425e73043362938b9824`  

### Playfair Cipher Example
**Input:** `HELLO`, Key: `KEYWORD`  
**Output:** (Encrypted Text)  

### Hill Cipher Example
**Input:** `ACT`, Key Matrix: `6 24 1;13 16 10;20 17 15`  
**Output:** `POH`  

## License
This project is open-source and available for modification and distribution.

## Contributors
Developed by [Your Name].
