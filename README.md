# 🤖 InterviewPrep - AI-Powered Mock Interview Platform

![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vapi AI](https://img.shields.io/badge/Vapi_AI-Voice_Integration-blue?style=for-the-badge)

> **A sophisticated full-stack application that leverages GenAI and Voice AI to simulate real-time technical interviews.**

---

## 🚀 Overview

**InterviewPrep** addresses the anxiety and lack of feedback candidates face during job hunting. By integrating **Google Gemini** for intelligent question generation and **Vapi AI** for real-time voice interaction, this application provides users with a lifelike mock interview experience.

It’s not just a CRUD app; it's a complex integration of real-time audio streaming, LLM processing, and secure backend architecture.

### 🌟 Key Features

* **🎙️ Real-time Voice Interaction:** Users speak directly to the AI, which responds instantly with human-like latency using Vapi AI.
* **🧠 Context-Aware Questions:** Google Gemini generates technical questions dynamically based on the user's specified job role and experience level.
* **📊 Instant Feedback Loop:** Provides detailed feedback on answers, rating them on correctness and clarity.
* **🔐 Secure Authentication:** Robust user management and session handling via Firebase Auth.
* **📱 Responsive Dashboard:** A clean, accessible UI built with Tailwind CSS and Shadcn/UI for tracking interview history.

---

## 🛠️ Technical Architecture

This project demonstrates proficiency in building scalable, AI-driven web applications.

### Core Stack
* **Frontend:** Next.js 14 (App Router) for server-side rendering and optimized performance.
* **Language:** TypeScript for type safety and maintainable code.
* **Styling:** Tailwind CSS + Shadcn/UI for a modern, accessible component system.
* **Backend/BaaS:** Firebase (Firestore, Auth, Storage) for serverless scalability.
* **AI Integrations:**
    * **Vapi AI:** Handles voice-to-text, text-to-voice, and conversation flow.
    * **Google Gemini API:** Generates interview context and evaluates user responses.

### 💡 Challenges & Learnings
*(Recruiters love this section—it shows you understand your code)*

* **Handling Real-Time Audio:** Implemented low-latency voice streaming to ensure the "interviewer" doesn't lag, providing a natural conversation flow.
* **Prompt Engineering:** Designed robust system prompts for Gemini to ensure the AI acts strictly as a professional interviewer and provides constructive feedback.
* **State Management:** Managed complex application states (recording status, transcript generation, feedback loading) to ensure a smooth UX.

---

## 📸 Product Demo

Here is a glimpse into the user experience, showcasing the clean UI and complex real-time integrations.

<br/>

<div align="center">
  <h3>The User Dashboard</h3>
  <p><em>A central hub built with Shadcn/UI for tracking interview progress, analyzing average scores, and quickly initiating new sessions.</em></p>
  <img src="./dashboard-preview-1.png" alt="InterviewPrep Dashboard" width="850" />
</div>

## 🤸 Getting Started locally

To run this project dynamically on your local machine:

**1. Clone the repository**
```bash
git clone [https://github.com/anupam-iiitm/InterviewPrep.git](https://github.com/anupam-iiitm/InterviewPrep.git)
cd InterviewPrep
