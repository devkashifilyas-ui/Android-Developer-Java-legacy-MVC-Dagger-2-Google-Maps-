
# GigAlert — (Demo)

GigAlert is a single-page interactive prototype that demonstrates a real-time job monitoring dashboard for Upwork-style freelance workflows.

This demo is designed as a systems-thinking artifact to showcase UI clarity, workflow efficiency, and rapid prototyping capability.

---

## Overview

GigAlert simulates a live job scanning environment with:

- Real-time scanning indicator
- Smart match scoring engine (visual representation)
- Skill-based tagging with highlight logic
- Budget and category filtering
- Client quality indicators
- Interactive job actions (Dismiss / Propose)
- Toast notifications
- Animated scan workflow with step-by-step log

This prototype is built as a single self-contained HTML file with embedded CSS and JavaScript. No external dependencies are required.

---

## Purpose

This demo is intended to:

- Demonstrate fast UI prototyping capability
- Show system-oriented thinking (monitor → filter → act)
- Illustrate clean frontend architecture in a compact format
- Serve as a portfolio artifact in proposals

It is not connected to the real Upwork API. All data is simulated for demonstration purposes.

---

## Features

### Dashboard

- Scanning status indicator with pulse animation
- 4 statistical cards (Matched Today, Proposals Sent, Avg Match Score, Connects Used)
- Sidebar filters for categories and budget tiers
- Alert configuration panel

### Job Cards

Each job includes:

- Match percentage bar
- Skill tags with match highlighting
- Client quality indicators
- Interactive buttons

### Interactions

- "Scan Now" triggers animated workflow simulation
- Category filtering dynamically updates job list
- Dismiss removes job from feed
- Propose triggers action toast notification

---

## How to Run

1. Open the HTML file in any modern browser.
2. No installation required.
3. To deploy:
   - Upload to GitHub
   - Enable GitHub Pages
   - Or deploy to Netlify / Vercel

---

## Deployment (GitHub Pages)

1. Push this file to a repository.
2. Go to Settings → Pages.
3. Select main branch.
4. Save.
5. Your demo will be live at:

   https://yourusername.github.io/repository-name/

---

## Tech Stack

- HTML5
- Modern CSS (Grid, Animations, Custom Properties)
- Vanilla JavaScript (No frameworks)

---

## Future Extensions

- Real Upwork RSS/API integration
- Supabase backend for saved alerts
- Proposal generator integration
- Email or push notification integration
- Match algorithm scoring engine
- User authentication layer
