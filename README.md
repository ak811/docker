# Flask + Redis with Docker Compose

This project is part of **Cloud Computing for Data Analysis (ITCS 6190/8190, Fall 2025)** hands-on exercise.  
It demonstrates how to containerize a Python Flask web application, connect it to a Redis cache, and orchestrate services using Docker Compose.

---

## 🚀 Setup & Run

1. **Clone the repo / download files**

   Make sure the following files are present in the project folder:
   - `app.py`
   - `requirements.txt`
   - `Dockerfile`
   - `compose.yaml`

2. **Build and start the containers**
   ```bash
   docker compose up --build
