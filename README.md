# 🌤 Real-Time Weather Dashboard

A full-stack app featuring real-time weather data, interactive maps, authentication, and developer resources.

## 🛠 Tech Stack

- Frontend: Next.js, Tailwind CSS, React Leaflet, NextAuth, Context API
- Backend: Node.js, Express.js, MongoDB (via Mongoose)
- APIs: WeatherAPI, weather.gov, Dev.to

## 🔐 Auth

Using NextAuth.js with credentials-based login (email/password)

## 🌦 Features

- Search city & view 7-day weather forecast
- Radar map with real-time weather alerts
- Save/delete favorite cities (CRUD)
- Auth-protected dashboard
- Dev.to integration with `/resources` page

## 🧪 Setup

### 1. Install
```bash
cd backend && npm install
cd ../frontend && npm install
```

### 2. Configure `.env` Files
Backend:
```
MONGODB_URI=your_mongo_uri
OPENWEATHER_API_KEY=your_api_key
AUTH_EMAIL=admin@example.com
AUTH_PASS=admin123
```

Frontend:
```
NEXTAUTH_SECRET=supersecret
NEXTAUTH_URL=http://localhost:3000
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000/api
```

### 3. Run
```bash
cd backend && npm run dev
cd frontend && npm run dev
```

### 4. Run Tests
```bash
cd frontend
npm test
```

## 📦 Deployment

- Vercel (frontend)
- Render (backend)
- MongoDB Atlas (database)
