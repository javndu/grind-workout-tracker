# GRIND — Personal Workout Tracker and Gym Log

GRIND is a browser-based workout tracker for logging gym exercises, sets, reps, and weights. Follow a weekly training routine, review previous sessions, and track strength progress from one lightweight HTML app.

The app uses HTML, CSS, and JavaScript with browser local storage. It runs without a backend server or an account.

## Features

- Log exercise sets, repetitions, and lifted weight.
- Follow a weekly gym routine with push, pull, legs, upper-body, lower-body, and rest days.
- Review workout history and exercise progress.
- Track training streaks and completed exercises.
- Choose kilograms or pounds and record bodyweight.
- Adjust routines and workout reminder settings.
- Export and import JSON backups of your training data.
- Mobile-friendly interface with a dark theme.

## Run the workout tracker

1. Select **Code → Download ZIP** and extract the files.
2. Open `grind.html` in Chrome, Edge, Safari, or another modern browser.
3. Use **Today** to view your routine and log exercises.
4. Open **History**, **Progress**, **Routine**, or **Settings** to manage your training.

For more predictable browser storage and notification behavior, serve the folder locally rather than opening it as a file. For example, if Python is installed:

```sh
python -m http.server 8000
```

Then open `http://localhost:8000/grind.html`.

## Frequently asked questions

### Can I use GRIND as a gym workout log?

Yes. Record sets, reps, and weights for individual exercises, then review your previous workouts and exercise progress.

### Does it support a push pull legs workout routine?

The default training schedule includes push, pull, legs, upper-body, lower-body, and rest days. You can adjust the routine to suit your training.

### Where is my workout history saved?

Logs, routines, and settings are saved in your browser's local storage. Data is tied to the browser, profile, and site address you use. Export a backup from Settings before clearing browser data or moving devices, then import it into the new browser.

### Is there a login or cloud sync?

No account is required. This version stores training data locally and does not provide cloud synchronization.

### Can I use it on my phone?

The interface is designed for a narrow mobile screen. If you host the HTML file on a website, you can open that site from a phone browser. Browser features such as reminders may vary by platform.

## Project structure

- `grind.html` — the workout app, including its interface, styling, and JavaScript.

## Privacy and limitations

Workout logs stay in browser local storage. The app loads fonts from Google Fonts; font requests are external network requests. Browser storage is not a substitute for a durable backup.

This repository contains the app source. It is not a live hosted service. Reminder behavior depends on browser permissions and whether the page is running.
