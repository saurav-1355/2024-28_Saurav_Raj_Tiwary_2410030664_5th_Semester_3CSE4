# 🚀 NeoLnk – AI-Powered URL Shortener

NeoLnk is a modern URL shortening platform built using **Python Flask**, **SQLite**, **HTML/CSS/JavaScript**, and analytics tools. It allows users to shorten long URLs, create custom aliases, generate QR codes, track clicks, and visualize analytics through an interactive dashboard.

## 📌 Features

* 🔗 Shorten long URLs instantly
* ✏️ Custom alias support
* ⏳ Link expiration management
* 📊 Real-time analytics dashboard
* 📱 QR Code generation
* 🌐 Browser and OS tracking
* 📈 Click history visualization
* 🎨 Modern glassmorphism UI design
* ⚡ Fast and lightweight architecture

---

## 🛠️ Technologies Used

### Backend

* Python
* Flask

### Database

* SQLite

### Frontend

* HTML5
* CSS3
* JavaScript

### Libraries

* Flask
* user-agents
* Chart.js
* QRCode.js

### Testing

* Python Unit Testing Framework

---

## 📂 Project Structure

```text
NeoLnk/
│
├── app.py
├── database.py
├── requirements.txt
├── test_app.py
│
├── static/
│   ├── styles.css
│   ├── main.js
│
├── templates/
│   └── index.html
│
└── database/
    └── neolnk.db
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/neolnk.git
cd neolnk
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run Application

```bash
python app.py
```

Application will start on:

```text
http://localhost:5000
```

---

## 🔄 System Workflow

1. User enters a long URL.
2. NeoLnk generates a unique Base62 short code.
3. URL is stored in SQLite database.
4. Short URL is created.
5. User can share or generate QR code.
6. Every click is logged.
7. Analytics dashboard updates in real time.

---

## 📊 Analytics Dashboard

The dashboard provides:

* Total Click Count
* Browser Usage Statistics
* Operating System Statistics
* Click History Trends
* QR Code Preview

---

## 🧪 Testing

Run automated tests using:

```bash
python -m unittest test_app.py
```

The project includes tests for:

* Base62 code generation
* URL validation
* Alias collision handling
* Link expiration
* Redirection functionality
* Analytics tracking

---

## 🎯 Project Objectives

* Build a complete URL shortening platform
* Implement custom aliases
* Enable click tracking and analytics
* Generate QR codes automatically
* Provide a responsive user interface
* Demonstrate Flask and database integration

---

## 🔮 Future Enhancements

* User Authentication
* Role-Based Access Control
* Cloud Deployment
* Custom Domains
* Multi-user Support
* AI-based Traffic Prediction
* Advanced Analytics Reports

---

## 👨‍💻 Author

**Saurav Raj Tiwary**

B.Tech Computer Science & Engineering
IILM University, Greater Noida

Roll No: 2410030664

---

## 📜 License

This project is developed for educational and internship purposes. Feel free to modify and extend it for learning and research.
