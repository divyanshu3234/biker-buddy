# Biker’s Buddy

A minimal Android HUD for motorcyclists using old or secondary Android phones.

Biker’s Buddy turns a spare Android phone into a **glanceable riding HUD**, so your primary phone stays safe in your pocket and your eyes stay on the road.

---

## Why this exists

- Phone-mounted navigation damages modern phone cameras (OIS failure from vibration)
- Dedicated motorcycle HUDs and CarPlay screens are expensive
- Existing apps are car-focused and visually cluttered
- Riders need **simple, glanceable information**, not full phone UIs

This project is built for **budget-conscious riders** and the biker community.

---

## What Edition 1 DOES (current)

- GPS-based speed display
- Incoming call alerts
- On-call status indicator
- Music playback controls (Play / Pause / Next / Previous)
- Designed for helmet intercom use
- Always-on, distraction-minimal HUD UI

Edition 1 focuses on **core riding signals**, not navigation complexity.

---

## What Edition 1 does NOT do

- No CarPlay or Android Auto
- No screen mirroring
- No messaging or notifications
- No cloud accounts or login
- No touch-heavy interaction while riding

This is a **secondary riding display**, not a phone replacement.

---

## Planned features (next editions)

- Turn-by-turn navigation arrows (map-free, biker-first)
- Speed-based touch lock for safety
- Arrow-only navigation mode
- Brightness and power optimization
- Primary phone → HUD event syncing (Android / iOS)

---

## How it’s meant to be used

- Primary phone (Android or iOS):
  - Stays in pocket or bag
  - Handles navigation, calls, music
- Old Android phone:
  - Mounted on handlebar
  - Runs Biker’s Buddy as HUD
- Helmet intercom:
  - Handles audio, calls, voice commands

This setup avoids camera damage and reduces distraction.

---

## Tech stack

- Android
- Kotlin
- Jetpack Compose
- Google Location Services (GPS speed)
- Bluetooth (HFP + AVRCP for calls and media)

---

## Safety note

Do not interact with the screen while riding.
Use helmet or intercom controls for calls and music.

This project prioritizes **glanceability and rider safety** over features.

---

## Status

🚧 Early prototype (Edition 1 MVP)  
Built as a fast, community-first experiment.

---

## License

MIT
