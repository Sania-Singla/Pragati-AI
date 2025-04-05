# EduAI – Smart Doubt Resolution System

EduAI is an AI-powered web platform enabling real-time student doubt resolution and personalized test generation for teachers.

---

## 🖥 Frontend – React.js, Chart.js

- Built with React.js for responsive student-teacher interface.
- Chart.js used for interactive analytics visualizations.
- Students submit doubts; teachers track engagement, assign AI-curated tests.

---

## 🔁 Backend & APIs – Node.js, Express.js

- RESTful API using Node.js & Express.js.
- Handles sessions, doubts, topic mapping.
- Routes:   
  - GET / (live session)
  - GET /test  (for auto test generation)
  - GET /post  (for post analysis report of the session) 

---

## 🧠 AI/ML Engine – SBERT, FAISS, T5, RoBERTa, Hydra

- SBERT + FAISS: Semantic clustering of doubts.
- T5: Generates test questions.
- RoBERTa: Subject-wise classification.
- Hydra: Suggests concept re-explanations based on feedback.

---

## 🗃 Database – MongoDB

- Stores doubts, sessions, feedback, and generated content.
- Optimized for flexible schema and analytics queries.

---

## ☁ Cloud Infrastructure – Google Cloud Platform

- APIs & AI services hosted with load balancing and auto-scaling.
- Cloud storage supports image/media-based doubt inputs.

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm
- MongoDB

### Installation


npm install

#### Run Server

npm run dev


#### Build for Production

npm run build