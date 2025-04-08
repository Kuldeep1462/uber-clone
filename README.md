Sure! Here's a clean and professional **GitHub project description** for your **Uber Clone**—you can paste this into your `README.md` or GitHub repo description:

---

## 🚗 Uber Clone – Full Stack MERN App

A full-featured Uber clone built with the MERN stack (MongoDB, Express, React, Node.js). This project simulates a ride-hailing platform with functionality for both **users** and **drivers**, including ride requests, real-time location updates, authentication, and map integration.

---

### 🌟 Features

- ✅ **User & Driver Authentication** (JWT + Cookies)
- 📍 **Google Maps Integration** for live tracking
- 🚕 **Book a Ride** – select pickup/drop-off
- 👨‍✈️ **Captain Dashboard** for managing rides
- 📦 **MongoDB Atlas** database (connected via Mongoose)
- 🍪 Cookie-based auth with `HttpOnly` tokens
- 💬 Real-time ride updates (Socket.io ready integration)

---

### 🔧 Tech Stack

- **Frontend**: React, Tailwind CSS, React Router
- **Backend**: Node.js, Express.js, MongoDB (Mongoose)
- **Auth**: JWT + Cookies
- **Maps**: Google Maps API
- **Database**: MongoDB Atlas + MongoDB Compass (for local testing)

---

### 📁 Folder Structure

```
/frontend       → React app for UI
/backend        → Express server, routes, controllers
.env            → Environment variables for both client/server
```

---

### 🚀 Setup Instructions

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/uber-clone.git
   cd uber-clone
   ```

2. Install backend dependencies  
   ```bash
   cd backend
   npm install
   ```

3. Setup `.env` in backend:
   ```
   PORT=5000
   MONGO_URI=<your_mongo_connection_string>
   JWT_SECRET=<your_jwt_secret>
   ```

4. Start the backend:
   ```bash
   npm start
   ```

5. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

6. Setup `.env` in frontend:
   ```
   VITE_BASE_URL=http://localhost:5000
   ```

7. Start the frontend:
   ```bash
   npm run dev
   ```

---

### 🛠️ To Do / Improvements

- [ ] Add real-time ride updates with Socket.io
- [ ] Add payment integration (e.g., Stripe)
- [ ] Optimize UX for mobile
- [ ] Add ride history & driver rating

