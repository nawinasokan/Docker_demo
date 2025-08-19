# 🐳 nawinasokan-docker_demo

This project demonstrates running a **Django web application** inside **Docker**.  
It contains a simple Django app (`welcome_app`) with a basic HTML template (`welcome.html`) served through Docker.


---

## 🚀 Features

- Django project containerized with **Docker**
- Lightweight setup with `requirements.txt`
- Basic HTML page (`welcome.html`) rendered via `welcome_app`
- Clean `.dockerignore` to avoid bloating image

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Django**
- **Docker**

---

## ⚙️ Setup & Run

### 1. Clone this repository
  git clone repo-docker_demo.git
  cd nawinasokan-docker_demo/welcome_project


### 2. Build Docker image
  docker build -t django-docker-demo .

### 3. Run the container
  docker run -d -p 8000:8000 django-docker-demo

### 4. Open in browser
  Visit http://localhost:8000 to see the Django welcome page.

## 📬 Contact

- **Name:** Nawin Asokan  
- **Role:** Full Stack Python Developer  
- **Email:** [nawinasokan16@gmail.com]  
- **GitHub:** [https://github.com/nawinasokan] 
- **LinkedIn:** [https://linkedin.com/in/naiwn-a-dev]  