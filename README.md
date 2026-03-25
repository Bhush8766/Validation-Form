# 🔐 OTP Verification System (Frontend Project)

A simple and responsive **User Authentication System** built using **HTML, CSS, Bootstrap, and JavaScript**.
This project includes **Registration, Login, Validation, and LocalStorage-based authentication**.

---

## 🚀 Features

* ✅ User Registration with validation
* ✅ Login Authentication
* ✅ Data stored in **LocalStorage**
* ✅ Error handling with Bootstrap alerts
* ✅ Dashboard (index page) after login
* ✅ Logout functionality
* ✅ Responsive UI using Bootstrap

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

### 1️⃣ Registration

* User enters:

  * Username
  * Email
  * Password
  * Confirm Password
* Validation checks:

  * Username length (min 6)
  * No special characters
  * Valid email format
  * Strong password (uppercase + number)
* Data is stored in **LocalStorage**

---

### 2️⃣ Login

* User enters email & password
* Data is verified from LocalStorage
* If valid → Redirect to Dashboard
* If invalid → Error message shown

---

### 3️⃣ Dashboard (index.html)

* Displays logged-in user name
* Logout button available
* Redirects to login if no user session

---

## 💾 LocalStorage Keys Used

```
"user"        → Stores registered user data  
"loginUser"   → Stores logged-in user session  
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open project folder in VS Code
3. Run using **Live Server**
4. Open `register.html`

---

## ⚠️ Note

* This is a **frontend-only project**
* No backend or database is used
* LocalStorage is used for learning/demo purposes

---

## 📌 Future Improvements

* 🔒 OTP Verification system
* 🔥 Firebase Authentication
* 🛒 Full E-commerce integration
* 🌙 Dark Mode UI
* 📱 Mobile optimization

---

## 🙌 Author

Developed by **Bhushan Ahire**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
