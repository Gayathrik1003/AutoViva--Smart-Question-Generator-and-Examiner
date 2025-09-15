# 🤖 AutoViva - Smart Question Generator and Examiner

An AI-powered college management and viva automation system. AutoViva helps educators streamline the process of generating viva questions, managing academic entities, and exporting exam data. Built with modern web technologies and MongoDB backend.

---

## 🚀 Features

- 🔐 Secure authentication with **MongoDB**
- 🧠 Auto-generate viva questions using **Google Generative AI**
- 👨‍🏫 Manage Students, Teachers, Subjects, Exams, Results
- 📄 Export PDFs using `pdf-lib`
- ⚡ Fast and clean interface built with **React**, **TailwindCSS**, and **Vite**
- 🔧 RESTful API powered by **Express.js**

---

## 🛠️ Tech Stack

### Frontend
- React + Vite
- TailwindCSS
- Zustand (state management)
- React Router
- Lucide & Radix UI Icons

### Backend
- Node.js + Express
- MongoDB with Mongoose
- JWT Authentication
- Modular API design

---

## 📁 Project Structure

```
AutoViva/
├── .bolt/                  # AI prompt configuration
├── backend/                # Express + MongoDB backend
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── server.js
├── src/                    # React frontend
│   ├── components/
│   │   ├── Layout.tsx
│   │   ├── ProtectedRoute.tsx
│   │   └── icons/
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
├── index.html
├── vite.config.ts
├── tailwind.config.js
├── .env
└── package.json
```

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/12hestin/AutoViva-Smart-Question-Generator-and-Examiner.git
cd AutoViva-Smart-Question-Generator-and-Examiner

# Install frontend dependencies
npm install

# Start the frontend
npm run dev

# Go to backend and install dependencies
cd backend
npm install

# Run backend server
node src/server.js
```

---

## 🌐 Environment Setup

Create a `.env` file in the `backend/` folder with the following:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 💡 Contributions

Pull requests are welcome! Feel free to fork, improve, and submit a PR.

---

## 📬 Contact

Got feedback? Open an issue or reach out at [GitHub Issues](https://github.com/12hestin/AutoViva-Smart-Question-Generator-and-Examiner/issues)

---

⭐️ **Star this repo** if you find it useful!
