# WeathrBug 🌦️

Smart, AI-powered weather-based event scheduler with disaster prediction.  
Built with **Next.js**, **Tailwind CSS**, and **Supabase**.

---

## 📖 Project Overview
WeathrBug is a smart web app that helps users plan events around the weather.  
It integrates real-time weather forecasts, historical climate data, and disaster prediction models to recommend safe event windows and send proactive alerts.  

Core features:
- Weather-aware event scheduling
- Calendar integrations
- Disaster prediction and early warnings
- AI-driven natural language summaries and recommendations

---

## 🚀 Project Plan

### Title
**WeathrBug — Smart Weather-based Event Scheduler**

### Description
WeathrBug combines accurate weather data, historical patterns, and AI-powered forecasting to provide users with actionable insights when scheduling events. The platform acts as a personal "Mother Nature assistant" that not only forecasts the weather but also predicts disaster risks, enabling safer and more reliable planning.

### Roadmap (Living Document)
- **Phase 0:** Project setup (Next.js, Tailwind, Supabase, CI/CD, linting, type checks)  
- **Phase 1:** Event CRUD, Auth, Calendar integration  
- **Phase 2:** Weather data ingestion & simple rule-based alerts  
- **Phase 3:** AI/ML pipeline for forecasting & disaster prediction  
- **Phase 4:** AI-assisted development & testing integration (Copilot/LLMs)  
- **Phase 5:** Public beta release  

---

## 🛠️ Tech Stack

### Frontend
- [Next.js](https://nextjs.org/) — React framework with server-side rendering  
- [Tailwind CSS](https://tailwindcss.com/) — utility-first styling  

### Backend
- [Supabase](https://supabase.com/) — Postgres, Auth, Realtime, Edge Functions, Vector DB  

### Deployment & CI/CD
- [Vercel](https://vercel.com/) — frontend hosting  
- [GitHub Actions](https://github.com/features/actions) — CI/CD pipeline  

### Observability
- [Sentry](https://sentry.io/) — error monitoring  
- Supabase logs & analytics  

---

## 🤖 AI Integration Strategy

AI will play two major roles in the project:  
1. **Developer Productivity**  
   - Code generation, boilerplate scaffolding, and schema-aware coding with **GitHub Copilot / LLMs**  
   - Automated test generation and suggestions in PRs  
   - AI-assisted documentation and changelog drafting  

2. **Product Features**  
   - Natural language weather summaries (“Is it safe to host a picnic on June 7?”)  
   - Disaster prediction via hybrid models (rules + ML forecasting)  
   - Event risk scoring and personalized recommendations  

### AI for Development
- **Code Generation:** LLM-based assistants for generating repetitive code, API routes, and test scaffolding.  
- **Testing:** AI-driven generation of unit, integration, and E2E tests. Human reviewers validate before merging.  
- **Documentation:** Auto-generate API docs, inline comments, and PR summaries with LLMs.  

---

## ✅ Testing & Quality Assurance
- **Unit Tests:** Jest + React Testing Library  
- **Integration Tests:** Supertest / Playwright against Supabase previews  
- **End-to-End Tests:** Playwright browser flows (auth, event scheduling, alerts)  
- **AI-Assisted Tests:** LLM-suggested cases run in sandbox; flagged for human approval  
- **CI Pipeline:** lint → typecheck → build → test → AI-suggestions → deploy  

---

## 🔐 Security & Privacy
- Supabase Auth + Row Level Security  
- Data minimization principles (only store necessary info)  
- Encrypted backups & point-in-time recovery  

---

## 📅 Roadmap & Milestones
- [ ] **M1:** Repo setup, base stack integration  
- [ ] **M2:** Event scheduling + calendar sync  
- [ ] **M3:** Weather ingestion + rule-based alerts  
- [ ] **M4:** AI-powered forecasting + disaster predictions  
- [ ] **M5:** Beta launch with monitoring + observability  

---

## 📂 Project Structure (proposed)


---

## 🙌 Contributing
Contributions are welcome!  
Please open an issue or submit a PR. AI-generated contributions must always be reviewed by a human before merging.  

---

## 📜 License
MIT License © 2025 WeathrBug
