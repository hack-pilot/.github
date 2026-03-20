# Hack Pilot 🚀

**Your intelligent hackathon companion for tracking projects and seizing opportunities.**

Hack Pilot bridges your projects and the hackathon ecosystem. We empower developers to never miss deadlines and provide agent-assisted completion when time is running out.

---

## 🎯 Core Philosophy

**Projects are PRIMARY. Hackathons are SECONDARY.**

Best projects start with *you* and your ideas—not hunting for hackathons. Hack Pilot monitors progress and matches your projects to relevant hackathons in real-time.

---

## 📦 Our Repositories

### 1. Backend (`hackpilot`)
Intelligent Python agent that monitors GitHub repos, estimates completion %, matches projects to hackathons, and auto-generates submissions.

**Tech Stack:**
- Python + Agno (agent framework)
- FastAPI (webhook server)
- Claude API (LLM)
- PostgreSQL + PgVector
- GitHub App integration

**Key Features:**
- 🤖 GitHub Bot — reads/writes code via GitHub App
- 📋 Project Tracker — monitors velocity and estimates completion
- 🔍 Hackathon Scout — scrapes Devpost, MLH, Devfolio
- ⏰ Deadline Engine — timezone-aware alerts
- 🧠 Code Completion Agent — auto-completes unfinished code
- 🚀 Submission Generator — auto-generates README and descriptions

**Repo:** [hack-pilot/hackpilot](https://github.com/hack-pilot/hackpilot)

---

### 2. Dashboard (`hackpilot-dashboard`)
Modern Nuxt.js frontend for visualizing project status, tracking deadlines, and managing submissions.

**Tech Stack:**
- Nuxt.js (Vue 3)
- TypeScript
- Nuxt UI components

**Repo:** [hack-pilot/hackpilot-dashboard](https://github.com/hack-pilot/hackpilot-dashboard)

---

## 🎯 What Problems Do We Solve?

1. **Missing Deadlines** — Hack Pilot keeps you alert
2. **Project Abandonment** — Agent completion helps finish projects
3. **Hackathon Discovery** — Find opportunities without endless searching
4. **Submission Fatigue** — Auto-generate READMEs and descriptions
5. **Timezone Chaos** — Smart timezone-aware alerts

---

## 🚀 Getting Started

**Backend:** See [hackpilot](https://github.com/hack-pilot/hackpilot) for setup.

**Dashboard:**
```bash
pnpm install
pnpm dev
```

---

## 💡 Vision

Building the bridge between projects and opportunities. Hack Pilot will be the invisible agent that:
- Understands your coding patterns
- Predicts project completion time
- Alerts you to matching hackathons
- Auto-completes code before deadlines
- Generates submissions with one click

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Push and open a Pull Request

---

**Built with ❤️ for the hackathon community.**
