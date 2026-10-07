# AAGS-Planner

AAGS-Planner is a lightweight, browser-based academic planning tool for the Associate of Arts, General Studies (AAGS) degree pathway at Southeastern University (SEU). It helps students map out required courses across Challenge II through IV, track progress, and prepare print-ready plans for advising or personal planning.

This project is intentionally simple: it is a single-page HTML application with no build step, no framework, and no backend dependencies. Open it in a browser and start planning immediately.

## What it does

- Displays a full AAGS degree grid spanning Challenge II through IV
- Tracks how many courses have been placed in the plan
- Highlights the current term and past terms visually
- Lets users assign or remove courses in the planner grid
- Supports reset, export, and import of saved planning data as JSON
- Allows exporting the plan as PDF or PNG for print/display purposes
- Provides a clean, printable layout optimized for academic planning

## Degree planner overview

The planner is built around the SEU AAGS program structure and includes:

- 61 credit hours total
- 21 courses
- Challenge II, III, and IV terms
- Course placement across terms and categories
- Unofficial planning guidance only

## Important note

This tool is an independent, community-created planner and is not officially sanctioned, maintained, or supported by Classical Conversations (CC) or Southeastern University. It is meant for unofficial academic planning and self-organization.

## Repository contents

- `index.html` — the full application UI, styles, and logic in one file
- `README.md` — project overview and instructions

## How to use

1. Open `index.html` in a browser.
2. Select a current term from the dropdown if you want to highlight your active planning period.
3. Click courses in the side list and place them into the term grid.
4. Remove courses by clicking the course chip and selecting the remove option.
5. Use the buttons to:
   - Print / Save as PDF
   - Save as PNG
   - Export JSON
   - Import JSON
   - Reset the plan

## Local usage

Because this is a static HTML app, you do not need a framework or server:

- Double-click `index.html`, or
- Serve it locally with a simple static server if preferred

Example using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Files and responsibilities

- `index.html` contains the application structure, styling, data, and JavaScript behavior.
- The planner is designed to be easy to edit for adjusting degree requirements, course lists, or layout behavior.

## Typical workflow

- Start with a blank plan
- Place required courses in the appropriate challenge/term slots
- Track completed or upcoming coursework
- Export to JSON for saving progress
- Print or export a clean copy for advising or personal reference

## Project status

This repository is a focused, static planning tool for academic scheduling. It is intentionally lightweight and easy to use without installation overhead.

## License

No explicit license is currently provided in this repository.
