# 🌐 Pro-Tasker Frontend
(help by Yusuf,Reagan,David,Rico,Manasa,Menro)
{made alot of repos}
This is the **frontend** of **Pro-Tasker**, a modern project management application built with the **MERN stack**. This React-based UI connects to the Pro-Tasker backend API and supports features like user authentication, project dashboards, task updates, and role-based access.

---

## ⚙️ Tech Stack = The full set of technologies used to build and run a software application.

- **React**
- **Vite**
- **React Router DOM**
- **Axios**
- **Context API**
- **Custom Hooks (useAuth, useFetch)**
- **Tailwind CSS (if styled)**

---

## 📁 Folder Structure

frontend/
├── public/
├── src/
│ ├── client/ # Axios setup
│ ├── components/ # Shared UI components
│ ├── context/ # Auth context provider
│ ├── hooks/ # useAuth & useFetch
│ ├── pages/ # Page-level components (Login, Dashboard, etc.)
│ ├── utils/ # Token helpers
│ └── App.jsx # Routes and main layout
├── index.html
├── main.jsx
├── .env.production
├── vite.config.js


---

## 🛠️ Features

- 🔐 **User Authentication**
- 📁 **Project Dashboard**
- ✅ **Task Management by Project**
- 🔄 **Protected Routes with Context**
- 💡 **Custom Axios Clients for Backend Communication**

---

## 🌐 Environment Variables

Create a `.env.production` file:

VITE_API_URL=https://https://pro-tasker-backend-1-mb0s.onrender.com


---

## 🧪 Local Development

### 1. Install dependencies

```bash
npm install
2. Start development server
bash
Copy
Edit
npm run dev
Visit:
http://localhost:5173

🚀 Build for Production
bash
Copy
Edit
npm run build
Build output goes to the dist/ directory.

📦 Deployment
You can deploy this frontend to GitHub Pages, Netlify, Vercel, or pair it with your backend deployment on Render or Heroku.

To push your final build:

bash
Copy
Edit
git add .
git commit -m "Final frontend build"
git push origin main
If the push fails:

bash
git pull --rebase
git push --force
🧠 Author Notes
This frontend was built by Artis Watson as part of the final capstone for a full-stack MERN bootcamp. It demonstrates real-world architecture, client-server communication, and secure React app development.
