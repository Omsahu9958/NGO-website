# 🌱 HopeRoot Foundation — NGO Website

A minimal, production-grade static website built for a fictional NGO as part of **Task 3 – AI Website Generation** under the **InAmigos Foundation** internship program.

---

## 📌 Project Overview

| Detail | Info |
|---|---|
| **Type** | Static Frontend Website (Single HTML File) |
| **Domain** | NGO / Non-Profit |
| **Theme** | Minimal, Earthy, Community-focused |
| **Tool Used** | Claude AI (Anthropic) |
| **File** | `ngo-website.html` |

---

## 🗂️ Sections Covered

| # | Section | Description |
|---|---|---|
| 1 | **Navbar** | Fixed navigation with logo, links, Donate CTA, and mobile hamburger menu |
| 2 | **Hero** | Full-screen landing with tagline, description, CTAs, and live stat cards |
| 3 | **About Us** | Organisation story, 3 core values, decorative quote block |
| 4 | **Services / Programs** | 6 program cards — Education, Health, Women's Livelihoods, Shelter & WASH, Youth Leadership, Volunteer Network |
| 5 | **Impact** | Large typographic impact numbers (12,400+ beneficiaries, 38 villages, etc.) |
| 6 | **Get Involved** | 4 ways to help — Donate, Volunteer, Corporate CSR, Spread the Word |
| 7 | **Contact** | Address, phone, email + fully functional contact form with confirmation |
| 8 | **Footer** | Brand, 3 link columns, legal links (80G, 12A, FCRA), social links |

---

## 🎨 Design Decisions

- **Aesthetic:** Brutally minimal — generous whitespace, 1px borders, no box shadows
- **Typography:** `Cormorant Garamond` (editorial serif) + `DM Sans` (clean sans-serif)
- **Color Palette:**

| Name | Hex | Usage |
|---|---|---|
| Cream | `#FDFBF7` | Page background |
| Sand | `#F5F0E8` | Section backgrounds |
| Moss | `#4A6741` | Primary accent, CTAs |
| Earth | `#2C2416` | Headings, dark sections |
| Mist | `#B8C4B1` | Subtle accents, footer text |

- **Animations:** Scroll-triggered `IntersectionObserver` fade-up on every section block
- **Responsive:** Mobile-first layout with hamburger menu for screens < 780px

---

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, CSS Grid, Flexbox, `@keyframes`, `backdrop-filter`
- **Vanilla JavaScript** — scroll animations, mobile menu toggle, form handling
- **Google Fonts** — Cormorant Garamond, DM Sans
- **No frameworks, no build tools** — zero dependencies, single file

---

## 🚀 How to Run

1. Download `ngo-website.html`
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. No server, no install, no setup needed

```bash
# Or serve locally with Python
python -m http.server 8000
# Then open http://localhost:8000/ngo-website.html
```

---

## 📁 File Structure

```
Task-3-NGO-Website/
├── ngo-website.html     ← Complete website (self-contained)
├── README.md            ← This file
└── screenshots/         ← (Add your screenshots here)
    ├── hero.png
    ├── about.png
    ├── services.png
    └── contact.png
```

---

## ✅ Task Checklist

- [x] Website generated using AI tool (Claude by Anthropic)
- [x] Homepage / Hero section
- [x] About Us section
- [x] Services section
- [x] Contact Page
- [x] Additional sections (Impact, Get Involved, Footer)
- [ ] Screenshots uploaded to Drive
- [ ] Shared on LinkedIn
- [ ] Tagged InAmigos Foundation

---

## 🙏 Acknowledgements

Built as part of the **InAmigos Foundation** Virtual Internship Program.  
AI tool used: **Claude (Anthropic)** — [claude.ai](https://claude.ai)

---

*"Every root strengthens the whole tree. Every community member matters."*
