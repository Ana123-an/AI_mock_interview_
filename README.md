
<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="next.js" />
    <img src="https://img.shields.io/badge/-Vapi-white?style=for-the-badge&color=5dfeca" alt="vapi" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=DD2C00" alt="firebase" />
  </div>

  <h2 align="center">🧠 Prepwise — AI-Powered Interview Preparation Platform</h2>
  <p align="center">An intelligent, voice-interactive mock interview platform built using <b>Next.js</b>, <b>Firebase</b>, <b>TailwindCSS</b>, and <b>Vapi AI</b>.</p>
</div>

---

## 📘 Overview

**Prepwise** is an AI-driven job interview preparation platform designed to help users simulate real interviews through **voice interaction**.  
It enables users to create AI-led mock interviews, get instant performance feedback, and track their progress through an intuitive dashboard.

Built with **Next.js** for frontend and backend logic, **Firebase** for authentication and data storage, **TailwindCSS** for styling, and **Vapi AI** for intelligent voice interview interactions.

---

## ⚙️ Tech Stack

- **Next.js** – Frontend & backend framework  
- **Firebase** – Authentication and database  
- **Tailwind CSS** – Modern and responsive styling  
- **Vapi AI** – Voice interview assistant  
- **Google Gemini** – AI model for generating feedback and questions  
- **shadcn/ui** – Reusable UI components  
- **Zod** – Data validation

---

## 🌟 Features

✅ **User Authentication** – Secure signup and login using Firebase  
✅ **AI Interview Simulation** – Conduct interviews using voice-based AI agents  
✅ **Smart Feedback System** – Get structured AI feedback with performance breakdowns  
✅ **Interview Dashboard** – Manage, review, and retake interviews easily  
✅ **Custom Interview Generation** – Generate interviews based on role, experience, and tech stack  
✅ **Responsive UI** – Optimized for all screen sizes  
✅ **Elegant Design** – Professional and intuitive user experience  

---

## 🚀 Getting Started

### Prerequisites

Before starting, ensure you have installed:

- [Node.js](https://nodejs.org/en) (v18+)
- [Git](https://git-scm.com/)
- npm or yarn package manager

---

### 🧩 Installation

**1️⃣ Clone the repository**

```bash
git clone https://github.com/<your-username>/prepwise.git
cd prepwise
````

**2️⃣ Install dependencies**

```bash
npm install
```

**3️⃣ Setup environment variables**

Create a file named `.env.local` in the root directory and add your credentials:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=http://localhost:3000

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

---

### ⚡ Run the Project

Start the development server:

```bash
npm run dev
```

Visit the app at 👉 [http://localhost:3000](http://localhost:3000)

---

## 💡 Key Functionalities

### 🎤 AI Mock Interviews

Prepwise integrates with **Vapi Voice AI** to create realistic, conversational mock interviews for specific roles, experience levels, and technology stacks.

### 📊 AI Feedback System

After every interview, the system uses **Google Gemini** to analyze the transcript and provide structured feedback across:

* Communication Skills
* Technical Knowledge
* Problem-Solving
* Role Fit
* Confidence & Clarity

### 🧭 Dashboard

A clean dashboard lets users:

* View all past interviews
* Track feedback scores
* Retake interviews anytime

---

## 🧱 Project Structure

```
prepwise/
│
├── app/
│   ├── (auth)/           # Login & signup pages
│   ├── (root)/           # Dashboard, Interview pages
│   ├── api/              # Backend API routes
│
├── components/           # Reusable UI components
├── lib/                  # Helper utilities and constants
├── public/               # Assets (icons, images)
├── styles/               # Tailwind CSS setup
└── .env.local            # Environment variables
```

---

## 🧠 Example Commands

**Generate interview questions (API prompt):**

```javascript
`Prepare questions for a job interview for the role of ${role}. 
Experience Level: ${level}. 
Tech Stack: ${techstack}. 
Focus: ${type}. 
Number of Questions: ${amount}. 
Return in JSON format: ["Question 1", "Question 2", ...]`
```

**Generate feedback:**

```javascript
"You are an AI interviewer analyzing this transcript. 
Score the candidate from 0–100 across Communication, Technical Knowledge, Problem-Solving, Role Fit, and Confidence. 
Be detailed, objective, and specific in feedback."
```

---

## 🧾 Dummy Data Example

```javascript
export const dummyInterviews = [
  {
    id: "1",
    role: "Frontend Developer",
    type: "Technical",
    techstack: ["React", "Next.js", "Tailwind CSS"],
    level: "Junior",
    questions: ["What is React?"],
    finalized: false,
  },
  {
    id: "2",
    role: "Full Stack Developer",
    type: "Mixed",
    techstack: ["Node.js", "MongoDB", "React"],
    level: "Senior",
    questions: ["What is Node.js?"],
    finalized: false,
  },
];
```

---

## 🧩 Assets

All public assets used in the project can be found in the `/public` folder or configured under `public/assets/`.

---

## 🧭 Future Enhancements

* Integration with real-time analytics dashboard
* Exportable performance reports
* Personalized AI coaching suggestions
* Multi-language support
* Community leaderboard

---

## 🧑‍💻 Author

**Developed by [Ananya Mishra](https://github.com/Ana123-an)**
A passionate developer building intelligent web applications powered by AI and cloud technologies.

---

## 🪪 License

This project is open-source and available under the **MIT License**.

---

### 🌐 Live Demo (Localhost)

Run locally: [http://localhost:3000](http://localhost:3000)

---

```

---

✅ Just copy and paste this into your `README.md` — it’s already formatted for GitHub display with badges, headings, and clean sections.  
Would you like me to add **screenshots section placeholders** (like “📸 Preview Screens”) too? It improves the look for when you add images later.
```
