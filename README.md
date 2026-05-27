# CAIF 2026 — Canada-Africa Innovation Festival Poster

**Official event poster and mobile-first microsite for the Canada–Africa Innovation Festival, Toronto — May 29–30, 2026.**

Produced by **UKALD** in partnership with **NBTI, Abuja** on behalf of the **Federal Government of Nigeria**.

---

## What This Is

A single self-contained HTML file that serves as both a shareable digital poster and a lightweight mobile event page. Designed for staff distribution, social sharing, and GitHub Pages / Vercel deployment with zero setup.

---

## Features

- **Mobile-first responsive layout** — optimised for phones, works on all screen sizes
- **NBTI logo** embedded in the navbar — no external image requests
- **Live QR code** embedded as base64 — scans directly to the registration page
- **Native share button** — uses the Web Share API (iOS/Android share sheet); falls back to clipboard copy on desktop
- **Parallax hero** with smooth scroll animation
- **Partner logos** — UKALD, NBTI, Nigeria Coat of Arms
- **Bottom navigation bar** on mobile
- **Fully self-contained** — all assets baked in, works offline, no CDN failures except Tailwind + Google Fonts

---

## File Structure

```
/
├── caif-2026-poster.html    ← The poster (deploy this)
└── README.md
```

---

## Deployment

### Vercel (recommended)
1. Import this repo at [vercel.com](https://vercel.com)
2. Framework Preset → **Other**
3. Build Command → leave blank
4. Output Directory → leave blank
5. Deploy

Live URL: `yourproject.vercel.app`

### GitHub Pages
1. Go to repo **Settings → Pages**
2. Source → **Deploy from a branch**
3. Branch → `main` / `root`
4. Save

Rename `caif-2026-poster.html` to `index.html` for the root URL to load it automatically.

### Local
Open `caif-2026-poster.html` directly in any browser. No server needed.

---

## Share Button Behaviour

| Device / Browser | Behaviour |
|---|---|
| iOS Safari, Android Chrome | Opens native share sheet (WhatsApp, Messages, email, etc.) |
| Desktop Chrome / Edge | Copies URL to clipboard; icon briefly shows ✓ |
| Other desktop browsers | Opens a prompt with the URL to copy manually |

---

## Event Details

| | |
|---|---|
| **Event** | Canada-Africa Innovation Festival 2026 |
| **Date** | May 29 – 30, 2026 |
| **Venue** | 89 Chestnut St, Toronto, ON |
| **Convening body** | NBTI — National Board for Technology Incubation, Abuja |
| **Initiative of** | Federal Government of Nigeria |
| **Strategic partner** | UKALD |

---

## Partners

| Organisation | Role |
|---|---|
| **NBTI — National Board for Technology Incubation** | Convening body · Federal Republic of Nigeria |
| **UKALD** | Strategic production partner |
| **CAIF** | Host festival · Toronto, Ontario |

---

*© 2026 Canada-Africa Innovation Festival. Supported by UKALD & NBTI. Bridging innovation across continents.*
