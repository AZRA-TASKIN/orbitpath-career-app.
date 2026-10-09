# OrbitPath — Career, in Motion

OrbitPath is an independent career-planning and internship-discovery MVP. It is a fresh brand and implementation, not branded as SkillBridge.

## Included
- Personalized rule-based roadmaps for AI/ML, data, backend, full-stack, cybersecurity and cloud/DevOps.
- Learning resources and portfolio project ideas for each track.
- Live, one-column resume preview with print-to-PDF and downloadable HTML export.
- Internship and job search links for Internshala, LinkedIn, Naukri, Indeed, Wellfound and general job search.
- Direct career portals for selected companies.
- Skills portfolio with self-reported, project-supported and assessment-verified labels.
- Short AI/ML fundamentals quiz with explanations.
- Local application tracker with status and follow-up dates, plus CSV export.
- Browser-local persistence using localStorage.

## Run locally
1. Unzip the project.
2. Open `index.html` in a modern browser, or open the folder in VS Code and run it with the Live Server extension.
3. No npm install or API key is required for this prototype.

## Current prototype limits
- The roadmap is a curated rules-based plan, not a connected generative AI service.
- Job links open third-party search pages. The app does not scrape live job listings or submit applications.
- Data is saved locally in the current browser only. It is not synced between devices and there are no user accounts or backend API.
- Evidence labels are user-entered; the app does not issue professional credentials or independently verify external claims.

## Before production
Add authenticated accounts, encrypted backend storage, privacy and deletion controls, server-side APIs for any licensed job data, a connected AI model with structured output validation, a tested resume parser, employer challenge flows, accessibility checks and automated tests. Review each job provider's terms before integrating data feeds.
