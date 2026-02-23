# CR Earnings – Crypto Airdrop Alerts 🇱🇰

> Sri Lanka's #1 Crypto Airdrop Tracking Website

A lightweight, no-backend website built with HTML, CSS (Tailwind), and vanilla JavaScript. Curates and publishes the latest crypto airdrop opportunities for the Sri Lankan crypto community.

🔗 **Live Site:** [Sample Site](https://theshanbmr.github.io/cr-earnings)
▶️ **YouTube:** [@CR-Earnings](https://youtube.com/@CR-Earnings)

---

## Features

- 🪂 **Airdrop article cards** with image, title, popup detail view
- 🎬 **YouTube video embeds** inside article popups
- 📢 **Left & right sidebar ads** that rotate every 10 seconds
- 📌 **Fixed bottom ad bar** that stays on screen while scrolling
- 🌙 **Dark / Light / System theme** toggle
- 📱 **Fully responsive** – works on mobile, tablet, and desktop
- 🔢 **Pagination** – previous/next buttons appear after 10 articles
- 🔐 **Hidden admin panel** – not linked anywhere on the public site
- 💾 **No server needed** – all data stored in browser localStorage

---

## Project Structure

```
/
├── index.html       # Main public website
├── admin.html       # Hidden admin panel (not linked publicly)
└── README.md        # This file
```

---

## Admin Panel

Access the admin panel by navigating directly to `/admin.html`.

**Default credentials:**
| Field | Value |
|-------|-------|
| Email | `admin@crearnings.lk` |
| Password | `CRAdmin2024!` |

> ⚠️ **Change the default credentials immediately after first login** via the Settings tab.

### What you can manage:
- ➕ Add, edit, delete airdrop articles
- 📝 Save articles as Draft or Published
- 🖼️ Add images and YouTube video embeds to articles
- 📢 Manage left sidebar, right sidebar, and bottom bar ads

---

## Security

Since this is a public GitHub repository (required for free GitHub Pages hosting), credentials are protected using:

- A **custom double-layered hash** (non-reversible)
- A **runtime-only obfuscated pepper** — not stored as plain text
- **SessionStorage** for login sessions (auto-clears when browser closes)
- The admin panel URL (`/admin.html`) is **not linked** anywhere on the public site

> The code is made public solely for GitHub Pages hosting. See LICENSE for terms.

---

## Deployment (GitHub Pages)

1. Create a new GitHub repository
2. Upload `index.html`, `admin.html`, and `README.md`
3. Go to **Settings → Pages**
4. Set source to **Deploy from branch → main → / (root)**
5. Your site will be live at `https://yourusername.github.io/reponame/`

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure |
| Tailwind CSS (CDN) | Styling |
| Vanilla JavaScript | Logic & interactivity |
| Google Fonts (Orbitron, Exo 2) | Typography |
| localStorage / sessionStorage | Data & session management |

---

## License

Copyright © 2026 CR Earnings. All Rights Reserved.

This code is made public solely for hosting purposes via GitHub Pages.
Copying, modification, or redistribution is not permitted without written
permission from the owner.

---

*Built for the Sri Lankan Crypto Community 🇱🇰*
