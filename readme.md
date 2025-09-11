# Cybersecurity Projects

A collection of simple cybersecurity-related Python scripts for educational and demonstration purposes.

## Project Structure

- [`encrypt-decrypt-image.py`](encrypt-decrypt-image.py): Encrypt and decrypt images using a simple key-based pixel manipulation.
- [`encrypt-decrypt-msg.py`](encrypt-decrypt-msg.py): Encrypt and decrypt messages using the Caesar Cipher algorithm.
- [`keylogger.py`](keylogger.py): A basic keylogger that logs keystrokes to a file.
- [`packets.py`](packets.py): Capture and display network packets using Scapy.
- [`password-complexity-checker.py`](password-complexity-checker.py): Check the complexity and strength of passwords.

---

## Usage

### 1. Image Encryption/Decryption

Encrypt or decrypt an image file using a numeric key.

```sh
python encrypt-decrypt-image.py
```

### 2. Message Encryption/Decryption

Encrypt or decrypt a text message using the Caesar Cipher.

```sh
python encrypt-decrypt-msg.py
```

### 3. Keylogger

Logs all keystrokes to `keylog.txt`. **For educational use only.**

```sh
python keylogger.py
```

### 4. Packet Sniffer

Capture and display network packets (requires administrator/root privileges).

```sh
python packets.py
```

### 5. Password Complexity Checker

Check the strength of a password and get feedback.

```sh
python password-complexity-checker.py
```

---

## Requirements

- Python 3.x
- [Pillow](https://pypi.org/project/Pillow/) (`pip install pillow`) for image encryption
- [numpy](https://pypi.org/project/numpy/) (`pip install numpy`) for image encryption
- [scapy](https://pypi.org/project/scapy/) (`pip install scapy`) for packet sniffing
- [pynput](https://pypi.org/project/pynput/) (`pip install pynput`) for keylogger

---

## Disclaimer

These scripts are for educational purposes only. Do not use them for malicious activities. Always have permission before running network or keylogging tools on any