# Vishal — Portfolio Website

A modern, responsive 3-page personal portfolio website built with vanilla HTML, CSS, and JavaScript.
Developed as part of the **Soft Nexis Task 1** assignment.

> 👤 **Student:** Vishal
> 🎓 **University:** Savitribai Phule Pune University (SPPU), Pune
> 📅 **Year:** 2026

---

## 📄 Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero section, projects grid, skills chips |
| About | `about.html` | Bio, education & experience timeline, values |
| Contact | `contact.html` | Social channels, contact form with validation |

---

## ✅ Features

- Consistent navigation bar across all 3 pages with active link highlighting
- Hamburger menu for mobile (≤768px) with fullscreen overlay
- Responsive layout using CSS Grid (`auto-fit` / `minmax`) and Flexbox
- Media queries at `768px` and `480px` breakpoints
- Hover effects on buttons (lift + glow), cards (border highlight), and nav links
- CSS animations with staggered entrance on page load
- Contact form with validation and success state
- Fixed sticky navbar with glassmorphism blur effect

---

## 📁 File Structure

```
portfolio-site/
├── index.html        # Home page
├── about.html        # About page
├── contact.html      # Contact page
├── styles/
│   └── main.css      # Global styles (all pages)
├── images/           # Store your images here
└── README.md         # Project documentation
```

---

## 🎨 Design System

| CSS Variable | Value | Usage |
|---|---|---|
| `--bg` | `#0a0a0f` | Page background |
| `--surface` | `#111118` | Card / section background |
| `--accent` | `#c8ff00` | Highlights, buttons, links |
| `--text` | `#f0f0f0` | Primary text |
| `--text-muted` | `#888` | Secondary text |
| `--radius` | `12px` | Border radius |

### Fonts (Google Fonts)
- **Syne** — Headings and display text
- **DM Sans** — Body and UI text

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 768px` | Multi-column grid, horizontal nav |
| `≤ 768px` | Stacked single column, hamburger menu |
| `≤ 480px` | 2-column skills grid, stacked buttons |

---

## 🛠️ How to Run

No build tools or dependencies required. Just open in a browser:

```bash
# Option 1 — Open directly
open index.html

# Option 2 — Use VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Option 3 — Python local server
python3 -m http.server 3000
# Then visit: http://localhost:3000
```

---

## ✏️ Customization Guide

1. **Profile info** — Update name, title, and bio in all `.html` files
2. **Projects** — Edit the project cards in `index.html` with your real work
3. **Timeline** — Update education and experience in `about.html`
4. **Contact details** — Replace email and social links in `contact.html`
5. **Photo** — Add your image to `/images/` and replace the emoji in `about-photo` div
6. **Colors** — Edit CSS variables in `styles/main.css` under `:root`

---

## 🏫 About This Project

This portfolio was built as **Task 1** for the **Soft Nexis** internship/assignment program.

**Requirements fulfilled:**
- ✅ 3 Pages (Home, About, Contact)
- ✅ Consistent navigation bar
- ✅ Mobile responsive with hamburger menu
- ✅ CSS Flexbox & Grid layouts
- ✅ Media queries for responsiveness
- ✅ Hover effects on buttons and links

---

*Built with ❤️ by Vishal | Savitribai Phule Pune University | 2026*
