

## 📘 CourseApp

**CourseApp** is a full-stack web application for managing and browsing courses. It consists of a React frontend and a backend API documented and tested via Swagger. The frontend uses Redux for state management and Thunk for handling asynchronous operations like API calls.

---

### 🚀 Features

- 🧑‍🎓 User authentication and role-based access
- 📚 Course listing and detailed view
- ✏️ Admin panel for managing courses and authors (Create, Read, Update, Delete)
- 🌐 REST API integration using `react-redux` and `redux-thunk`
- 📄 Backend API with Swagger UI for easy testing

---

### ⚙️ Tech Stack

**Frontend:**
- React
- Redux & Redux Thunk
- React Router DOM
- Fetch API
- TailwindCSS (or your chosen styling solution)

**Backend:**
- Node.js / Express (assumed)
- Swagger UI
- PostgreSQL / MongoDB (depending on your setup)
---

### 📦 Installation

#### Backend

1. Navigate to the backend folder:
   ```bash
   cd courseapp-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the server:
   ```bash
   npm start
   ```
4. Open Swagger UI:
   ```
   http://localhost:PORT/api-docs
   ```

#### Frontend

1. Navigate to the frontend folder:
   ```bash
   cd courses-app-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```
4. The app will be available at:
   ```
   http://localhost:3000
   ```

---

### 🔐 User Roles (Example)

- **Admin:** Can manage courses and authors
- **User:** Can view courses only

---

### 🛠 API Documentation

Visit Swagger UI to explore and test all backend routes:  
```
http://localhost:PORT/api-docs
```

---

### 🧪 Development Tips

- Make sure the backend server is running before using the frontend.
- Use Redux DevTools Extension for debugging.
- To test protected routes, use role-based authentication via token headers.

---

### 📤 Deployment

To push the project to GitHub:

1. Initialize Git (if not done yet):
   ```bash
   git init
   ```
2. Commit all files:
   ```bash
   git add .
   git commit -m "Initial commit for CourseApp"
   ```
3. Push to GitHub:
   ```bash
   git remote add origin https://github.com/Dast1nn/course-app.git
   git push -u origin main
   ```
