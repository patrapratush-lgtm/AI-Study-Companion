# 🎓 AI Study Companion

## 📌 Overview

AI Study Companion is a full-stack intelligent web application designed to help students study more effectively by tracking academic performance, analyzing quiz mistakes, and generating personalized study plans.

Many students struggle to remember weak topics and maintain consistent study habits. This application solves that problem by acting as a smart digital study assistant that monitors learning progress and provides actionable recommendations.

The system combines quiz analytics, progress visualization, and AI-style study planning to create a personalized learning experience for each user.

---

## 🎯 Problem Statement

Students often face the following challenges:

- Forgetting topics they struggle with
- Repeating the same mistakes during exams
- Lack of structured study planning
- No performance tracking system
- Poor revision management

Traditional study methods do not adapt to individual learning patterns.

---

## 💡 Solution

AI Study Companion provides:

- Performance tracking through quizzes
- Automatic weak subject detection
- Personalized study task generation
- Progress analytics dashboards
- Persistent user data storage

The platform helps students understand **what to study**, **when to study**, and **how to improve**.

---

## 🚀 Key Features

### 🔐 Authentication System
- User Sign Up and Login
- Backend-based authentication
- User-specific data isolation
- Persistent accounts

---

### 📊 Dashboard
- Welcome banner
- Subject performance cards
- Progress bars per subject
- Recent quiz results
- Daily study goals
- Upcoming deadlines overview

---

### 🧠 Quiz Module
- Multiple subjects available
- Multiple-choice questions (MCQs)
- Real-time answer feedback
- Automatic score calculation
- Quiz results saved automatically

---

### ❌ Mistake Tracking
- Stores incorrect answers
- Tracks chosen vs correct answers
- Helps identify weak concepts
- Used for study plan generation

---

### 📚 AI Study Plan
Study plans support:

✅ Auto-generated tasks based on weak subjects  
✅ Manual task creation by users  

Each task includes:
- Subject
- Task description
- Priority level
- Completion status
- Creation date

---

### 📈 Progress Analytics
- Subject-wise performance charts
- Quiz history table
- Score trends over time
- Study streak counter
- Learning progress monitoring

---

## 🏗️ System Architecture


User Interface (Frontend)
↓
Application Logic
↓
Motoko Backend Services
↓
Persistent Data Storage



The frontend communicates with backend services that securely store and retrieve user learning data.

---

## 🗄️ Database Models

### Users
Managed through backend authorization system.

### QuizResults
- userId
- subject
- score
- totalQuestions
- date

### WrongAnswers
- userId
- subject
- question
- chosenAnswer
- correctAnswer
- date

### StudyPlanItems
- userId
- subject
- taskDescription
- priority
- completionStatus
- createdDate

### ProgressHistory
- userId
- subject
- scoreSnapshots

---

## 🛠️ Technology Stack

| Layer | Technology |
|------|------------|
| Frontend | Modern Web UI |
| Backend | Motoko |
| Authentication | Authorization Component |
| Storage | Persistent Backend Database |
| Deployment | Web Platform Hosting |

---

## ⚙️ Application Workflow

1. User creates an account or logs in.
2. Dashboard loads personalized data.
3. User takes quizzes by subject.
4. Results and mistakes are saved automatically.
5. Weak subjects are identified.
6. Study plan tasks are generated.
7. Progress analytics update dynamically.

---

## 🎯 Project Objectives

- Improve student learning efficiency
- Provide data-driven study recommendations
- Encourage consistent study habits
- Track academic improvement over time
- Demonstrate practical AI-assisted learning systems

---

## 🔮 Future Enhancements

- Real AI model integration
- AI-generated revision questions
- Smart exam reminder notifications
- Adaptive quiz difficulty
- Mobile application version
- Cloud analytics integration

---

## 📷 Application Pages

- Landing Page & Authentication
- Student Dashboard
- Quiz Interface
- Study Plan Manager
- Progress Analytics Page

---

## 🧪 Use Cases

- Students preparing for exams
- Self-paced learners
- Academic performance tracking
- Personalized revision planning

---

## 👨‍💻 Author

**AI Study Companion**  
Developed as an Academic Artificial Intelligence Project.

---

## 📄 License

This project is created for educational and learning purposes.
