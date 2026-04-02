# 🔍 Lost & Found Smart Portal 

A modern web-based application designed to help students report and track lost and found items within a college or community. This system enhances traditional lost-and-found systems by integrating **real-time cloud storage (Firebase)** and **AI-based matching** for better accuracy and automation.

---

## 🚀 Key Features

### 👤 User Authentication

* Secure **student registration & login**
* Uses registration number + password system
* Passwords are securely hashed

---

### 📦 Lost & Found Reporting

* Report **Lost Items**
* Report **Found Items with images**
* Add details like:

  * Item name
  * Description
  * Date
  * Location

---

### ☁️ Firebase Integration (REAL-TIME DATABASE)

* All user registrations stored in **Firebase Firestore**
* Lost/Found items can be stored in cloud
* Real-time sync and scalable backend

---

### 🤖 AI-Based Matching System

* Automatically suggests possible matches between lost & found items
* Generates **AI confidence score**
* Helps users recover items faster

---

### 🔔 Smart Notifications

* Users get notified when:

  * A matching item is found
  * Activity related to their report happens

---

### 🛡️ Role-Based Access

* **Students**:

  * Report items
  * View listings
* **Admin/HOD**:

  * Manage all items
  * View history
  * Moderate reports

---

### 📊 Activity Tracking

* Logs user actions
* Maintains history of reports
* Audit trail for transparency

---

### 🎨 Modern UI

* Clean and responsive interface
* Built using Bootstrap
* User-friendly experience

---

## 🛠️ Technologies Used

### 🔹 Backend

* Python
* Flask
* SQLAlchemy (Local Database)

### 🔹 Cloud & Database

* Firebase Firestore (Cloud Storage)

### 🔹 AI/ML

* Smart matching logic
* (Optional) YOLOv8 for object detection
* (Optional) CLIP model for image-text matching

### 🔹 Frontend

* HTML5
* CSS3 (Bootstrap)
* JavaScript

### 🔹 Security

* Flask-Login
* Password Hashing (Werkzeug / Passlib)

---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Lost2Found.git
cd lost-found-portal
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate   # Windows
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Firebase Setup

* Go to Firebase Console
* Create project
* Enable Firestore Database
* Generate **Private Key JSON**

👉 Place file in project folder:

```
firebase-key.json
```

---

### 5️⃣ Run Application

```bash
python app.py
```

👉 Open in browser:

```
http://127.0.0.1:5000/
```

---

## 🔐 Default Admin Access

| Role  | ID       | Password      |
| ----- | -------- | ------------- |
| Admin | ADMIN001 | adminpassword |
| HOD   | HOD001   | hodpassword   |

⚠️ Change passwords after first login

---

## 📌 Project Highlights

✔ Real-time Firebase integration
✔ AI-based smart matching
✔ Clean UI/UX
✔ Secure authentication
✔ Scalable architecture

---

## 👩‍💻 Developed By

**Ayesha Firdous**

---


