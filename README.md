# 🎯 Face Recognition Attendance System

This is a **Full-Stack Face Recognition Attendance System** that uses **React** for the frontend and **FastAPI / Python** for the backend.  
It allows users to **register**, **login**, **logout**, and for admins to **download attendance logs** — all using **live webcam capture** and **face recognition**.

---

## 📌 Features
- **Live Webcam Integration** – Captures frames directly from the user's webcam.
- **User Registration** – Register new users with a captured photo and name.
- **Login & Logout** – Verify identity via face recognition.
- **Admin Mode** – Access extra features like registration and downloading logs.
- **Attendance Logs Download** – Admins can download `.zip` files of attendance data.
- **Dynamic UI State Management** – Switch between live video and captured image previews.

---

## 🛠️ Tech Stack
### Frontend:
- **React** (JavaScript)
- HTML, CSS
- Axios for API calls
- Browser `MediaDevices` API for webcam access

### Backend:
- **Python** with **FastAPI**
- **face_recognition** library
- OpenCV (`cv2`) for image processing
- `uvicorn` server
- Attendance logs stored as `.zip` files

---

## 📂 Project Structure
📂 Face-Recognition-Attendance-System
├── 📂 backend
│   ├── main.py                 # FastAPI entry point
│   ├── requirements.txt        # Backend dependencies
│   ├── db/                     # Face embeddings / database
│   ├── logs/                   # Attendance log files (.zip)
│   ├── utils/                  # Helper functions (face processing, encoding, etc.)
│   └── API.py                  # API endpoint configurations
│
├── 📂 frontend
│   ├── 📂 src
│   │   ├── App.js              # Main React component
│   │   ├── MasterComponent.js  # Handles webcam, login, logout, registration
│   │   ├── API.js              # Stores API base URL
│   │   ├── index.js            # Entry point for React app
│   │   ├── components/         # Additional UI components
│   │   └── styles/             # CSS files
│   ├── package.json            # Frontend dependencies
│   └── package-lock.json
│
├── README.md                   # Project documentation
└── .gitignore                  # Git ignore rules
---

Ujjwal Roy
B.Tech in Computer Science and Business Systems
Narula Institute of Technology
