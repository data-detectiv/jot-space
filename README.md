# 📝 JotSpace

**JotSpace** is a full-stack note-taking web application built with the **MERN** stack (MongoDB, Express.js, React, and Node.js). It allows users to create, manage, and organize their notes with powerful features such as authentication, role-based access control, note pinning, and real-time editing.

---

## 🚀 Features

- 🔐 **Authentication** – Secure user registration and login
- 👥 **User Roles** – Assign admin/user roles for access control
- ✍️ **CRUD Operations** – Create, edit, delete, and view notes
- 📌 **Pin Notes** – Keep important notes at the top
- 🔎 **Search** – Quickly find notes by keywords
- 💡 **Responsive UI** – Clean and intuitive design with Tailwind CSS

---

## 🛠 Tech Stack

- **Frontend**: React, Vite, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Authentication**: JWT + bcrypt
- **State Management**: useState, useContext
- **Deployment**: (e.g., Render / Vercel / Railway / MongoDB Atlas)

---

## 📁 Project Structure

```

jot-space/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   └── App.jsx
│   └── vite.config.js
└── .env

````

---

## 🧪 Getting Started

### Backend Setup
```bash
cd backend
npm install
npm run dev
````

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

> Create a `.env` file in the backend and add:

```
PORT=5000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
```

---

## 🌐 Live Demo

\[Coming Soon]

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.

