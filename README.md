# 🕳️ Event Horizon — The Science of Black Holes

A futuristic, immersive educational website about the science of black holes. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools. Designed to be deployed on **GitHub Pages** in minutes.

![Event Horizon Preview](assets/svg/blackhole-hero.svg)

---

## 🚀 Live Demo

> Deploy to GitHub Pages: `Settings → Pages → Source: main branch → / (root)`

---

## 📁 Project Structure

```
event-horizon/
├── index.html              # Homepage — hero, facts, timeline
├── about.html              # About the team & mission
├── contact.html            # Contact form + FAQ
├── css/
│   └── style.css           # Shared styles, variables, components
├── js/
│   └── main.js             # Starfield, animations, scroll reveal
└── assets/
    └── svg/
        ├── blackhole-hero.svg      # Animated hero black hole
        ├── anatomy-diagram.svg     # Labelled anatomy of a BH
        ├── types-comparison.svg    # Stellar / Intermediate / Supermassive
        └── nebula-bg.svg           # Background nebula texture
```

---

## ✨ Features

- **Animated Black Hole** — SVG hero with spinning accretion disk and pulsing event horizon
- **Twinkling Starfield** — Canvas-rendered, includes occasional shooting stars
- **Mouse Parallax** — Hero black hole responds to cursor movement
- **Scroll Reveal** — Staggered fade-in animations on content sections
- **SVG Diagrams** — Anatomy diagram, types comparison, nebula backgrounds
- **Responsive** — Mobile-friendly hamburger navigation
- **FAQ Accordion** — Smooth expand/collapse
- **Contact Form** — Client-side with success state
- **Zero Dependencies** — No npm, no build step, no frameworks

---

## 🛠️ Getting Started

### Option 1: GitHub Pages (Recommended)

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set Source to `main` branch, root `/`
4. Your site is live at `https://yourusername.github.io/event-horizon/`

### Option 2: Local Development

```bash
# Clone the repo
git clone https://github.com/yourusername/event-horizon.git
cd event-horizon

# Open directly in browser
open index.html

# OR use a local server (recommended for SVG assets)
npx serve .
# or
python3 -m http.server 8080
```

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--void` | `#000005` | Page background |
| `--accent` | `#ff6b00` | Primary orange — CTAs, highlights |
| `--cyan` | `#00e5ff` | Secondary accent — links, form focus |
| `--gold` | `#ffd166` | Tertiary — accretion disk, stat numbers |
| `--muted` | `#6b5f8a` | Body text, descriptions |
| `--text` | `#e8deff` | Primary text |

**Fonts:** Orbitron (headings) · Share Tech Mono (labels) · Rajdhani (body)

---

## 📄 Pages

| Page | Description |
|------|-------------|
| `index.html` | Hero, What is a Black Hole, Types, Facts, Timeline |
| `about.html` | Mission, Team, Stats, Values |
| `contact.html` | Contact form, Info, FAQ accordion |

---

## 🔧 Customization

**Change accent color:** Update `--accent` in `css/style.css`

**Add a new page:** Copy the `page-header` block from `about.html` and link it in `nav` and `footer`

**Update team members:** Edit the `.team-card` sections in `about.html`

**Modify facts:** Find the `.fact-item` blocks in `index.html`

---

## 📜 License

Content: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free for educational use with attribution  
Code: [MIT License](LICENSE)

---

## 🙏 Credits

Scientific content informed by:
- NASA/ESA public education materials
- Event Horizon Telescope Collaboration (2019, 2022)
- Hawking, S. (1974). *Black hole explosions?* Nature
- Wheeler, J.A. (1968). Our Universe: the Known and the Unknown

---

*"Black holes are where God divided by zero." — Steven Wright*
