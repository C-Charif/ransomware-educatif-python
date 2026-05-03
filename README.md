# 🔐 Project: Educational Ransomware in Python

## 📌 Description

This project was developed as part of a cybersecurity course.
Its goal is to understand how ransomware works for educational purposes only.

⚠️ **Important:**
This project is strictly educational and must be executed in a controlled environment.

---

## 🎯 Objectives

* Understand symmetric encryption
* Manipulate files using Python
* Implement an encryption/decryption system
* Study ransomware mechanisms

---

## 🛠️ Technologies Used

* Python 3
* `cryptography` library (Fernet)

---

## 📂 Project Structure

```
ransomware/
│── rans.py        # Encryption script
│── decrypt.py     # Decryption script
│── theKey.key     # Automatically generated key
│── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone  https://github.com/C-Charif/ransomware-educatif-python.git
cd ransomware-educatif-python
```

### 2. Install dependencies

```bash
pip install cryptography
```

---

## ▶️ Usage

### 🔒 Encryption

```bash
python rans.py
```

### 🔓 Decryption

```bash
python decrypt.py
```

---

## 🔐 How It Works

* Generates an encryption key
* Encrypts files in the directory
* Stores the key in `theKey.key`
* Decrypts files using authentication (secret passphrase)

---

## ⚠️ Disclaimer

This project is for educational purposes only.
Any malicious use is illegal and unethical.

---

## 👨‍💻 Author

* Chaima Charif

---

## 📚 Conclusion

This project helps in understanding ransomware attacks and the techniques used to defend against them.
