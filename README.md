# 📌 Smart Recruitment Platform – PFE

**Projet de Fin d’Études (PFE)**: Développement d’une plateforme de recherche d’emploi intégrant l’intelligence artificielle pour optimiser le processus de recrutement.

---

## 🧠 Project Overview

This platform aims to simplify recruitment by providing:

- **Intelligent Matching**: Uses cosine similarity between candidate CVs and job postings to suggest the best matches.  
- **Salary Suggestions**: AI-based model estimates competitive salaries for job offers.  
- **Candidate Features**: Apply to jobs, track applications, view suggested positions.  
- **Recruiter Features**: Post job offers, filter and select candidates, analyze matches.  

---

## ⚙️ Technologies

- **Backend**: Django REST Framework (DRF) – handles APIs, database models, and AI integration.  
- **Frontend**: React – responsive UI for candidates and recruiters.  
- **AI/ML**: Pre-trained models for similarity computation and salary prediction.  
- **Database**: PostgreSQL (or your chosen DB).  
- **Authentication**: JWT tokens for secure login.  

---

## 🏗 Features

### For Candidates

- Browse and search for job offers.  
- Receive AI-based job recommendations.  
- Apply to jobs and track application status.  

### For Recruiters

- Post and manage job offers.  
- View candidate profiles and AI match scores.  
- Filter candidates by skills, experience, and match ranking.  

### AI Features

- **CV/Job Matching**: Computes similarity between candidate CV text and job description using cosine similarity.  
- **Salary Estimation**: Provides suggested salaries based on job type, location, and market data.

---

## 💻 Installation & Setup

1. **Clone the repository**:

```bash
git clone https://github.com/HajarEssaoudi/jobLib
cd joblib
```
2. **Backend Setup**:
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
3. **Frontend Setup:**:
```bash
cd frontend
npm install
npm start
```
4. **Access the app:**:

- Frontend: http://localhost:3000
- Backend API: http://localhost:8000/api

## 🧵 Learning Outcomes

- Building a full-stack web application with **Django REST Framework** and **React**.
- Integrating **AI/ML models** for real-world applications.
- Handling **user authentication** and role-based access (candidates vs recruiters).
- Managing relational data effectively with PostgreSQL.
- Implementing modular, maintainable, and scalable code architecture.
- Understanding the challenges of **matching algorithms** and recommendation systems.








