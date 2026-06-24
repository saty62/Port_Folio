# Priyadarshan Satyam Bharti — Personal Portfolio

A clean, dark-themed personal portfolio website built with pure HTML and CSS. No frameworks, no build tools — just one file, ready to deploy anywhere.

🔗 **Live Links**
- LinkedIn: [priyadarshan-satyam-bharti](https://www.linkedin.com/in/priyadarshan-satyam-bharti-2904a228b/)
- GitHub: [saty62](https://github.com/saty62)
- Email: satyampriyadarshan62@gmail.com

---

## 📁 Project Structure

```
portfolio/
└── portfolio.html   # Single-file portfolio (HTML + CSS)
└── README.md        # You're here
```

---

## ✨ Features

- **Single-file** — everything lives in one `portfolio.html`, no dependencies to install
- **Responsive** — works on mobile, tablet, and desktop
- **Dark theme** — deep navy background with purple/teal accents
- **Smooth scroll** — fixed navigation with anchor-linked sections
- **No JavaScript** — pure HTML + CSS, fast and lightweight

---

## 🗂️ Sections

| Section | Content |
|---|---|
| Hero | Name, tagline, skill chips, CTA buttons |
| About | Bio + key stats (CGPA, DSA problems, CodeChef rating, NGO impact) |
| Skills | 6 categorised skill cards |
| Projects | DecodeX Hackathon, Mitron Bank Credit Card Analytics |
| Achievements | Hackathon finalist, CodeChef 2-star, DSA milestones, ServiceNow certs |
| Experience | Unnati Welfare Society (Team Lead), IIIT Athletics Club (Secretary) |
| Education | IIIT Bhagalpur — B.Tech ECE (2023–2027) |
| Contact | Email, LinkedIn, GitHub, phone |

---

## 🚀 Deployment

### Option 1 — GitHub Pages (recommended)

1. Create a new repository on GitHub (e.g. `portfolio`)
2. Add `portfolio.html` and rename it to `index.html`
3. Go to **Settings → Pages → Source** and select the `main` branch
4. Your site will be live at `https://<your-username>.github.io/portfolio`

### Option 2 — Netlify Drop

1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `portfolio.html` (renamed to `index.html`)
3. Netlify gives you a live URL instantly — no account required

### Option 3 — Vercel

```bash
npm i -g vercel
vercel deploy portfolio.html
```

### Option 4 — Any static host

Upload `portfolio.html` (as `index.html`) to any static hosting service:
- Cloudflare Pages
- Render
- Firebase Hosting
- Surge.sh

---

## 🎨 Design

| Token | Value |
|---|---|
| Background | `#0a0a0f` |
| Card surface | `#16161f` |
| Primary accent | `#7c6af7` (purple) |
| Secondary accent | `#3ecfb0` (teal) |
| Muted text | `#7a7a9a` |
| Display font | Space Grotesk |
| Mono font | Space Mono |
| Body font | Inter |

Fonts are loaded from Google Fonts — requires an internet connection to render correctly.

---

## ✏️ Customisation

All content is in plain HTML — no config files or templating. To update:

- **Links** — search for `href=` to find LinkedIn, GitHub, email, and phone
- **Stats** — find `.stat-num` elements in the About section
- **Projects** — duplicate a `.project-card` div and edit the text
- **Colors** — change CSS variables in `:root` at the top of the `<style>` block

---

## 📄 License

This project is open source. Feel free to fork and adapt it for your own portfolio.

---

*Built by Priyadarshan Satyam Bharti — Munger, Bihar*
