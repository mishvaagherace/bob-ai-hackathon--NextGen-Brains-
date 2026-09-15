# MISSIONREADY AI
## Mission Readiness & Predictive Maintenance Copilot

A production-quality AI-powered mission readiness and predictive maintenance dashboard for military organizations.

---

## Getting Started

```bash
cd missionready-ai
npm install
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173)

**Demo credentials:** Any email + password (demo auth — no real credentials stored)

---

## Features

- **AI-powered fleet readiness** — Real-time health scores for 20+ assets
- **Predictive maintenance** — 9 predicted failures with failure probability and sensor analysis
- **AI Copilot** — Natural language interface for querying fleet status
- **Sensor Intelligence** — Interactive charts with anomaly detection
- **Maintenance Planner** — AI-prioritized maintenance schedule
- **Alert Center** — Severity-categorized real-time alerts
- **Analytics Dashboard** — Historical trends and performance metrics
- **Digital Twin View** — Component health visualization per asset
- **Dark/Light Mode** — Full theme toggle

---

## Project Structure

```
src/
  components/
    layout/     — Sidebar, TopNav
    ui/         — Toast, AssetDetailDrawer, AIAnalysisOverlay
  data/         — mockData.ts (20 assets, 9 failures, 22 maintenance records, 14 alerts)
  hooks/        — useAppContext (global state)
  layouts/      — AppLayout
  pages/        — All 9 pages + Login
  types/        — TypeScript type definitions
  utils/        — aiEngine, helpers
```

---

## Tech Stack

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Recharts
- Lucide React

---

> This is a decision-support and predictive maintenance prototype only.
> All data is simulated. No real military information is used.
