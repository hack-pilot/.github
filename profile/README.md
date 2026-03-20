# Hack Pilot 🚀

**Your AI-powered hackathon companion for tracking projects and seizing opportunities.**

Hack Pilot is an intelligent system that bridges your personal projects and the global hackathon ecosystem. We empower developers to never miss a submission deadline and provide AI-assisted project completion when time is running out.

---

## 🎯 Core Philosophy

**Projects are PRIMARY. Hackathons are SECONDARY.**

We believe the best projects start with *you* and your ideas—not with hunting for hackathons. Hack Pilot monitors your development progress and intelligently matches your projects against relevant hackathons in real-time.

---

## 📦 Our Repositories

### 1. **Backend** (`hackpilot`)
The intelligent core of Hack Pilot. Python-powered agent that monitors your GitHub repositories, estimates project completion %, matches projects to hackathons, and auto-generates submission materials.

**Tech Stack:**
- Python + Agno (agent framework)
- FastAPI (webhook server)
- Claude API (LLM)
- PostgreSQL + PgVector
- GitHub App integration

**Key Features:**
- 🤖 GitHub Bot — reads/writes your code via GitHub App
- 📋 Project Tracker — monitors commit velocity and estimates completion
- 🔍 Hackathon Scout — scrapes Devpost, MLH, Devfolio for matching hackathons
- ⏰ Deadline Engine — timezone-aware alerts with "point of no return" estimation
- 🧠 Code Completion Agent — auto-completes unfinished code and opens PRs
- 🚀 Submission Generator — auto-generates README and submission descriptions

**Repository:** [hack-pilot/hackpilot](https://github.com/hack-pilot/hackpilot)

---

### 2. **Dashboard** (`hackpilot-dashboard`)
The user-facing frontend built with Nuxt.js. A clean, modern interface for visualizing your project status, tracking deadlines, and managing hackathon submissions.

**Tech Stack:**
- Nuxt.js (Vue 3 framework)
- TypeScript
- Nuxt UI components

**Repository:** [hack-pilot/hackpilot-dashboard](https://github.com/hack-pilot/hackpilot-dashboard)

---

## 🎯 What Problems Do We Solve?

1. **Missing Deadlines** — Deadlines come and go, but Hack Pilot keeps you alert
2. **Project Abandonment** — Automatic code completion helps you push incomplete projects over the finish line
3. **Hackathon Discovery** — Find relevant opportunities without endless searching
4. **Submission Fatigue** — Auto-generate READMEs and submission descriptions
5. **Timezone Chaos** — Smart alerts that understand your timezone

---

## 🚀 Getting Started

### Backend Setup
See [hackpilot](https://github.com/hack-pilot/hackpilot) for detailed setup instructions.

### Dashboard Setup
See [hackpilot-dashboard](https://github.com/hack-pilot/hackpilot-dashboard) for installation and development instructions.

```bash
pnpm install
pnpm dev
```

---

## 💡 Vision

We're building the bridge between personal projects and global opportunities. In the future, Hack Pilot will be the invisible assistant that:
- Understands your coding patterns
- Predicts when you'll finish your projects
- Alerts you to hackathons matching your interests
- Automatically completes your code when deadlines loom
- Generates professional submissions with a single click

---

## 🤝 Contributing

We welcome contributions! Whether you're fixing bugs, adding features, or improving documentation:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📚 Documentation

- **Backend Docs:** See [hackpilot README](https://github.com/hack-pilot/hackpilot)
- **Dashboard Docs:** See [hackpilot-dashboard README](https://github.com/hack-pilot/hackpilot-dashboard)

---

## 📧 Questions?

Reach out through GitHub Issues or Discussions. We're here to help!

---

**Built with ❤️ for the hackathon community.**
