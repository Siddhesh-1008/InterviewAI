# 🚀 InterviewAI – AI Powered Interview Preparation Platform

InterviewAI is a full-stack AI powered platform that helps candidates prepare for technical interviews by analyzing job descriptions, resumes, and generating personalized interview strategies using Generative AI.

The system evaluates the candidate profile, extracts relevant skills, and generates technical questions, behavioral questions, roadmaps, and skill gap analysis.

---

# ✨ Features

• AI generated technical interview questions
• Behavioral interview preparation
• Resume analysis using AI
• Job description analysis
• Skill gap detection
• Match score calculation for roles
• Personalized interview roadmap

---

# 🛠 Tech Stack

### Frontend

* React.js
* Vite
* Axios
* Tailwind CSS

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* Mongoose

### AI Integration

* Generative AI API

### Other Tools

* Multer (file uploads)
* JWT Authentication

---

# 🏗 System Architecture

```
              ┌─────────────────────┐
              │      User Browser    │
              │   (React Frontend)   │
              └──────────┬──────────┘
                         │
                         ▼
               ┌─────────────────┐
               │   Frontend UI   │
               │  React + Vite   │
               └────────┬────────┘
                        │
                        ▼
                ┌───────────────┐
                │  Backend API  │
                │ Node + Express│
                └───────┬───────┘
                        │
         ┌──────────────┴──────────────┐
         ▼                             ▼
 ┌───────────────┐              ┌──────────────┐
 │   MongoDB     │              │  AI Engine   │
 │ User Data &   │              │ Generative AI│
 │ Interview Data│              │ Processing   │
 └───────────────┘              └──────────────┘
```

---

# 🧠 AI Workflow

```
User enters Job Description
        │
        ▼
User uploads Resume or adds profile description
        │
        ▼
Frontend sends request to Backend API
        │
        ▼
Backend processes inputs
        │
        ▼
AI Model analyzes:
   • Resume
   • Job Description
   • Skill matching
        │
        ▼
AI generates:
   • Technical Questions
   • Behavioral Questions
   • Interview Roadmap
   • Skill Gap Analysis
        │
        ▼
Frontend displays Interview Plan
```

---

# 📸 Project Screenshots

### Interview Plan Generator

UI where users submit job description and resume to generate AI interview strategy.

### Loading Screen

AI processing stage where the system analyzes the profile.

### Interview Dashboard

Displays:

• Technical questions
• Behavioral questions
• Interview roadmap
• Skill gap analysis
• Match score

---

# 📂 Project Structure

```
InterviewAI
│
├── Backend
│   ├── controllers
│   ├── routes
│   ├── models
│   └── server.js
│
├── Frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── services
│
├── .gitignore
├── LICENSE
└── README.md
```

---

# ⚙ Installation Guide

## 1 Clone Repository

```
git clone https://github.com/Siddhesh-1008/InterviewAI.git
```

---

## 2 Backend Setup

```
cd Backend
npm install
```

Create `.env` file

```
PORT=3000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
GENAI_API_KEY=your_ai_api_key
```

Run backend server

```
npm run dev
```

---

## 3 Frontend Setup

Open new terminal

```
cd Frontend
npm install
npm run dev
```

Frontend will run on

```
http://localhost:5173
```

---

# 📊 Example Output

The platform generates:

• Technical interview questions
• Behavioral interview questions
• Interview roadmap
• Skill gap suggestions
• Role match score

---

# 🔮 Future Scope

• AI mock interview simulation
• Voice based interview practice
• Resume improvement suggestions
• Multi-company interview preparation modules
• Integration with LinkedIn job postings
• AI based interview scoring system

---

# 👨‍💻 Author

**Siddhesh Sawant**

Graduate Computer Engineer
Full Stack Developer (Java + MERN)
