# Real-Time-Chat-Application
# 💬 Real-Time Chat Application (Spring Boot + WebSocket)

A real-time chat application built using **Spring Boot and WebSocket**, allowing multiple users to communicate instantly. The project is fully **containerized using Docker** and deployed on the cloud using **Render**.

---

## 🚀 Live Demo

👉 https://real-time-chat-application-f90o.onrender.com

---

## 📌 Features

* ⚡ Real-time messaging using WebSocket
* 👥 Multi-user chat support
* 🌐 Browser-based chat interface
* 🔄 Instant message broadcasting
* ☁️ Deployed on cloud (Render)
* 📦 Dockerized for consistent deployment

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Real-Time Communication:** WebSocket (STOMP protocol)
* **Frontend:** HTML, CSS, JavaScript
* **Build Tool:** Maven
* **Containerization:** Docker
* **Deployment:** Render

---

## 📂 Project Structure

```
chat-app/
│── Dockerfile
│── app/
│    ├── src/
│    ├── target/
│    ├── pom.xml
```

---

## ⚙️ How It Works

* WebSocket establishes a persistent connection between client and server
* Messages are sent to a central endpoint
* Server broadcasts messages to all connected users in real-time

---

## 🐳 Docker Setup

### Build Docker Image

```
docker build -t chat-app .
```

### Run Container

```
docker run -p 8080:8080 chat-app
```

---

## 🧪 Run Locally

1. Clone the repository:

```
git clone https://github.com/himanshu2611/Real-Time-Chat-Application.git
```

2. Navigate to project:

```
cd chat-app/app
```

3. Build and run:

```
./mvnw.cmd clean package
java -jar target/*.jar
```

4. Open in browser:

```
http://localhost:8080/chat.html
```

---

## 📸 Screenshots

<img width="1920" height="1080" alt="Screenshot (1543)" src="https://github.com/user-attachments/assets/26730655-e852-4430-86b8-bb70103ed9f2" />


<img width="1920" height="1080" alt="Screenshot (1544)" src="https://github.com/user-attachments/assets/a125d1f2-69b0-48fa-a13b-64de31fd589e" />

---

## 💡 Future Improvements

* 🔐 User authentication (JWT)
* 💾 Store chat history (MongoDB)
* 🚀 Scalability with Redis
* 🎨 Improved UI/UX

---

## 👨‍💻 Author

**Himanshu Tiwari**

* GitHub: https://github.com/himanshu2611

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
