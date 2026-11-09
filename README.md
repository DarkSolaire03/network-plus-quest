# Network+ Quest

## 🌐 Live Site: [darksolaire03.github.io/network-plus-quest](https://darksolaire03.github.io/network-plus-quest/)

> Turn studying for the CompTIA Network+ exam into an adventure — complete quests, earn XP, rise through the ranks, and face the exam as your final boss.

## About

**Network+ Quest** turns the CompTIA Network+ N10-009 exam into a study RPG. Instead of staring at a long checklist of exam objectives, you work through the five Network+ domains as game levels, checking off quests as you learn each topic.

Every completed quest earns XP, fills your progress bar, and moves you closer to exam day. It is built to make steady, daily study feel rewarding — and to show you, at a glance, exactly what you have covered and what is still ahead.

## How to Use It

1. Open the live site: **https://darksolaire03.github.io/network-plus-quest/**
2. Work through the quests level by level, starting with Domain 1.
3. Check off each quest as you study and understand that topic.
4. Watch your XP and progress bar fill up as you complete quests.
5. Your progress saves in your browser (using `localStorage`), so you can close the page and pick up where you left off on the same browser and device.
6. Keep going until you have cleared all five levels — then take on the final boss: the Network+ exam itself.

## The 5 Levels

The five levels follow the five CompTIA Network+ N10-009 domains:

| Level | Domain | What You Will Learn |
| --- | --- | --- |
| Level 1 | **Domain 1: Networking Concepts** | How networks work — models, protocols, ports, IP addressing, and core networking ideas. |
| Level 2 | **Domain 2: Network Implementation** | Putting networks together — devices, cabling, wireless, switching, routing, and network design. |
| Level 3 | **Domain 3: Network Operations** | Running networks day to day — monitoring, documentation, business continuity, and keeping things up and running. |
| Level 4 | **Domain 4: Network Security** | Protecting networks — threats and attacks, hardening, access control, and security best practices. |
| Level 5 | **Domain 5: Network Troubleshooting** | Fixing networks — a step-by-step troubleshooting methodology, common problems, and the tools to solve them. |

## Features

- **24 checkable exam-objective quests** across the five domains
- **XP and progress tracking** — a progress bar that fills as you complete quests
- **Ranks that rise** as your XP grows, so your progress feels like leveling up
- **Progress saved in your browser** with `localStorage` — no account or sign-in needed
- **Mobile-friendly** — study on your phone, tablet, or computer
- **Single-file site** — everything lives in one `index.html` file, so it loads fast and is easy to maintain
- **A clear finish line** — the exam is the final boss, after you clear every level

## How to Edit / Update It

You do not need any special tools to update this site:

1. Open `index.html` in this repository on GitHub.
2. Click the pencil (**Edit**) icon, make your changes, and commit them.
3. GitHub Pages redeploys the site automatically — your changes appear on the live site within a few minutes.

To add a quest, edit the quest list in `index.html` and commit. To change the wording, ranks, or layout, edit the same file — there is no build step to run.

## Tech Notes

- **Single `index.html`** with inline CSS and JavaScript — no build step, no framework, and no separate files to manage
- Hosted on **GitHub Pages**
- Includes a `.nojekyll` file so GitHub Pages serves the site exactly as written
- Progress is stored locally in the browser with `localStorage`; clearing browser data will reset progress

## My Other Sites

- **Emberwrath Chronicles** — https://darksolaire03.github.io/emberwrath-chronicles/
- **Get To Know Juan** — https://darksolaire03.github.io/about-juan/
