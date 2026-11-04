# AskBridge

**From confusion to clarity.**

AskBridge is a front-end Design Thinking prototype for improving communication between students and faculty when students have unanswered academic doubts.

## Project structure

```text
AskBridge/
├── index.html
├── README.md
├── .gitignore
└── assets/
    └── (reserved for future images, icons, and other static assets)
```

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder (make sure `index.html` is in the repository root).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The public URL will appear in the Pages settings.

## Prototype features

- Public landing page
- Student and faculty dashboard views
- Student doubt submission
- Faculty response, request-for-detail, and discussion-suggestion flows
- Doubt status tracking
- Sample faculty profiles and consultation availability
- Browser local storage for demo data

## Important limitations

This is a front-end demonstration only. It does not include a backend, real authentication, server-side database, email/SMS notifications, or integration with university systems. The faculty profiles, consultation slots, and sample questions are illustrative.

Newly submitted questions and prototype actions are stored in the current browser using `localStorage`. They are not shared between different users or devices.

## Suggested next steps

- Add real authentication and role-based access.
- Add a backend API and database.
- Connect real faculty profiles and availability.
- Add secure notifications and consultation booking.
- Add privacy, consent, and data-retention controls before any real student data is collected.
