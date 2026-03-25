# 📝 Form Validation & Authentication System

A simple and responsive **User Registration and Login System** built using **HTML, CSS, Bootstrap, and JavaScript**.
This project demonstrates **form validation, error handling, and LocalStorage-based authentication**.

---

## 🚀 Features

* ✅ User Registration with validation
* ✅ Login Authentication
* ✅ Data stored in **LocalStorage**
* ✅ Form validation (Username, Email, Password)
* ✅ Error messages using Bootstrap alerts
* ✅ Dashboard page after login
* ✅ Logout functionality
* ✅ Fully responsive UI

---

## 📂 Project Structure

```
project-folder/
│
├── register.html   # Registration Page
├── login.html      # Login Page
├── index.html      # Dashboard Page
├── style.css       # Custom Styling
└── README.md
```

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* Bootstrap 5
* JavaScript (Vanilla JS)
* Browser LocalStorage

---

## 🔑 How It Works

### 1️⃣ Registration Page

* User enters:

  * Username
  * Email
  * Password
  * Confirm Password

* Validation includes:

  * Username must be at least 6 characters
  * No special characters allowed in username
  * Valid email format
  * Password must contain:

    * Minimum 6 characters
    * At least 1 uppercase letter
    * At least 1 number
  * Password and confirm password must match

* After successful validation:

  * Data is stored in **LocalStorage**

---

### 2️⃣ Login Page

* User enters:

  * Email
  * Password

* System checks:

  * If user exists in LocalStorage
  * If email matches
  * If password matches

* On success:

  * Redirects to **Dashboard (index.html)**

---

### 3️⃣ Dashboard (index.html)

* Displays logged-in user name
* Provides logout button
* Redirects to login page if user is not logged in

---

## 💾 LocalStorage Keys Used

```
"user"        → Stores registered user data  
"loginUser"   → Stores current logged-in session  
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open the project folder in VS Code
3. Run using **Live Server**
4. Open `register.html`

---

## ⚠️ Important Note

* This is a **frontend-only project**
* No backend or database is used
* LocalStorage is used for learning/demo purposes only

---

## 📌 Future Improvements

* 🔒 OTP Verification
* 🔥 Firebase / Backend Integration
* 📧 Email verification system
* 🌙 Dark mode UI
* 📱 Advanced responsive design

---

## 🙌 Author

Developed by **Bhushan Ahire**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
