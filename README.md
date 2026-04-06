# 🚀 TechLearn QOTD (Question of the Day Platform)

## 📌 Overview
**TechLearn QOTD** is a full-stack web application designed to help users improve their coding skills through a **daily question system**. Users can solve problems, submit code, and track their progress over time.

---

## ✨ Features
- 📅 Daily coding questions (QOTD)
- ✍️ Code submission system
- 🧪 Run and evaluate solutions
- 🔐 User authentication & authorization
- 📊 Progress tracking dashboard
- 🎨 Smooth and responsive UI with animations

---

## 🏗️ Tech Stack

### 💻 Frontend
- React (Vite)
- Tailwind CSS
- Framer Motion
- Lucide Icons

### ⚙️ Backend
- Node.js
- Express.js

### 🗄️ Database
- MongoDB *(or JSON-based storage for lightweight setup)*

---

## 📂 Project Structure
```
techlearn-QOTD/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── components/
│
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 1. Clone the Repository
```bash
git clone https://github.com/your-username/techlearn-QOTD.git
cd techlearn-QOTD
```

---

### 🔹 2. Backend Setup
```bash
cd backend
npm install
npm start
```

📌 Create a `.env` file inside `/backend` with:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

### 🔹 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

---

## 🌐 Usage
1. Open your browser and go to:
   http://localhost:5173
2. Sign up / log in  
3. Solve the **Question of the Day**  
4. Submit your code  
5. Track your progress 🚀  

---

## 📊 Future Enhancements
- 🏆 Leaderboard system  
- 💬 Discussion forum for each question  
- 📈 Advanced analytics dashboard  
- 🧠 AI-based hints & recommendations  

---

## 🤝 Contributing
Contributions are welcome!

1. Fork the repo  
2. Create a new branch  
```bash
git checkout -b feature-name
```
3. Commit your changes  
```bash
git commit -m "Added new feature"
```
4. Push to your branch  
```bash
git push origin feature-name
```
5. Open a Pull Request 🎉  

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 💡 Author
**Anugya Jain**
