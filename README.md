# 🎓 Tutor Bot — AI Tutoring Web Platform for University Faculty & Students

**Tutor Bot** is a mobile-first, production-ready AI tutoring platform designed for university professors and students. Faculty members can configure specialized AI tutors for their courses, upload sectioned course modules, establish custom guardrails, and generate unique student access codes. Students log in using their class code and interact with customized AI tutoring modes, including Socratic questioning, practice quizzes, and step-by-step guidance.

---

## 🌟 Key Features

### 🎓 **Instructor Portal**
* **Course & Class Management:** Create and manage university courses with unique class access codes (e.g. `NYU-CS101-2026`).
* **Sectioned Course Modules:** Upload syllabus materials, readings, and lecture notes organized by module.
* **Scaffolding & Help Level Controls:**
  * **Minimal Hints (High Independence):** Guides students with subtle nudges.
  * **Balanced Guidance:** Offers structured feedback and partial steps.
  * **Full Step-by-Step Explanations:** Complete detailed walk-throughs.
* **Tutoring Styles:**
  * **Socratic Method:** Teaches strictly through guided questioning.
  * **Friendly Mentor:** Conversational, encouraging, and supportive.
  * **Practice Quizmaster:** Tests student comprehension with interactive questions.
  * **Direct Instructor:** Formal academic style.
* **Safety Guardrails:**
  * Prevent direct homework/essay answer dumping.
  * Enforce academic honor code rules.
  * Restrict discussion strictly to course domain topics.

### 👨‍🎓 **Student Portal**
* **Class Code Login:** One-tap login using class access codes provided by professors.
* **Module Selection:** Choose specific course modules to study.
* **Interactive AI Chat:** Real-time conversation powered by **Gemini 3.1 Pro** (`gemini-3.1-pro-preview`) with automatic model fallbacks (`gemini-2.5-flash`, `gemini-2.0-flash`, `gemini-flash-latest`).
* **Audio Voice Playback:** Native ElevenLabs text-to-speech audio synthesis for tutor replies.

---

## 🔒 Security & Passcode
Protected by a SHA-256 client-side passcode lock (`Andizzle19902026!`) with encrypted API key management for Google Gemini and ElevenLabs.

---

## 🌐 Live Deployment
* **Live Web App:** [https://arclightinnovation.github.io/tutor-bot/](https://arclightinnovation.github.io/tutor-bot/)
* **Passcode:** `Andizzle19902026!`
