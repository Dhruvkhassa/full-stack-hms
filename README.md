# 🏥 Hospital Management System (HMS)

The **Hospital Management System (HMS)** is a full-stack web application designed to streamline hospital operations such as managing patients, doctors, appointments, and records.  

This project demonstrates an end-to-end solution using both **frontend & backend** technologies, enabling medical staff and admins to efficiently manage healthcare workflows.

---

## 🚀 Features
- 👨‍⚕️ **Doctor Management** – Add, view, and manage doctor records.
- 🧑‍🤝‍🧑 **Patient Management** – Register new patients, view records, and manage history.
- 📅 **Appointments** – Schedule, update, and cancel medical appointments.
- 📝 **Medical Records** – Maintain patient history and treatment records.
- 🔐 **Authentication** – Secure login system for admin/staff access.
- 📊 **Dashboard** – Centralized overview of key hospital activities.
- 🌐 **Full-Stack Architecture** – Combines frontend (UI) and backend (logic/database).

---

## 🛠️ Tech Stack
### Frontend:
- **HTML5 / CSS3 / JavaScript**
- **React.js / Bootstrap** (if applicable)

### Backend:
- **Node.js / Express.js** (if implemented)
- **MongoDB / MySQL** (for database connectivity)

> _(Adjust the stack above depending on what your implementation actually uses — since repo is named `full-stack`, it likely involves Node/Express + MongoDB or MySQL.)_

---

## 📂 Project Structure (Example)
```
full-stack-hms/
├── backend/                 # Backend (API, DB models, authentication)
├── frontend/                # Frontend (UI, components, services)
├── package.json             # Dependencies
├── README.md                # Documentation
└── LICENSE                  # MIT License
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repo:
```bash
git clone https://github.com/DhruvKhassa/full-stack-hms.git
cd full-stack-hms
```

### 2️⃣ Install dependencies (both frontend & backend)
```bash
cd backend
npm install

cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the backend folder with:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application
```bash
# In backend
npm start

# In frontend
npm start
```

The app should now be running at:
👉 Frontend: `http://localhost:3000`  
👉 Backend API: `http://localhost:5000`

---

## 📸 Screenshots (Optional)
_Add UI screenshots or demo GIF here for a professional look._

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 👨‍💻 Author
- **Dhruv Khassa** – [GitHub Profile](https://github.com/DhruvKhassa)

---

✨ A digital solution to make hospital management more efficient and reliable.
