# 📒 Address Book

**Address Book** is a secure web application that allows users to manage and store personal addresses. Each user can **create** and **view** addresses, while ensuring that entries created by others **cannot be modified or deleted**, providing complete ownership control.

---

## 🌐 Live Demo

👉 [Address Book](https://address-book-mv3s.onrender.com/alladdress)

---

## 📦 Features

- 👤 **User Authentication**
  - Secure Login, Signup, and Logout
  - Flash messages for user feedback (login success, invalid credentials, etc.)
  
- 📚 **Address Management**
  - Only the logged-in user (owner) can create an address
  - Entries cannot be modified or accessed by other users
  - Stores important contact details:
    - Name & Address
    - (Optional) Personal note
    - Relationship
    - Email ID
    - Status on Social Media

- 🔐 **Security**
  - Protected routes (only authenticated users can access)
  - Sessions and authentication managed with Passport.js

---

## 🛠 Tech Stack

### 🌐 Frontend
- **HTML**
- **CSS**
- **Bootstrap** – For responsive UI design

### 🖥 Backend
- **Node.js** – Runtime environment
- **Express.js** – Server-side framework
- **Passport.js** – Authentication and session handling

### 💾 Database
- **MongoDB** – NoSQL database to store users and addresses

## 💡 How It Works

- Users sign up and securely log in
- They can add address entries, which are stored in MongoDB
- Each address is linked to its creator
- Other users cannot view, edit, or delete another person’s data
- Flash messages notify users about successful actions and errors

