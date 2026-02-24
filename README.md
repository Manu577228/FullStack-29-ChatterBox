# 🚀 ChatterBox – Real-Time Chat Application  

A modern **real-time chat application** built using **Spring Boot, Thymeleaf, WebSocket (SockJS + STOMP), and Bootstrap 5**, enabling seamless live messaging with a responsive UI.

---

## 🌐 Tech Stack

- **Backend:** Spring Boot  
- **Frontend:** Thymeleaf + Bootstrap 5  
- **Realtime Communication:** WebSocket  
- **Protocol:** STOMP  
- **Fallback Support:** SockJS  
- **Build Tool:** Maven  

---

## ⚡ Features

- 🔥 Real-time message broadcasting  
- 👥 Multiple users support  
- 💬 Instant UI updates without refresh  
- 📱 Fully responsive design (Bootstrap 5)  
- 🔌 WebSocket fallback using SockJS  
- 🧠 Clean MVC architecture  

---

## 🏗️ Project Structure

```
src/main/java/com/chat/app
│
├── config
│   └── WebSocketConfig.java
│
├── controller
│   └── ChatController.java
│
├── model
│   └── ChatMessage.java
│
└── AppApplication.java

src/main/resources
│
├── templates
│   └── chat.html
│
└── application.properties
```

---

## 🔄 How It Works

1. Client connects to `/chat` WebSocket endpoint  
2. STOMP protocol sends messages to `/app/sendMessage`  
3. Spring Boot message broker broadcasts to `/topic/public`  
4. All subscribed clients receive messages instantly  

---

## ▶️ Run Locally

```bash
# Clone the repository
git clone https://github.com/Manu577228/FullStack-29-ChatterBox.git

# Navigate into project
cd FullStack-29-ChatterBox

# Run the application
./mvnw spring-boot:run
```

Then open:

```
http://localhost:8080
```

---
---

## 🚀 Future Enhancements

- 🔐 Authentication & User Login  
- 🗂️ Private Chat Rooms  
- 📎 File Sharing  
- 📨 Message Persistence (Database)  
- ☁️ Cloud Deployment  

---

## 👨‍💻 Author

**Bharadwaj (Manu577228)**  
- GitHub: https://github.com/Manu577228  
- YouTube: https://youtube.com/@code-with-Bharadwaj  

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and share it with others!

---

> Built with ❤️ using Spring Boot & WebSockets
