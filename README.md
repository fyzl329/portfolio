# fyz@portfolio:~$

An interactive **terminal-style portfolio** built with HTML, CSS, and vanilla JavaScript — simulating a retro command-line interface that responds to user commands like `about`, `skills`, `projects`, and `contact`.

---

## Overview

This project transforms a developer portfolio into a **live terminal experience**. It’s inspired by the aesthetics of classic CRT monitors — flickering neon-green text, a dark background, and blinking cursors — while remaining fully responsive and interactive.

The interface is minimal, smooth, and surprisingly human.

**Commands include:**

| Command     | Description |
|--------------|-------------|
| `help`       | Shows all available commands |
| `about`      | Displays personal and mission details |
| `skills`     | Lists technical competencies with progress bars |
| `projects`   | Displays major projects and their statuses |
| `status`     | Shows system/engine status and deployment info |
| `contact`    | Lists ways to connect (GitHub, Email, Website) |
| `clear`      | Resets the terminal screen |

---

## Features

- **Fully interactive command-line UI**
- **Retro terminal glow and flicker effect**
- **Auto-scroll output window**
- **Custom progress bars**
- **Responsive layout (mobile-friendly)**
- **Keyboard-based navigation (Enter to execute)**

---

## Tech Stack

- **HTML5** – Structure and content  
- **CSS3** – Styling, animations, flicker and glow effects  
- **JavaScript (Vanilla)** – Command logic, dynamic rendering  

No frameworks, no dependencies, no bloat.

---

## Commands & Architecture

Each command is handled by a clean function:

- `showHelp()` → Prints available commands  
- `showAbout()` → Displays developer information  
- `showSkills()` → Renders skill bars dynamically  
- `showProjects()` → Builds an interactive project table  
- `showStatus()` → Shows simulated system stats  
- `showContact()` → Lists contact methods  

Input is captured via an event listener on the text field, and output lines are appended dynamically using DOM operations.

---

## Developer Info

**Name:** Fayazul (FYZ)  
**Role:** Student | Developer | Designer | Educator  
**Mission:** Building interactive ecosystems for STEM learning.  
**Focus:** Physics simulations, structured quiz engines, intuitive UIs.

---

## Contact

- **GitHub:** [fyzl329](https://github.com/fyzl329)  
- **Email:** [fayazulh329@gmail.com](mailto:fayazulh329@gmail.com)  

---
