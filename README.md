# MTEC3200_Project2_GAA
# HereToHelp

A volunteering app that connects people who need a hand with everyday things to neighbors nearby who are willing to help.

**Live link:** [TBD — Expo link + screen recording once the prototype is built]

## Team

- Gabriel A. Aguilar (solo)

## Problem

_Draft — to be revised after interviews (see `docs/synthesis.md`)._

People in a neighborhood sometimes need help with small, everyday tasks they can't easily do alone, while others nearby would be willing to help but never find out who needs it or when. Asking can feel awkward or like a burden, and offers of help often go unnoticed, so needs go unmet even when help is close by.

## Platform

Native app built with [Expo](https://expo.dev) (React Native) and Expo Router. Screens live in `src/app/`; each file there is a screen.

## How to run

1. Install the **Expo Go** app on your phone (App Store or Google Play).
2. Install dependencies (first time only):

   ```bash
   npm install
   ```

3. Start the app:

   ```bash
   npx expo start
   ```

   On campus wifi, or if your phone can't connect, use the tunnel instead:

   ```bash
   npx expo start --tunnel
   ```

4. Scan the QR code in the terminal with the Camera app (iPhone) or Expo Go (Android).
5. Edit a file in `src/app/` and save. The app on your phone updates automatically.

Useful commands: `npx expo lint` (lint), `npx expo install <package>` (add a package with compatible versions), `npx expo-doctor` (diagnose setup problems).

## Docs

**Research**
- Stakeholder map: `docs/stakeholder_map.png`
- Interview script: `docs/interview_script.md`
- Recruiting message + consent statement: `docs/recruiting_script.md`
- Interview notes template: `docs/interview_template.md`
- Interviews (solo goal: 5, including people outside my circle): `docs/P1_YYYY-MM-DD.md` …

**Design and testing**
- MVP: `docs/mvp.md`
- Wireframes: `docs/wireframes.md`, `docs/wireframes/`, `docs/wireframe-slides.html`
- Prototype test: `docs/prototype-test.md`

## Privacy

Participants are referred to by code only (P1, P2, P3 …). No last names, phone numbers, emails, addresses, or face photos. The key linking codes to names is stored outside GitHub.
