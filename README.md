# 🚀 Travel India Smart - Full-Stack Travel Super App

> A production-ready multi-transport travel booking platform for India with trains, buses, flights, and local transport.

## 📋 Project Overview

**Travel India Smart** is a comprehensive travel planning and booking super app inspired by IRCTC, RedBus, and MakeMyTrip, built with modern tech stack and production-ready architecture.

### ✨ Key Features
- 🚂 Multi-transport search (trains, buses, flights, autos, cabs)
- 🤖 AI-powered trip planner
- 📍 Live tracking (trains, buses, cabs)
- 💳 Secure payment gateway (Razorpay + UPI)
- 🗺️ Google Maps integration
- 📱 Offline mode with ticket storage
- 🌍 Multi-language support (Hindi, English, regional)
- 💰 Budget planner & expense tracker
- 🔔 Smart alerts (price drops, delays, platform changes)
- 🤖 AI chatbot for travel assistance

## 🏗️ Project Structure

```
travel-india-smart/
├── backend/                    # Node.js Express API
│   ├── src/
│   │   ├── config/            # Configuration (DB, Redis, Auth)
│   │   ├── controllers/        # Route controllers
│   │   ├── models/             # Database models
│   │   ├── routes/             # API routes
│   │   ├── middleware/         # Custom middleware
│   │   ├── services/           # Business logic
│   │   ├── integrations/       # Third-party APIs
│   │   ├── utils/              # Helper functions
│   │   ├── validators/         # Request validators
│   │   └── app.js              # Express app setup
│   ├── migrations/             # Database migrations
│   ├── package.json
│   ├── server.js               # Entry point
│   └── Dockerfile
├── frontend/                   # React Web App
│   ├── src/
│   │   ├── components/         # Reusable components
│   │   ├── pages/              # Page components
│   │   ├── services/           # API services
│   │   ├── hooks/              # Custom hooks
│   │   ├── store/              # Redux store
│   │   ├── utils/              # Utilities
│   │   ├── styles/             # Global styles
│   │   ├── assets/             # Images, icons
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   ├── vite.config.js
│   └── Dockerfile
├── mobile/                     # Flutter Mobile App
│   ├── lib/
│   │   ├── models/             # Data models
│   │   ├── services/           # API services
│   │   ├── screens/            # UI screens
│   │   ├── widgets/            # Reusable widgets
│   │   ├── providers/          # State management
│   │   ├── utils/              # Utilities
│   │   ├── assets/             # Images, fonts
│   │   └── main.dart           # Entry point
│   ├── pubspec.yaml
│   ├── Dockerfile
│   └── README.md
├── docs/                       # Documentation
│   ├── API.md                  # API documentation
│   ├── DATABASE.md             # Database schema
│   ├── ARCHITECTURE.md         # Architecture overview
│   ├── DEPLOYMENT.md           # Deployment guide
│   └── INTEGRATIONS.md         # Third-party integrations
├── docker-compose.yml          # Docker orchestration
├── .env.example                # Environment template
├── .gitignore
└── SETUP.md                    # Setup instructions
```

## 🛠️ Tech Stack

### Backend
- **Runtime**: Node.js 18+
- **Framework**: Express.js
- **Database**: PostgreSQL 13+
- **Cache**: Redis 6+
- **Auth**: JWT + OTP (Firebase)
- **Realtime**: Socket.io
- **API Gateway**: Express

### Frontend (Web)
- **Framework**: React 18
- **Build Tool**: Vite
- **State Management**: Redux Toolkit + Context API
- **UI Framework**: TailwindCSS + Material-UI
- **Maps**: Google Maps API
- **HTTP Client**: Axios
- **Forms**: React Hook Form

### Mobile (Flutter)
- **Framework**: Flutter 3+
- **State Management**: Provider + Riverpod
- **Local Storage**: SQLite + GetStorage
- **HTTP**: Dio
- **Maps**: Google Maps Flutter
- **Push Notifications**: Firebase Cloud Messaging

### External Integrations
- **Trains**: IRCTC API
- **Flights**: Amadeus API
- **Buses**: RedBus API
- **Cabs**: Ola/Uber API
- **Maps**: Google Maps
- **Payments**: Razorpay + UPI
- **Weather**: OpenWeatherMap
- **AI**: OpenAI API
- **SMS/WhatsApp**: Twilio

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 13+
- Redis 6+
- Flutter 3+
- Docker & Docker Compose

### Setup

```bash
# 1. Clone repository
git clone https://github.com/imran100khanali-rgb/travel-india-smart.git
cd travel-india-smart

# 2. Setup environment variables
cp .env.example .env

# 3. Start with Docker Compose (recommended)
docker-compose up -d

# 4. Or setup manually
cd backend && npm install && npm run dev
# In another terminal
cd frontend && npm install && npm run dev
# In another terminal
cd mobile && flutter pub get && flutter run
```

## ✅ Verification

- **Backend API**: http://localhost:5000/api/health
- **Frontend**: http://localhost:5173
- **Database**: PostgreSQL on port 5432
- **Redis**: Redis on port 6379

## 📚 Documentation

See the `/docs` folder for:
- [API Documentation](./docs/API.md)
- [Database Schema](./docs/DATABASE.md)
- [Architecture Overview](./docs/ARCHITECTURE.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)
- [Integrations Guide](./docs/INTEGRATIONS.md)

## 🔐 Security

- End-to-end encryption for sensitive data
- Secure payment processing (PCI compliant)
- OTP-based authentication
- JWT token-based API security
- Role-based access control (RBAC)
- Environment variables for secrets
- HTTPS/TLS everywhere
- Rate limiting on all APIs
- SQL injection prevention with parameterized queries

## 📊 Scalability

- Load balancing ready
- Database connection pooling
- Redis caching layer
- CDN-ready static assets
- Microservices-ready architecture
- Container orchestration (Docker/Kubernetes)
- Horizontal scaling support

## 🤝 Contributing

Please read our contributing guidelines before submitting PRs.

## 📄 License

MIT License - See LICENSE file

## 👨‍💼 Author

Imran Khan (@imran100khanali-rgb)

---

**Built with ❤️ for Indian travelers** 🇮🇳
