# 🔐 Password Checker

This is a Python project that checks the strength of a password and verifies whether it has been exposed in any known data breaches using the **Have I Been Pwned API**.

---

## 📌 Features

- Checks password against public data breaches using the Pwned Passwords API
- Provides information about password exposure count
- Ensures user privacy by using **k-anonymity**
- Simple and beginner-friendly code

---

## 🚀 How It Works

1. **Take user input** for a password (or multiple).
2. **Hashes the password** using SHA-1.
3. **Only the first 5 characters** of the hash are sent to the API.
4. The API returns a list of matching suffixes.
5. If a match is found, it tells you **how many times** your password has been exposed.

---

## 🛠️ Technologies Used

- Python 3
- `requests` module
- SHA-1 hashing
- Pwned Passwords API (by Troy Hunt)

---

## 📂 Project Structure


