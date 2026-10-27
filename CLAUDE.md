# Eero's Space Launch Tracker

A space launch tracker built by Eero (age 10) using Claude Code.

## What it does
Tracks upcoming rocket launches from NASA, SpaceX, and Blue Origin in real time.

## Features
- Three separate sections: NASA, SpaceX, Blue Origin
- Each launch shows: rocket name, launch site, date/time, mission description
- Live countdown timer for each upcoming launch
- Embedded live video stream when a launch is live (via YouTube)
- Space-themed design: dark background, stars, space colors

## Tech Stack
- Single file: index.html (HTML + CSS + JavaScript, no frameworks)
- Launch data: The Space Devs Launch Library 2 API (free, no key needed)
  - Endpoint: https://ll.thespacedevs.com/2.2.0/launch/upcoming/
- Live video: YouTube embed (URL pulled from API when available)

## Rules
- ALWAYS keep everything in one index.html file
- NEVER use frameworks like React or Vue
- Keep code simple and readable
- After every significant feature, commit to git with a short message
- Do NOT push to GitHub automatically — only push when asked
- Never include personal names or emails in the code or commits

## How to run
Open index.html in any browser.

## Git / Deployment
- Commit after every significant feature Eero confirms he likes
- Will be deployed via GitHub Pages so Eero can play at home
