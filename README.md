# 📘 Blog App (Node.js + Express)

A simple full-stack blog application built using **Node.js**, **Express**, and **EJS**, with REST API communication using Axios.

---

## 🚀 Features

* 📝 Create blog posts
* ✏️ Edit posts
* ❌ Delete posts
* 📖 View all posts
* 🔄 REST API communication (frontend ↔ backend)
* 🎨 Dynamic pages using EJS

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Frontend:** EJS, HTML, CSS
* **HTTP Client:** Axios
* **Data Storage:** In-memory (temporary)

---

## 📁 Project Structure

```
blog-app/
│
├── node_modules/        # Dependencies (ignored in Git)
│
├── public/
│   └── styles/
│       └── main.css     # Styling
│
├── views/
│   ├── index.ejs        # Home page
│   └── modify.ejs       # Create/Edit page
│
├── app.js               # Frontend server (EJS + Axios)
├── server.js            # Backend API server
├── package.json
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/blog-app.git
cd blog-app
```

---

### 2️⃣ Install dependencies

```
npm install
```

---

### 3️⃣ Run the project

👉 Start backend server:

```
node server.js
```

👉 Start frontend server:

```
node app.js
```

---

## 🌐 Usage

* Frontend: http://localhost:3000
* Backend API: http://localhost:4000

---

## 🔁 API Endpoints

| Method | Endpoint   | Description     |
| ------ | ---------- | --------------- |
| GET    | /posts     | Get all posts   |
| GET    | /posts/:id | Get single post |
| POST   | /posts     | Create post     |
| PATCH  | /posts/:id | Update post     |
| DELETE | /posts/:id | Delete post     |

---

## 🔮 Future Improvements

* 🗄️ Connect to PostgreSQL database
* 🔐 Add authentication (login/signup)
* 🌍 Deploy online
* 🎨 Improve UI design

---

## 👨‍💻 Author

Karuppaiya Murugan

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
