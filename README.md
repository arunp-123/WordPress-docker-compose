# wordpress-docker-compose 🐳

A simple and production-friendly Docker Compose setup to run a WordPress website with a MySQL database. This setup uses persistent volumes, a custom bridge network
---

## 📦 Stack

- **WordPress** (latest)
- **MySQL** (latest)
- **Docker Compose**

🚀 How to Use
1. Clone the Repository

2. Start the Containers
docker compose up -d
⏳ It might take a few moments on the first run to download images.
3. Access WordPress
Open your browser and go to:
👉 http://localhost (or your EC2 public IP)


🧹 Management Commands
Stop all services:

docker compose down

View logs:

docker compose logs -f

Rebuild containers:

docker compose up -d --build
