# PlaceMate AI – Intelligent Placement Assistance Platform

PlaceMate AI is a full-stack placement assistance platform designed to simplify campus recruitment by connecting students, recruiters, and administrators through a centralized system.

The platform combines resume analysis, job matching, skill-gap analysis, and recruitment management to make the placement process more organized and data-driven.

## Key Features

### Student Module

- Student registration, login, and profile management.
- Browse and explore available job opportunities.
- Apply for jobs and track application status.
- Upload and analyze resumes.
- Resume-to-job matching using TF-IDF and cosine similarity.
- Skill extraction and skill-gap analysis.
- Career recommendations based on existing skills.

### Recruiter Module

- Recruiter dashboard.
- Create, update, and manage job postings.
- View applicants and their resume match scores.
- Update application statuses.
- Manage recruitment rounds and interview feedback.

### Admin Module

- Centralized administrative dashboard.
- Manage students and recruiters.
- Manage companies and job postings.
- Monitor applications.
- Manage job and user statuses.

### AI-Powered Features

- Resume parsing and information extraction.
- Skill extraction using NLP techniques.
- Resume and job-description similarity scoring.
- Skill-gap analysis.
- Career recommendations.

## Technology Stack

| Component         | Technologies                      |
| ----------------- | --------------------------------- |
| Frontend          | React.js, JavaScript, CSS         |
| Build Tool        | Vite                              |
| Backend           | Python, Flask                     |
| Database          | SQLAlchemy, relational database   |
| Authentication    | JWT                               |
| AI / NLP          | Python, TF-IDF, Cosine Similarity |
| Resume Processing | PDF and TXT parsing               |
| Version Control   | Git and GitHub                    |

## Project Structure

```text
PlaceMate/
│
├── backend/
│   ├── app/
│   │   ├── ai/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   └── utils/
│   ├── migrations/
│   ├── requirements.txt
│   └── run.py
│
├── database/
│   ├── schema.sql
│   └── seed_data.py
│
├── docs/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
│   ├── package.json
│   └── package-lock.json
│
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.12+
- Node.js and npm
- A configured relational database
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/isshhiittaaa/PlaceMate-AI.git
cd PlaceMate-AI
```

### 2. Backend Setup

```powershell
cd backend
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Configure your backend environment variables in a local `.env` file according to the application's configuration. Do not commit this file.

Start the Flask server:

```powershell
flask --app "app:create_app" run --debug
```

Backend URL: `http://127.0.0.1:5000`

### 3. Frontend Setup

Open a separate terminal:

```powershell
cd frontend
npm install
npm run dev
```

Frontend URL: `http://localhost:5173`

## Current Development Status

- [x] Student, recruiter, and admin modules.
- [x] Authentication and role-based access.
- [x] Job posting and application management.
- [x] Resume parsing and skill extraction.
- [x] Resume-job similarity scoring.
- [x] Skill-gap analysis and career recommendations.
- [x] Recruitment round management.
- [ ] Generative AI-powered career assistance.
- [ ] AI-driven mock interview preparation.
- [ ] Personalized AI learning roadmaps.

## Future Enhancements

- Generative AI career mentor chatbot.
- AI-assisted resume improvement and job-description tailoring.
- Personalized skill development roadmaps.
- AI-generated mock interview questions and feedback.
- Retrieval-Augmented Generation (RAG) for contextual career guidance.

## Author

**Ishita Srivastava**
B.Tech – Computer Science and Engineering
KIIT University

GitHub: [@isshhiittaaa](https://github.com/isshhiittaaa)

---

*PlaceMate AI – Making campus placements smarter, more organized, and more accessible.*
