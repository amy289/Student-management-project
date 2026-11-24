# Lab 6 — Student Management Frontend
A responsive browser-based student management project using HTML5, CSS3 and JavaScript.

## Features
- Add, view, edit and delete student records (client-side CRUD)
- Search by name, email, student ID or department
- Department and semester filters; sort by name or semester
- Required-field and email validation; duplicate ID/email checks
- Student objects stored in an array and persisted as JSON in localStorage
- Dynamic table updates without page reload
- Record count cards, JSON import/export, pagination and last-10 activity log

## Run
1. Extract this ZIP.
2. Open `index.html` in Chrome or Edge.
3. Add a student and refresh the page to confirm localStorage persistence.

No PHP or MySQL is required. This is a static frontend and can be hosted on GitHub Pages.

## GitHub upload
Upload the **contents of this folder** to the repository root. `index.html` must be at the root, alongside the `css` and `js` folders. Then use Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Data note
Data is stored only in the current browser's localStorage; it does not sync across devices. Export JSON for a backup.
