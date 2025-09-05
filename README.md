
# ProDev Mobile Setup — React Native (Expo + TypeScript)

![expo](https://img.shields.io/badge/Expo-%2350B0FF.svg?logo=expo&logoColor=white)
![license](https://img.shields.io/badge/license-Educational-lightgrey)

**A collection of compact, focused React Native learning projects** built with **Expo** and **TypeScript**. Each task lives in its own folder and can be run independently on a physical device using **Expo Go**.

This repository is part of the **ALX Continuing Frontend/Backend engineering program**. Primary goals: **hands-on learning**, **clean code**, and **repeatable setups**.

## Table of contents

- [Overview](#overview)
- [Quick links](#quick-links)
- [Tech stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Quick start (run a task)](#quick-start-run-a-task)
- [Tasks — what you will find](#tasks-what-you-will-find)
- [Troubleshooting & FAQ](#troubleshooting--faq)
- [Conventions & commits](#conventions--commits)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

- **Purpose:** Learn core mobile concepts progressively with small, reviewable examples.
- **Audience:** Students, reviewers, and engineers learning Expo + TypeScript.
- **Structure:** Each task is isolated so you can run only what you need.

## Quick links

- Mobile setup notes: [`mobile-development-setup/README.md`](./mobile-development-setup/README.md)
- Task 0 — Mobile environment notes: [`mobile-development-setup/`](./mobile-development-setup/)
- Task 1 — First Expo Router app: [`prodev-mobile-app-0x00/README.md`](./prodev-mobile-app-0x00/README.md)
- Task 2 — Components & styling: [`prodev-mobile-app-0x01/README.md`](./prodev-mobile-app-0x01/README.md)
- Task 3 — Safe areas & images: [`prodev-mobile-app-0x02/README.md`](./prodev-mobile-app-0x02/README.md)
- Task 4 — Login screen & shared styles: [`prodev-mobile-app-0x03/README.md`](./prodev-mobile-app-0x03/README.md)

## Tech stack

- **React Native** (via Expo)
- **TypeScript**
- **Expo Router** (file-based routing)
- **Expo Go** for device testing
- (Planned) **NativeWind** for Tailwind-like utilities

## Prerequisites

Make sure you have the following installed:

- Node.js (LTS) — check with `node --version`
- npm (or pnpm)
- Visual Studio Code (recommended)
- Expo Go on your mobile device
- An (optional) Expo account for publishing or build tasks

## Quick start — run a task

From the repository root pick a task folder (example uses Task 2):

```powershell
cd 'prodev-mobile-app-0x02'
npm install    # first run only
npx expo start  # starts Metro & DevTools
```

Tip: Scan the QR code in Expo DevTools using Expo Go. If LAN doesn't work, switch to Tunnel mode.

## Tasks — what you will find

Each `prodev-mobile-app-0xNN` folder focuses on one learning objective. Highlights below include the main files and implemented features.

- **Task 0 — Mobile development setup** (`mobile-development-setup/`)
  - Notes and verification steps for Windows/macOS/Linux device setup.

- **Task 1 — First mobile app (Expo Router)** (`prodev-mobile-app-0x00/`)
  - Minimal Expo Router scaffold with `app/_layout.tsx` and `app/index.tsx`.

- **Task 2 — Components & styling** (`prodev-mobile-app-0x01/`)
  - Exercises with `StyleSheet`, text variants, and layout patterns.

- **Task 3 — Safe areas, images & touchables** (`prodev-mobile-app-0x02/`)
  - Uses `SafeAreaView`, `ImageBackground`, and responsive layouts with `Dimensions`.
  - Includes sample assets in `assets/images/`.

- **Task 4 — Login screen & shared styles** (`prodev-mobile-app-0x03/`)
  - Login UI, inputs with `secureTextEntry`, social sign-in buttons, and a centralized `styles/` module.

## Troubleshooting & FAQ

- **QR code not connecting:** switch Expo DevTools from **LAN** to **Tunnel**, disable VPN/firewall temporarily, or try a mobile hotspot.
- **Images not loading:** verify the relative `require(...)` path and case-sensitive file names.
- **Blank/red screen after changes:** check Metro/terminal output; reload (press `r` in Metro) and clear cache if needed.

## Conventions & commits

- **Commit messages**: `type(scope): short description` (imperative). Example: `feat(app-0x02): add ImageBackground landing screen`
- **Branch names**: `task/0x03-login-screen`, `task/0x02-landing`
- **Code style**: Follow React Native community conventions and keep changes small per commit.

## Contributing

If you'd like to contribute or suggest improvements:

1. Fork the repo
2. Create a branch for the task or fix
3. Open a pull request with a concise description and testing notes

## License

This repository is for **educational purposes** under the ALX ProDev Frontend program. If you plan to reuse this outside coursework, consider adding an explicit license such as **MIT**.

## Author
Gabriel Ifeanyi, Pro Frontend Developer