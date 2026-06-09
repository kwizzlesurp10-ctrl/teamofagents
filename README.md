# TeamOfAgents

**Production-Grade Multi-Agent Orchestration Platform**

A breathtaking, single-file HTML experience featuring a 5-step deployment wizard with LangGraph-style execution, real Google Drive persistence support, and a ready-to-deploy backend proxy.

## Live Experience

Open `index.html` directly in any modern browser (Chrome, Arc, Safari, Firefox).

## Key Features

- **5-Step Interactive Wizard**
  - Task definition
  - Agent team configuration
  - Dynamic plan review
  - Animated LangGraph node execution
  - Results + Real backend upload

- **LangGraph-Style Orchestration**
  - Visual state machine with live node activation
  - Streaming-style execution logs
  - Realistic metrics (tokens, cost, duration)

- **Real Google Drive Integration Ready**
  - Connected to your actual `TeamOfAgents_Deployments` folder
  - "Create & Upload Real File via Backend Proxy" button
  - Includes complete Vercel Edge Function code (copy & deploy in 2 minutes)

- **Zero Runtime Errors (v1.6)**
  - All event handlers properly scoped
  - Safe clipboard and button interactions

## Quick Start

1. Clone or download this repo
2. Open `index.html`
3. Run through the wizard
4. In Step 5, click **Create & Upload Real File via Backend Proxy**
5. Deploy the included proxy function for actual file creation in Google Drive

## Backend Proxy (Production)

The modal contains a complete, production-ready Vercel Edge Function that:
- Accepts POST requests with task data
- Authenticates with Google Service Account
- Creates timestamped JSON traces in your Drive folder

### Deploy the Proxy

1. Copy the code from the modal
2. Create a new Vercel project
3. Add environment variable: `GOOGLE_SERVICE_ACCOUNT` (your service account JSON)
4. Deploy
5. Update the proxy URL in the HTML if needed

## Tech Stack

- Pure HTML5, Tailwind CSS (via CDN), Vanilla JavaScript
- No frameworks, no build step
- Designed for easy extension to real LangGraph backend

## Repository

Created and pushed via AetherWeb Elite v4.2

**Repo:** https://github.com/kwizzlesurp10-ctrl/teamofagents

---

*Built for production autonomy. Ready for real backend integration.*