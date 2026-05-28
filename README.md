# Docker Frontend-Backend-DB Application

A full-stack 3-tier web application containerized using Docker and Docker Compose.

## 📌 Project Overview

This project demonstrates deployment of a complete 3-tier architecture application using:

* **Frontend** → React.js
* **Backend** → Node.js + Express.js
* **Database** → MongoDB
* **Containerization** → Docker & Docker Compose

All services run in separate containers and communicate through Docker networks.

---

## 🏗️ Architecture

```text
User → Frontend (React)
            ↓
      Backend API (Node.js/Express)
            ↓
        MongoDB Database
```

---

## 📂 Project Structure

```bash
docker-frontend-backend-db-master/
│
├── frontend/          # React frontend
├── backend/           # Node.js backend
├── docker-compose.yml
├── README.md
```

---

## ⚙️ Technologies Used

* React.js
* Node.js
* Express.js
* MongoDB
* Docker
* Docker Compose

---

## 🚀 Features

* Multi-container Docker setup
* Frontend and backend separation
* MongoDB integration
* Docker networking
* Easy deployment using Docker Compose

---

## 🐳 Docker Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2️⃣ Build and Start Containers

```bash
docker compose up --build
```

OR

```bash
docker-compose up --build
```

---

## 🌐 Application Ports

| Service  | Port  |
| -------- | ----- |
| Frontend | 3000  |
| Backend  | 3001  |
| MongoDB  | 27017 |

---

## 🔍 Verify Running Containers

```bash
docker ps
```

---

## 🛑 Stop Containers

```bash
docker compose down
```

---

## 📸 Output

After successful deployment:

* Frontend → `http://localhost:3000`
* Backend API → `http://localhost:3001`

---

## 📦 Docker Commands Used

### Build Image

```bash
docker build -t app-name .
```

### Run Container

```bash
docker run -d -p 3000:3000 app-name
```

### Check Containers

```bash
docker ps
```

### View Logs

```bash
docker logs <container-id>
```

---

## 🔧 Challenges Faced

* Docker networking between containers
* Port mapping issues
* MongoDB container connection
* Docker Compose configuration
* Container build errors

---

## 📚 Learning Outcomes

Through this project, I learned:

* Docker fundamentals
* Containerization concepts
* Docker Compose
* Multi-container deployment
* AWS EC2 deployment basics
* Docker networking
* Image and container management

---

## 👨‍💻 Author

**Rishant Raj**

Final Year B.Tech CSE Student
Interested in DevOps, Cloud & Software Development

---

## ⭐ Future Improvements

* Deploy using Kubernetes
* Add Nginx reverse proxy
* CI/CD pipeline integration
* AWS ECS deployment
* SSL/HTTPS configuration
