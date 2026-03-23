# AI Study Companion

## Current State
New project with no existing application files.

## Requested Changes (Diff)

### Add
- Student login and signup pages with authorization
- Dashboard with subjects, quiz scores, study streak, and weak topics
- Quiz feature: take quizzes by subject, submit answers, view score, track wrong answers
- Study Plan page: personalized study suggestions based on quiz performance
- Progress page: charts/stats showing quiz history and improvement over time
- Sidebar navigation: Dashboard, Quiz, Study Plan, Progress
- Sample/seed data for subjects and quizzes

### Modify
N/A (new project)

### Remove
N/A (new project)

## Implementation Plan
1. Backend (Motoko)
   - User profiles linked to authorization principal
   - Subjects data store with name and metadata
   - Quiz store: questions per subject, options, correct answer
   - Quiz results store: user, subject, score, wrong answers, timestamp
   - Study plan store: suggested topics per user based on quiz results
   - CRUD APIs: getSubjects, getQuizBySubject, submitQuizResult, getQuizHistory, getWeakTopics, getStudyPlan
   - Seed example subjects and quiz questions
2. Frontend (React + Tailwind)
   - Auth flow: Login / Signup pages
   - App shell: fixed sidebar + main content area
   - Dashboard page: welcome banner, subjects grid with progress, recent scores, daily goals
   - Quiz page: select subject, answer MCQs, submit, view score and wrong answers
   - Study Plan page: list recommended revision topics
   - Progress page: quiz history table and simple visual stats
   - Responsive design for mobile and desktop
