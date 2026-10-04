# Email Activity Tracker

## Overview

A single-page, offline-capable tracker for logging when and how long you used an email account and which platforms you used.

## Purpose

Gives a private way to record and review account activity without any server.

## Features

- Dashboard, Add Activity, History, Data Management and Privacy views
- Activity form: email, date, end time, comeback time (duration calculated), platforms (ChatGPT, Gmail, Google Drive, YouTube, custom, etc.), notes, custom fields
- List and calendar history views with search and filters
- Edit, duplicate and delete records
- Optional reminders (browser notifications and beep while the tab is open)
- Light/dark theme
- Export to CSV and JSON backup, import from JSON, clear all data
- Data stored locally in the browser (localStorage)

## Technologies

HTML, CSS, JavaScript, localStorage. No frameworks or build step; one self-contained `index.html`.

## Responsive Design

Layout adapts with CSS media queries. Tested without horizontal scrolling at 360, 390, 768, 1024 and 1440px widths.

## UI/UX

Top navigation bar, card-based history, toast feedback and confirm dialogs for destructive actions.

## Known Limitations

Data lives only in one browser on one device; clearing browser data deletes it. Reminders only fire while the tab is open.

## Project Structure

```text
01-email-tracking-tool/
├── index.html
├── screenshots/
└── README.md
```

## Screenshots

| Desktop | Mobile |
|---|---|
| ![Desktop](screenshots/desktop-home.png) | ![Mobile](screenshots/mobile-home.png) |

![Feature](screenshots/feature.png)

## Live Demo

[Live Demo](https://d-sandeepani.github.io/frontend-web-projects/ai-assisted-web-projects/01-email-tracking-tool/)

## GitHub Repository

https://github.com/d-sandeepani/frontend-web-projects/tree/main/ai-assisted-web-projects/01-email-tracking-tool

## AI-Assisted Development

This project was developed with AI-assisted support (ideation, coding assistance, debugging and development support). I reviewed, tested and adjusted the result. It is not described as 'built entirely by AI'.

## Learning Outcomes

State management in vanilla JS, localStorage persistence, form validation, date/time calculations, file export/import.