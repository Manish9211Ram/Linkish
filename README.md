# 🔗 Linkish – Smart URL Shortener

**Linkish** is a Django-based URL shortening web application that converts long URLs into short, shareable links. It also includes smart/fuzzy URL handling logic for efficient link management and redirection.

---

## 🚀 Features

- 🔗 Shorten long URLs instantly  
- 🎯 Unique short code generation  
- 🔁 Automatic redirection to original URL  
- 🧠 Fuzzy URL handling logic  
- 🗄 Database storage of URLs  
- ⚡ Fast and lightweight Django backend  

---

## 🛠 Tech Stack

| Technology | Use |
|-----------|-----|
| Python | Core language |
| Django | Backend framework |
| SQLite | Database |
| HTML/CSS | Frontend |
| Bootstrap | UI Styling |

---

## 📂 Project Structure
Linkish/
│── fuzzyurl/ # Smart matching logic app
│── shortener/ # URL shortening app
│── manage.py # Django entry point
│── db.sqlite3 # Database

---

## ⚙ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Manish9211Ram/Linkish.git
cd Linkish
```
### 2️⃣ Create Virtual Environment
``` bash
python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows
```
### 3️⃣ Install Dependencies
``` bash
pip install -r requirements.txt
```
### 4️⃣ Run Migrations
``` bash
python manage.py migrate
```
### 5️⃣ Start Server
```bash
python manage.py runserver
```
Open 👉 http://127.0.0.1:8000

## 🧩 How It Works
1.User submits a long URL
2.System generates a short unique code
3.Mapping is stored in the database
4.Opening the short URL redirects to the original link





