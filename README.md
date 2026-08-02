# Apnea Breath-Hold Trainer v2026 - web app 2026

> A quiet, browser-based single-file trainer for apnea preparation and breath-hold practice. Version 2026 is tailored to dry static apnea, combining paced breathing, timed holds, and local progress records.

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathanvsjmiller531/apnea-breath-hold-trainer?style=flat-square)](https://github.com/nathanvsjmiller531/apnea-breath-hold-trainer)

---

<p align="center">
  <a href="https://nathanvsjmiller531.github.io/apnea-breath-hold-trainer/">
    <img src="https://img.shields.io/badge/Download-Apnea%20Breath--Hold%20Trainer%20Latest-brightgreen?style=for-the-badge" alt="Download Apnea Breath-Hold Trainer">
  </a>
</p>

> **[Download Apnea Breath-Hold Trainer v2026](https://nathanvsjmiller531.github.io/apnea-breath-hold-trainer/)**

---

[Download Latest Build](https://nathanvsjmiller531.github.io/apnea-breath-hold-trainer/)

---

## What the App Does

Apnea Breath-Hold Trainer provides a focused web interface for breath-hold sessions, especially dry static apnea practice. It offers a simple way to prepare with guided breathing, run timed holds, and record results without installing a larger application.

Session information, including personal-best results, is kept in the browser's local storage. Since the project is distributed as a compact HTML file, it can be opened directly, saved for offline use, and reused across training sessions when internet access is limited.

---

## Included Training Tools

- Step-by-step breathe-up guidance for session preparation
- A max-hold clock for timing breath-hold attempts
- CO2 and O2 table routines with interval timing
- Box breathing for controlled, paced breathing exercises
- An orb-style breathing display that shows session progress
- Personal-best records for following hold-time progress
- Light and dark display modes
- A standalone HTML format that supports offline use

---

## Getting Started

The application requires only its HTML file.

1. Clone or download the repository:
   - `git clone https://github.com/nathanvsjmiller531/apnea-breath-hold-trainer.git
2. Open the HTML file with a modern web browser.
3. Alternatively, serve the file through a local static server or another static web host.

For ordinary use, there is no build process: open the file and begin.

---

## Using the Trainer

Open the app, then select the format that matches your planned session. You can prepare with a guided breathe-up, run a maximum-hold timer, or follow an interval table. The layout is intended for a steady and repeatable training routine.

A typical session might include:

- Practicing box breathing or the guided breathe-up first
- Starting the max-hold timer before beginning the hold
- Following a CO2 or O2 table for interval work
- Checking the personal-best record after training
- Choosing light or dark mode for the current environment

The single-file design also makes it possible to keep using the same local copy from session to session.

---

## Browser Storage and Settings

The trainer uses browser `localStorage` for its local data.

Values may include:

- personal-best results
- the selected theme
- the current training progress state

A representative state object looks like this:

```json
{
  "theme": "dark",
  "personalBest": 120,
  "lastMode": "co2-table"
}
```

To remove saved data, clear the site data associated with the browser origin from which the app is being opened.

---

## Requirements

- A modern browser capable of displaying HTML
- Sufficient browser storage for preferences and progress data
- Internet access only when retrieving the app from a hosted page
- No runtime installation, since the application runs from a single HTML file

---

## Frequently Asked Questions

**Where should I ask for help?**  
Check the repository issue tracker or the project discussion area when either is available in your fork or hosting setup.

**Does the trainer work without an internet connection?**  
Yes. After the HTML file is available locally, it is intended to run offline as a standalone file.

**Where does the app keep my settings?**  
Settings are stored in the browser's `localStorage` for the file or site origin being used.

**What could cause my records to disappear?**  
Clearing browser storage, changing browsers, or opening the app from another origin can make previously saved data unavailable.

**How can I install an update?**  
Get the latest build from the project page and replace your existing local HTML file with the newer version.

---

## License

This project is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
