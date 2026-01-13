Milestone aka Egoistic 

Milestone is a personal daily tracking web application that helps you evaluate, reflect, and visualize your life consistency over time. It combines a calendar-based rating system, journaling, streak tracking, and yearly heatmap visualization in a clean, themeable interface.

The application runs entirely in the browser and stores all data locally using localStorage.

Features
📅 Daily Rating & Journal

Rate each day from 1 to 5 using a color-coded intensity scale.

Add optional journal notes for any day.

Past entries older than two days automatically switch to read-only mode.

🔥 Streak Tracking

Displays:

Current streak

Longest streak

Total active days

Encourages consistency and habit formation.

📊 Yearly Heatmap

Visual overview of the entire year.

Each day is color-coded based on your rating.

Quickly identifies productive vs low-activity periods.

📈 Distribution Analysis

Breaks down your day ratings (1–5).

Shows how often you are in high-performance vs low-performance states.

Generates motivational feedback based on trends.

🎨 Themes & Fonts

Multiple built-in themes:

Antique

Traditional

Charcoal & Orange

Charcoal & Wine

Midnight

Multiple font styles including script, serif, and monospace.

All visual preferences are saved automatically.

🎯 Goal Countdown

Set a target date.

Displays the number of days remaining.

Useful for deadlines, challenges, or long-term goals.

📤 Backup & Restore

Export your entire dashboard data as a JSON file.

Import backups to restore or migrate data between devices.

📸 Share Mode

Generates a clean, presentation-style layout.

Hides controls and focuses on streaks and calendar for screenshots or sharing.

How It Works

No backend. No accounts. No tracking.

All data is stored locally in the browser using:

localStorage

Data structure:

Daily entries: { score, note }

Settings: theme, font, goal name, target date

File Structure
/ (root)
│
├── index.html        # Main application
├── manifest.json     # PWA metadata
├── icon-192.png      # App icon (required)
└── icon-512.png      # High-resolution app icon

Progressive Web App (PWA)

This project supports installation as a standalone app.

Install:

Open the site in Chrome or Edge.

Click Install App in the address bar.

Or use Add to Home Screen on mobile.

PWA Capabilities:

Runs in standalone mode

Custom app icon

Theme color integration

Works offline (data stored locally)

Usage

Click any date in the calendar.

Rate your day from 1 (worst) to 5 (best).

Optionally write a journal note.

Save.

Track streaks, review heatmaps, and adjust themes in Settings.

Limitations

Data is device-specific (stored in browser).

Clearing browser storage will erase all data unless backed up.

No cloud sync (by design).

Ideal Use Cases

Daily productivity tracking

Habit building

Self-reflection journaling

Goal-focused challenges

Personal performance visualization

License

This project is open for personal use and learning purposes.
If you plan to modify or redistribute, add a license file accordingly.