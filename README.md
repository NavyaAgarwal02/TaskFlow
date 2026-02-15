# ✅ TaskFlow – Full Stack Task Manager Application

TaskFlow is a full-stack task management application that allows users to create, view, update, and delete tasks with priority and status support.

The project uses Node.js, Express, MongoDB for the backend and React (Vite) with Tailwind CSS for the frontend. The backend is deployed on Render and serves RESTful APIs to the frontend.



## 🚀 Features

### Backend
- Create, Read, Update, Delete (CRUD) operations
- Task priority: Low, Medium, High
- Default task status: Pending
- RESTful API architecture
- MongoDB integration using Mongoose

### Frontend
- Add new tasks with priority
- Fetch and display tasks from backend
- Delete tasks
- Real-time UI updates (no page reload)
- Responsive and modern interface



## 🛠 Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Frontend
- React (Vite)
- Tailwind CSS
- JavaScript (ES6)
- Fetch API



## 📁 Project Repositories

- **Backend:** https://github.com/naveenc-04/task-manager-backend  
- **Frontend:** https://github.com/naveenc-04/task-manager-frontend  



## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /api/tasks | Get all tasks |
| POST   | /api/tasks | Create a new task |
| PUT    | /api/tasks/:id | Update a task |
| DELETE | /api/tasks/:id | Delete a task |



## ⚙️ Backend Setup (Local)

### 1. Clone Repository
```bash
git clone https://github.com/naveenc-04/task-manager-backend.git
cd task-manager-backend
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### 4. Start Server

```bash
npm start
```

Server will run at:

```
http://localhost:5000
```



## ⚙️ Frontend Setup (Local)

### 1. Clone Repository

```bash
git clone https://github.com/naveenc-04/task-manager-frontend.git
cd task-manager-frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=https://task-manager-backend-r94r.onrender.com
```

For local backend testing:

```env
VITE_API_URL=http://localhost:5000
```

### 4. Run Development Server

```bash
npm run dev
```

Frontend will run at:

```
http://localhost:5173
```



## 🌐 Deployment

### Backend

* Hosted on Render
* Provides production REST APIs

### Frontend

* Connects to deployed backend
* Uses environment variables for API access



## 🔄 Application Workflow

1. User creates a task from the frontend
2. Frontend sends API request to backend
3. Backend stores data in MongoDB
4. Updated task list is returned
5. UI updates instantly



## 📄 Environment Variables Summary

### Backend

```env
PORT=5000
MONGO_URI=MongoDB URI
```

### Frontend

```env
VITE_API_URL=Backend API URL
```



## 🚧 Future Enhancements

* User authentication
* Task categories
* Due dates and reminders
* Search and filtering
* Task completion tracking



## 👨‍💻 Author

Developed by **Navya Agarwal**



## 📜 License

This project is licensed under the MIT License.

```

---

### ✅ How to Use
1. Copy everything inside the box.
2. Create `README.md` in your main project folder.
3. Paste and commit to GitHub.

If you'd like, I can next help you **add screenshots, badges, or live demo links** to make it even more impressive.
```
