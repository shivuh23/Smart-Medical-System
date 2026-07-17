# Smart Medical System


A comprehensive full‑stack medical management platform enabling doctors and patients to manage appointments, treatments, vitals, analytics, AI-driven suggestions, and secure reports. Built using the latest modern web technologies with a clean UI and scalable backend.

## 🚀 Features
### 👨‍⚕️ Doctor Module
- View and manage patients
- Add treatments, prescriptions, and advice
- Upload and manage patient reports
- Search patients by Patient ID (PID)
- View analytics and vitals charts

### 🧑‍🤝‍🧑 Patient Module
- View health vitals trends
- Access medical reports
- View treatments and doctor advice
- Secure password update
- Analytics dashboard

### 🤖 AI Engine (Optional)
- Generates insights from vitals
- Suggests preventive care recommendations
- Natural language summary generator

## 🛠 How to Run This Project Locally

This project includes:
- **Backend** (Node.js + Express + MongoDB)
- **Frontend** (React + Vite)
- **AI Engine** (optional)

---

## 📦 1. Clone the Repository
```bash
git clone https://github.com/Satish20102003/smart-medical-system.git
cd smart-medical-system
```

---

## 🟣 2. Run Backend (Server)
### Go to backend folder:
```bash
cd backend
```

### Install dependencies:
```bash
npm install
```

### Create `.env` file:
```
MONGO_URI=your_mongodb_atlas_url
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_optional_key
```

### Start backend:
```bash
node server.js
```

Backend will run on:
```
http://localhost:5000
```

---

## 🟢 3. Run Frontend (React + Vite)
### Open new terminal and go to frontend:
```bash
cd frontend
```

### Install dependencies:
```bash
npm install
```

### Create `.env` file:
```
VITE_API_URL=http://localhost:5000
```

### Start frontend:
```bash
npm run dev
```

Frontend runs on:
```
http://localhost:5173
```

---

## 🌐 4. Live Deployed Version (Online Demo)
### ✔ Frontend (Vercel)
👉 **https://smart-medical-system.vercel.app**

### ✔ Backend (Render)
👉 **https://smart-medical-system.onrender.com**

---

## 📌 5. Demo Login Accounts
### Doctor Login  
```
Email: doctor@gmail.com
Password: 123456
```

### Patient Login  
```
Email: patient@gmail.com
Password: 123456
```

---

## 🛠 Tech Stack
### Frontend
- React.js
- Tailwind CSS
- Recharts
- Lucide Icons
- Axios

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- Multer file upload

### DevOps / Tools
- Git & GitHub
- VS Code
- Postman / Thunder Client

## 📁 Folder Structure
```
smart-medical-system/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── api/
│   │   └── App.js
│   └── package.json
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── uploads/
│   └── server.js
└── README.md
```

## ⚙️ Installation & Setup
### 1. Clone the repo
```
git clone https://github.com/yourusername/smart-medical-system.git
```

### 2. Install frontend
```
cd frontend
npm install
npm start
```

### 3. Install backend
```
cd backend
npm install
node server.js
```

### 4. Environment variables (IMPORTANT)
Create `.env` in **backend**:
```
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
```

## 📊 Vitals & Analytics
The patient dashboard includes:
- Heart rate graphs
- Temperature trends
- BP charts
- Oxygen level tracking
- Doctor insights

## 📸 Screenshots
Below are sample placeholders — replace with your real images.

### 🧩 Login Page
![Login Screenshot](assets/screenshots/login.png)

### 🏥 Patient Dashboard
![Dashboard Screenshot](assets/screenshots/patient_dashboard.png)

### 👨‍⚕️ Doctor Treatment Page
![Doctor Screenshot](assets/screenshots/doctor_treatment.png) (Add yours here)
```
![Dashboard Screenshot](path_to_image)
![Login Screen](path_to_image)
```

## 📄 API Endpoints
### Patients
- `GET /patients/profile/me`
- `GET /patients/:id`
- `PUT /patients/update-password`

### Treatments
- `POST /treatments/:id`
- `GET /treatments/:id`

### Reports
- `POST /reports/upload/:id`
- `GET /reports/:id`

## 🔐 Security
- JWT authentication
- Password hashing
- Role-based access control
- GitHub secret protection
- `.env` secured with `.gitignore`

## 🧪 Testing
Use Postman or Thunder Client to test API routes.

## ⭐ Project Highlights
- Clean & Modern UI
- AI-Assisted Engine
- Full Analytics
- Secure Authentication
- Doctor–Patient Collaboration

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

## 📜 License
MIT License

Made By Shivanand


