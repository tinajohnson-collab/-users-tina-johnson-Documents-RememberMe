# RememberMe App

A low-cognitive-load reminder system designed for therapists and patients.

## Features
- **One-Screen Interface**: Minimalist design to reduce cognitive fatigue.
- **Voice Input**: "Speak" button to add reminders naturally.
- **Cognitive Load Shield**: Background logic that filters noise and only alerts the therapist when intervention is significantly required (3-Strike Rule).
- **Mocked AI & Calendar**: Simulates intelligent scheduling and Google Calendar syncing.
- **Real Backend Integration**: Uses `ntfy.sh` for sending REAL push notifications to the therapist's phone during critical alerts.

## Setup
1. Open `standalone_preview.html` in your browser to see the app immediately.
2. (Optional) Run `npm install` and `npm run dev` if you have Node.js installed.

## Real API Testing
- Go to [ntfy.sh/rememberme_therapist_shield](https://ntfy.sh/rememberme_therapist_shield) to see the live notifications triggered by the app.
