# Taskify – Full Stack Task Manager

Taskify is a full-stack task management app where users can manage their daily tasks with priority levels.

---

## 🔧 Tech Stack

- **Frontend**: React (Vite) + Tailwind CSS  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB + Mongoose  
- **Authentication**: JWT (JSON Web Tokens)

---

## 📁 Project Structure

```
taskify/
├── client/   → React frontend
└── server/   → Node backend with Express
```

---

## 🚀 Local Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/manpreet0905/taskify.git
cd taskify
```

### 2. Setup Backend

```bash
cd server
npm install
```

Create a `.env` file inside `server/` and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend server:

```bash
npm run dev
```

---

### 3. Setup Frontend

```bash
cd ../client
npm install
npm run dev
```

Visit: [http://localhost:5173](http://localhost:5173)

---

## 🌐 Deployment Instructions

### Frontend on Vercel

1. Go to [https://vercel.com](https://vercel.com)  
2. Import your GitHub repo  
3. Set root directory to `client/`  
4. Framework: Vite  
5. Deploy  

---

### Backend on Render

1. Go to [https://render.com](https://render.com)  
2. Click "New Web Service"  
3. Repo: `taskify`  
4. Root directory: `server/`  
5. Build Command: `npm install`  
6. Start Command: `npm run dev`  
7. Add environment variables:  
   - `MONGO_URI`  
   - `JWT_SECRET`  
8. Click Deploy  

---

## ✅ Features

- 🔐 JWT Authentication  
- 📝 Add/View/Delete Tasks  
- 🟢 Task Priority: High / Medium / Low  
- 🗂 Organized REST API  

---

## 📜 License

MIT – Free to use and modify
