# SaishTask App

SaishTask is a full-stack task management application built with Spring Boot and React.  
It helps users create task lists, add tasks, track progress, and manage daily work efficiently.

---

## Tech Stack

### Backend
- Java 21
- Spring Boot
- JPA Hibernate
- PostgreSQL / Docker
- Maven

### Frontend
- React (Vite + TypeScript)
- Axios
- Tailwind CSS
- NextUI Components

---

## Project Structure

saish-task-app/
   ├── backend/
   │     └── tasks  (Spring Boot backend)
   ├── frontend/
         └── tasks-fe  (React frontend)

---

## 📸 Screenshots

### Homepage UI
![Homepage](frontend/screenshots/homepageSaishTask.png)

### ➕ Create Task List Modal
![Create Task List](frontend/screenshots/create-tasklist.png)

---

## 🔧 Setup Instructions

### Backend
cd backend/tasks
mvn clean install
docker-compose up -d

### Frontend
cd frontend/tasks-fe
npm install
npm run dev

---

## 👨‍💻 Developed By
### Saish Sanas
