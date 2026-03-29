# PyDataSync

> Python data synchronization between databases with conflict resolution

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Python, Flask, MongoDB, Redis

## 🏗️ Architecture
Backend service with Python, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/pydatasync
cd pydatasync

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
