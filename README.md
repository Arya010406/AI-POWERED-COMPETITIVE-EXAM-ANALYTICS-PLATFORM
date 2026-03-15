# 📊 Exam Analytics Platform

An intelligent full-stack exam performance analytics system that helps students analyze test results, identify weak topics, track progress, and generate personalized study plans.

Built for academic projects, hackathons, and learning analytics use-cases.

---

## 🚀 Overview

The Exam Analytics Platform allows students to:

* Take online tests
* Review answers with explanations
* Track subject-wise performance
* Detect weak areas automatically
* Generate study recommendations
* View advanced analytics dashboards

The system uses backend analytics logic to process test submissions and produce actionable insights.

---

## 🧠 Key Features

### 👤 Authentication System

* Student registration & login
* Secure user accounts
* Session-based access control

---

### 📝 Test Engine

* Attempt multiple-choice tests
* Submit answers instantly
* Store test history

---

### 📊 Performance Analytics

* Score tracking across tests
* Topic-wise accuracy analysis
* Weak vs strong subject detection
* Progress trends

---

### 🔎 Mistake Intelligence

* Identify repeated mistakes
* Highlight frequently wrong topics
* Provide question explanations

---

### 📅 Study Plan Generator

* Personalized study recommendations
* Focus on weak subjects
* Structured learning guidance

---

### 📈 Dashboard Insights

* Overall performance summary
* Topic intelligence reports
* Detailed test review pages

---

## 🏗️ Tech Stack

### 🎨 Frontend

* React.js
* Vite
* Context API for authentication
* Axios API client

---

### ⚙️ Backend

* Django
* Django REST Framework
* Custom analytics processing engine
* Management command for seed data

---

### 🗄️ Database

* SQLite (default Django DB)

*(Can be switched to PostgreSQL easily)*

---

## 📂 Project Structure

```
exam2/
│
├── backend/
│   ├── accounts/        # authentication app
│   ├── analytics/       # core exam + ML logic
│   │   ├── ml_engine.py
│   │   ├── models.py
│   │   ├── views.py
│   │   └── seed_data.py
│   └── manage.py
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── api/
│   │   └── context/
│   └── vite.config.js
```

---

## ⚡ Installation Guide

### ✅ 1. Clone Repository

```
git clone <your-repo-url>
cd exam2
```

---

## 🔧 Backend Setup (Django)

```
cd backend
python -m venv venv
venv\Scripts\activate      # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

### 🌱 Optional: Seed Demo Data

```
python manage.py seed_data
```

This creates sample:

* users
* questions
* test datasets

---

## 🎨 Frontend Setup (React + Vite)

Open a new terminal:

```
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 🔗 API Connection

If backend runs on another port, update:

```
frontend/src/api/client.js
```

Change base URL accordingly.

---

## 📸 Main Pages

* Login / Register
* Dashboard
* Take Test
* Test Review
* Test Analytics
* Topic Intelligence
* Study Plan
* Progress Tracking

---

## 🧪 Example Workflow

1. Register account
2. Login
3. Take test
4. Submit answers
5. View analytics dashboard
6. Check weak topics
7. Follow generated study plan

---

## 🎯 Use Cases

* College academic project
* Smart India Hackathon submission
* EdTech prototype
* Learning analytics research
* Student performance monitoring

---

## 🔮 Future Improvements

* AI-generated adaptive questions
* Difficulty-based test selection
* Real-time ML predictions
* Teacher admin dashboard
* Cloud deployment
* Mobile app version

---



## 📜 License

This project is for educational and academic use.

---

⭐ If you like this project, consider starring the repository!
