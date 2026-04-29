# 🛠️ Travel India Smart - Setup Guide

## Prerequisites

- Node.js 18+ ([Download](https://nodejs.org/))
- PostgreSQL 13+ ([Download](https://www.postgresql.org/download/))
- Redis 6+ ([Download](https://redis.io/download))
- Flutter 3+ ([Download](https://flutter.dev/docs/get-started/install))
- Docker & Docker Compose ([Download](https://www.docker.com/products/docker-desktop))
- Git

## 📦 Installation Steps

### 1. Clone Repository

```bash
git clone https://github.com/imran100khanali-rgb/travel-india-smart.git
cd travel-india-smart
```

### 2. Setup Environment Variables

```bash
cp .env.example .env
```

Edit `.env` with your configuration.

### 3. Docker Compose Quick Start (Recommended)

```bash
# Start all services
docker-compose up -d

# Check logs
docker-compose logs -f

# Stop all services
docker-compose down
```

### 4. Backend Setup

```bash
cd backend

# Install dependencies
npm install

# Run database migrations
npm run migrate

# Start development server
npm run dev
```

### 5. Frontend Setup

```bash
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### 6. Mobile Setup

```bash
cd mobile

# Get Flutter dependencies
flutter pub get

# Run on emulator/device
flutter run
```

## ✅ Verification

1. **Backend API**: http://localhost:5000/api/health
2. **Frontend**: http://localhost:5173
3. **Database**: PostgreSQL on port 5432
4. **Redis**: Redis on port 6379

## 📚 Documentation

See `/docs` folder for detailed documentation.
