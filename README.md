# 📝 To-Do Full Stack App

A full-stack **To-Do application** built using the **MERN stack**.
The project allows users to create, view, update, and delete tasks through a React frontend connected to a Node.js/Express backend and MongoDB database.

🔗 **Live Demo:** (https://to-do-full-stack-app-delta.vercel.app/)

---

## 🚀 Features

* ➕ Add new tasks
* 📋 View all tasks
* ✏️ Update existing tasks
* 🗑️ Delete tasks
* 🔄 Real-time frontend and backend API communication
* 🗄️ MongoDB database integration
* 🌐 RESTful API architecture
* 📱 Responsive user interface
* ⚠️ Basic error handling and API validation
* 🔐 Environment variables for sensitive configuration

---

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Axios

### Backend

* Node.js
* Express.js
* REST API

### Database

* MongoDB
* Mongoose

### Tools & Deployment

* Git & GitHub
* Postman
* Vercel
* Render
* VS Code

---

## 📂 Project Structure

```text
todo-fullstack-app/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── docs/
│
├── postman/
│
├── .gitignore
├── README.md
└── vercel.json
```

---

## ⚙️ How It Works

The application follows a simple client-server architecture:

```text
React Frontend
      ↓
   Axios
      ↓
Express REST API
      ↓
   Mongoose
      ↓
MongoDB Database
```

The frontend sends HTTP requests to the Express backend.
The backend processes the request and performs the required operation in MongoDB.

---

# 💻 Getting Started

Follow the steps below to run the project locally.

## 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

Move into the project folder:

```bash
cd todo-fullstack-app
```

---

## 2. Setup Backend

Open a terminal and navigate to the backend:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `backend` folder:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

Start the backend:

```bash
npm run dev
```

The backend should now be running locally.

Example:

```text
http://localhost:5000
```

---

## 3. Setup Frontend

Open another terminal:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the frontend:

```bash
npm run dev
```

Open the local URL shown in your terminal, usually:

```text
http://localhost:5173
```

---

# 🔌 API Endpoints

The backend provides REST API endpoints for managing tasks.

| Method | Endpoint         | Description       |
| ------ | ---------------- | ----------------- |
| GET    | `/api/tasks`     | Get all tasks     |
| POST   | `/api/tasks`     | Create a new task |
| PUT    | `/api/tasks/:id` | Update a task     |
| DELETE | `/api/tasks/:id` | Delete a task     |


---

# 🧪 Testing With Postman

The API can also be tested using **Postman**.

You can find the Postman collection/documentation inside the:

```text
postman/
```

folder.

Test the following operations:

* Create a task
* Get all tasks
* Update a task
* Delete a task

---

# 🔐 Environment Variables

Sensitive information such as database credentials should not be committed to GitHub.

Create a `.env` file locally:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

# 🌐 Deployment

The application uses separate deployments for the frontend and backend.

### Backend

Hosted using:

**Render**

### Frontend

Hosted using:

**Vercel**

The frontend communicates with the deployed backend through its API URL.

---


# 🎯 Learning Outcomes

While building this project, I worked with:

* React component structure
* REST API development
* Express.js routing
* MongoDB database operations
* Mongoose models
* Axios API requests
* CRUD operations
* Environment variables
* API testing with Postman
* Git and GitHub
* Full-stack deployment

This project helped me understand how a frontend, backend, API, and database work together in a real-world web application.

---

# 🔮 Future Improvements

Some features that can be added in future versions:

* User authentication
* Individual task lists for users
* Task priority
* Due dates
* Search and filtering
* Task categories
* Dark/light mode
* Better form validation
* Task completion tracking

---

# 👨‍💻 Author

**Anushka Parashar**

Frontend Developer • React Developer • Software Developer

* GitHub: https://github.com/Anushkaparashar009
* LinkedIn: https://www.linkedin.com/in/anushkaa-parashar

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.

---

**Built with ❤️ using the MERN Stack.**
