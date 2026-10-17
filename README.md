# JobTrack

JobTrack is a responsive job application tracker built with React and Vite. It provides a dashboard for reviewing application progress, managing job entries, and viewing application details.

## Features

- Dashboard with total, applied, interview, and rejected application counts.
- Recent applications preview showing up to four entries.
- Dedicated page for browsing all applications.
- Add application form with job, company, location, status, date, URL, and notes fields.
- Application details page with status updates, editable job information, notes, and activity.
- Settings screen with Profile, Notifications, Appearance, and Security sections.
- Responsive layouts for desktop, tablet, and mobile screens.

## Tech stack

- React
- Vite
- Lucide React icons
- ESLint

## Getting started

### Prerequisites

- Node.js compatible with Vite 8
- npm

### Install and run locally

```bash
git clone https://github.com/ZumarArshad/Job-tracker-application.git
cd Job-tracker-application
npm install
npm run dev
```

Vite prints the local development URL in the terminal.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the local development server |
| `npm run build` | Create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Project structure

```text
src/
├── components/       # Shared dashboard, navigation, and application components
├── pages/            # Dashboard, applications, details, add form, and settings
├── App.jsx           # App state and page navigation
├── App.css           # Main application layout
└── index.css         # Global styles and design tokens
```

## Data and persistence

This project currently runs entirely in the browser and does not connect to a backend. Application records and settings are held in React state, so changes are not retained after a page reload. The settings and security screens are frontend UI and do not update a server-side account.
