# 🔐 Strong Password Generator

A modern, mobile-friendly **single-page password generator** built with **HTML, Bootstrap 5, and JavaScript**. The app helps users generate secure passwords with real-time strength feedback and a clean, app-like user interface.

---

## ✨ Features

* ✅ Generate strong random passwords
* 📏 Adjustable password length (6–32 characters)
* 🔠 Options for:

  * Uppercase letters
  * Lowercase letters
  * Numbers
  * Symbols
* 📊 Real-time password strength meter
* 📋 Copy-to-clipboard with validation
* 🚫 Prevents copying empty passwords
* 📱 Mobile-app-like UI (responsive & touch-friendly)
* 🎨 Bootstrap 5 styling with modern design

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Custom styling
* **Bootstrap 5** – Responsive UI components
* **JavaScript (Vanilla)** – Password logic & validation

---

## 🚀 How It Works

1. Select password length using the slider
2. Choose character types (uppercase, lowercase, numbers, symbols)
3. Click **Generate Password**
4. View password strength instantly
5. Click **Copy** to copy the generated password

> ⚠️ The password field is read-only to prevent manual entry and improve security.

---

## 🔐 Password Strength Logic

The strength meter evaluates:

* Password length
* Presence of uppercase letters
* Presence of lowercase letters
* Presence of numbers
* Presence of symbols

Strength levels:

* Very Weak
* Weak
* Medium
* Strong
* Very Strong

---

## 📂 Project Structure

```
password-generator/
│
├── index.html   # Single-page application (HTML, CSS, JS)
├── README.md    # Project documentation
```

---

## 🧪 Validation & Error Handling

* ❌ Cannot generate a password if no character option is selected
* ❌ Cannot copy when password field is empty
* ✅ In-app Bootstrap alerts instead of JavaScript popups

---

## 📱 Mobile Support

* Fully responsive layout
* Touch-friendly controls
* App-like centered card design

---

## 🔧 Customization

You can easily:

* Integrate into a **PHP / SecureLearn project**
* Add **show/hide password toggle**
* Enforce **minimum strength before copying**
* Save password history using `localStorage`
* Convert to a **PWA (Progressive Web App)**

---

## 📜 License

This project is open-source and free to use for personal or educational purposes.

---

## 👤 Author

Created by **Amos Ngeno**

---

✅ *Secure passwords made simple.*
