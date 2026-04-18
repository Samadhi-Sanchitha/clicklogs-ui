# clicklogs-ui
Web-based click logging system for user interface research using Firebase Firestore. Captures tap duration, interface variation, and device platform (Android/PC) for analysis.

# Click Logging System (UI Experiment)

## Overview

This project is a web-based click logging system developed for user interface (UI) research. It captures detailed timing data of user interactions across different device types and interface variations.

The system allows users to perform tapping tasks, while recording interaction metrics such as timestamps, duration, and sequence. The collected data is stored in Firebase Firestore for further analysis.

---

## Features

* Device selection (Android / PC)
* Two interface variations:

  * Feedback shown
  * No feedback
* Captures up to 50 taps per session
* Records:

  * Tap sequence number
  * Start and end timestamps
  * Tap duration
  * Interface type
  * Device platform
  * Session ID
* Stores data in Firebase Firestore (`tap_logs` and `sessions` collections)

---

## Technologies Used

* HTML, CSS, JavaScript
* Firebase Firestore (NoSQL database)
* Live Server (for local testing)
* GitHub Pages (for deployment)

---

## Deployment

The application is deployed using GitHub Pages and can be accessed via:

👉 [Paste your GitHub Pages URL here]

---

## Data Collection Process

Participants are required to:

1. Select their device type (Android or PC)
2. Tap the button repeatedly for each interface variation
3. Complete both variations for full session data

All interaction data is automatically stored in Firebase Firestore.

---

## Purpose

The system is designed to analyze:

* User interaction speed (tap duration)
* Differences between device types
* Effect of interface feedback on performance
* User completion vs drop-off behavior

---

## Author

Samadhi Sanchitha Fernando

