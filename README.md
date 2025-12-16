# 🎥 Clueso.io Clone – Full Stack Assignment

A simplified **full-stack clone of Clueso.io**, built as an assignment project using **Spring Boot** and **vanilla frontend technologies**.  
This project demonstrates REST API development, frontend–backend integration, and basic SaaS-style functionality.

---

## 🚀 Features

- Add video metadata (title & description)
- View list of uploaded videos
- RESTful API using Spring Boot
- Frontend integration using Fetch API
- Clean and modular project structure
- Easy to extend with authentication, file upload, or AI features

---

## 🛠 Tech Stack

### Backend
- Java 17
- Spring Boot
- REST API
- Maven

### Frontend
- HTML
- CSS
- JavaScript (Vanilla)

---

## 📁 Project Structure

clueso-clone/
│
├── backend/
│ ├── src/main/java/com/example/cluesoclone
│ │ ├── controller/
│ │ ├── model/
│ │ └── CluesoCloneApplication.java
│ ├── src/main/resources/
│ │ └── application.properties
│ └── pom.xml
│
├── frontend/
│ ├── index.html
│ ├── style.css
│ └── script.js
│
└── README.md


---

## ▶️ How to Run the Project

### 1️⃣ Run Backend (Spring Boot)

1. Open **Eclipse / IntelliJ**
2. Import the `backend` folder as a **Maven project**
3. Run:


CluesoCloneApplication.java

4. Backend will start at:


http://localhost:8080


---

### 2️⃣ Run Frontend

1. Open:


frontend/index.html

in any modern browser
2. Make sure backend is running
3. Add video title & description and submit

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|------|---------|------------|
| POST | `/api/videos` | Add video metadata |
| GET  | `/api/videos` | Fetch all videos |

---

## 📌 Future Enhancements

- Video file upload support
- AI transcription & voiceover
- User authentication (Spring Security)
- Database integration (MySQL)
- Admin dashboard

---

## 🎯 Purpose of This Project

This project was developed as an **assignment** to demonstrate:
- Full-stack development skills
- REST API creation
- Frontend–backend communication
- Clean code and folder structure

---

## 👨‍💻 Author

**R Rohit**  
Java Full Stack Developer  

---

## 📄 License

This project is for educational and assignment purposes only.
