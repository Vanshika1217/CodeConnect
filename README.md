# CodeConnect — Real-Time Collaborative Coding Platform

CodeConnect is a real-time collaborative coding platform that allows developers to write, edit, and execute code together. It features live markers, user presence indicators, code-sharing links, and secure Docker-based execution. The platform is fully monitored using Prometheus and Grafana, ensuring performance, reliability, and observability.

---

## ✨ Features

- **Real-Time Collaboration**  
  Multiple users can code together in a shared editor with instant synchronization.

- **Live Editing Markers**  
  See exactly *who* is typing and *which part* they are editing.

- **Online Presence Indicators**  
  Displays which collaborators are online and currently active.

- **Shareable Collaboration Link**  
  Create and share session links for instant join access.

- **Multi-Language Code Execution**  
  Code is executed securely inside isolated Docker containers.

- **WebSocket-Based Real-Time Updates**  
  Smooth, low-latency collaboration powered by WebSockets.

- **Monitoring & Observability**  
  Integrated Prometheus metrics and Grafana dashboards for:
  - API performance  
  - Active sessions  
  - Docker container stats  
  - CPU & memory usage  

---

## 🧰 Tech Stack

### Frontend
- React.js  
- Monaco Editor  
- WebSockets  

### Backend
- Node.js + Express  
- WebSocket Server  
- Docker for code execution  

### Infrastructure & Monitoring
- Docker & Docker Compose  
- Prometheus  
- Grafana  
