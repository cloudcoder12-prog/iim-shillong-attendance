# IIM Shillong Section 6 Attendance Tracker

A zero-backend attendance + timetable web app for IIM Shillong PGP 2026–28 Term II, Section 6.

## Features
- Dashboard with overall and subject-wise attendance
- Present/Absent/Reset for current and previous classes
- "Classes you can still miss" based on your rules
- Section 6 timetable loaded from the supplied Term II schedule
- Timetable editor: add, edit, delete classes
- Subject/faculty/credit editor
- Editable attendance rules
- LocalStorage persistence
- JSON export/import backup
- GitHub Pages friendly: plain HTML/CSS/JS, no build step

## Initial rules
- 4 credits: can miss 3 classes
- 2 credits: can miss 2 classes

## GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, and `app.js`.
3. Repository → Settings → Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, folder: `/ (root)`.
6. Save. GitHub will give you the Pages URL.

## Important
The timetable is editable from the website, so a revised institute timetable does not require code changes.

Attendance is stored in the browser's localStorage. Use **Settings → Export JSON** before changing devices/browser data.
