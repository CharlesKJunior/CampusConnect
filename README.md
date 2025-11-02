# 🏫 CampusConnect

CampusConnect is a modern web-based platform designed to enhance communication, collaboration, and information sharing within a campus community. It connects students, lecturers, and administrators through a unified digital space.

---

## 🚀 Features (Current Progress)
- Django backend setup with JWT Authentication (`/api/token/` endpoint working ✅)
- PostgreSQL database connection
- Basic API structure in place
- Ready for frontend integration

---

## 🧱 Tech Stack
- **Backend:** Django Rest Framework (DRF)
- **Database:** PostgreSQL
- **Frontend (Planned):** React.js / Next.js
- **Authentication:** JSON Web Tokens (JWT)
- **Version Control:** Git & GitHub

---

## 🗂️ Project Structure
```
CampusConnect/
│
├── api/                # Main API app
├── campusconnect/      # Project configuration files
├── manage.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CampusConnect.git
   cd CampusConnect
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Linux/Mac
   venv\Scripts\activate     # On Windows
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the development server:
   ```bash
   python manage.py runserver
   ```

---

## 🔑 Authentication Endpoints
| Endpoint | Method | Description |
|-----------|---------|-------------|
| `/api/token/` | POST | Obtain JWT access & refresh tokens |
| `/api/token/refresh/` | POST | Refresh JWT access token |

---

## 💡 Next Steps
- Add models for Students, Lecturers, and Courses  
- Build the frontend dashboard  
- Integrate WebSocket for real-time notifications  
- Deploy to Render / Railway  

---

## 🧑‍💻 Author
**Mutebwa Charles**  
*Developer • Innovator • PLP Learner*
