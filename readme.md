# 🎥 LiveStream+

A **mini real-time streaming web app** built using **FastAPI (backend)**, **React (frontend)**, and **PostgreSQL (database)**.  
It demonstrates **Server-Sent Events (SSE)** for live data streaming and stores messages persistently in a database.

---

## 🚀 Features
- 🔴 Real-time updates via **Server-Sent Events (SSE)**
- 💾 Messages stored in **PostgreSQL**
- ⚡ Built with **FastAPI** and **React (Vite)**
- 🧱 Uses **SQLAlchemy ORM**
- 🔁 Fetches previous + new messages automatically

---

## 🧩 Tech Stack
| Layer | Technology |
|--------|-------------|
| **Frontend** | React + Vite + Tailwind CSS |
| **Backend** | FastAPI |
| **Database** | PostgreSQL |
| **Streaming** | Server-Sent Events (SSE) |
| **ORM** | SQLAlchemy |

---

## 📁 Folder Structure

```tree
livestream_plus/
│
├── backend/
│ ├── main.py
│ ├── database.py
│ ├── models.py
│ ├── requirements.txt
│ └── venv/
│
└── frontend/
├── src/
│ ├── App.jsx
│ └── components/
│ └── StreamView.jsx
├── index.html
└── package.json


---

## ⚙️ Backend Setup

### 1️⃣ Create and activate a virtual environment
```bash
cd backend
python -m venv venv

