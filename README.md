# Shot Review Tracker

Built to explore fast, dependency-free dashboards for CSV-driven workflows.

A single-file, in-browser tool for tracking review status across a list
of shots (or any similar batch-review workflow). Drop in a CSV and get:

- A dashboard with approval rate, refinement rate, and auto-routing stats
- Filtered views: All Shots, Needs Refinement, Set to Plate, Sent to VFX
- Live search across every table
- Status chips for at-a-glance scanning
- Data persists locally (localStorage) — nothing is uploaded anywhere

Click **Load sample data** to see it populated with mock shots, or load
your own CSV (columns: Shot ID, Shot Name, Timecode In/Out, Character ID,
Character Name, Clip Status, Review Status).

Built as a single static HTML file — no build step, no dependencies.

<img width="1158" height="772" alt="Screenshot 2026-07-29 at 4 44 01 PM" src="https://github.com/user-attachments/assets/47698378-9cee-4ab4-a103-f11f9d4df93e" />

Built to explore fast, dependency-free dashboards for CSV-driven workflows.

## Getting started

No installation required — this is a single HTML file.

**Option 1: Just open it**
1. Download `shot-review-tracker.html` (or clone the repo)
2. Double-click it, or open it in any browser (Chrome, Firefox, Safari, Edge)

**Option 2: Clone and run**
```bash
git clone https://github.com/LauraMosquera99/Project_Status_tracker.git
cd Project_Status_tracker
open shot-review-tracker.html   # macOS
# or just double-click the file in Finder/Explorer
```

That's it — no `npm install`, no server, no build tools. Everything runs client-side in the browser.
