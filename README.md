# IIM Shillong Section 6 Attendance Tracker — V2

A polished, mobile-friendly attendance + timetable app for IIM Shillong PGP 2026–28 Term II, Section 6.

## V2 additions
- Dark mode
- Mobile navigation
- Attendance health / donut graphic
- Subject status badges
- Visual attendance heatmap
- Improved dashboard
- "Misses left" and limit status
- Timetable editor
- Subject/faculty/credit editor
- JSON export/import
- LocalStorage persistence

## Important
V2 intentionally uses the same localStorage key as V1 (`iim-shillong-attendance-v1`) so attendance already marked in V1 is preserved when you replace the website files.

## Update on GitHub Pages
Replace:
- index.html
- styles.css
- app.js

README.md is optional.

No build step is required.


## V2.1 cache fix
`index.html` loads CSS and JS with `?v=2.1.0` cache-busting parameters so GitHub Pages/browser caches cannot mix V1 and V2 assets after deployment.


## V2.2 fixes
- Next-class arrow/card now opens Attendance filtered to the next class date.
- Timetable calendar cards no longer show Present/Absent buttons.
- Date filter is persistent and Clear date now actually clears it.
- Today button directly applies today's date filter.


## V3 additions
- Today's classes directly on the dashboard with Present/Absent actions.
- "Can I miss my next class?" calculator.
- Subject risk/attention section.
- Attendance filters: subject, date, and status.
- One-click filter into a subject.
- Undo after marking attendance.
- Better daily workflow and mobile dashboard.
- Existing localStorage attendance key remains unchanged.
