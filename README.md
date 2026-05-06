# CY9-Decode - Code Decoder

A dark-themed GUI application to decode and deobfuscate code in multiple programming languages.

## Supported Languages
- Python
- JavaScript
- Node.js
- Lua

## Features
- **Base64 Decoding** - Decode Base64 encoded strings
- **URL Decoding** - Decode URL encoded strings
- **Hex Decoding** - Convert hexadecimal to text
- **Code Beautify** - Format and beautify minified code
- **Deobfuscation** - Basic deobfuscation for obfuscated code
- **Encrypt with Password** - Encrypt code with a secret password
- **Decrypt with Password** - Decrypt code using the password
- **Load/Save Files** - Import and export code files
- **Dark Mode UI** - Easy on the eyes

## How to Run

### Option 1: Run Python Script
```bash
python cy9_decode.py
```

### Option 2: Build .exe
```bash
build_exe.bat
```
The .exe file will be in the `dist` folder.

## Usage
1. Select the programming language
2. Choose the operation type (Decode/Encrypt/Decrypt)
3. Enter password if using Encrypt/Decrypt
4. Paste or load your code
5. Click "Process"
6. Save the output if needed

### Encryption Example:
1. Select "Encrypt" operation
2. Enter a strong password
3. Paste your code
4. Click "Process"
5. Save the encrypted output

### Decryption Example:
1. Select "Decrypt" operation
2. Enter the SAME password used for encryption
3. Paste the encrypted code
4. Click "Process"
5. Your original code will appear

## Requirements
- Python 3.6+
- Pillow (for logo display)
- PyInstaller (for building .exe)

## Installation
```bash
pip install pillow
```

---
**CY9-Decode** - Decode all programming languages
