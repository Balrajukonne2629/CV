# 🌐 Balraju Konne — Personal Portfolio

> A modern, glassmorphism-styled developer portfolio built with pure HTML & CSS — no frameworks, no dependencies.

**Live Site →** [balrajukonne2629.github.io](https://balrajukonne2629.github.io)

---

## ✨ Features

- **Glassmorphism UI** — frosted glass cards with shimmer effects and glowing borders on hover
- **Aurora Background** — 3 animated color blobs that slowly drift behind the entire page
- **Custom Cursor** — a dot + lagging ring that reacts to interactive elements
- **Scroll Progress Bar** — thin glowing line at the top of the screen tracks reading progress
- **Scroll Reveal Animations** — every section fades and slides up as you scroll into it
- **Staggered Card Entrances** — cards in grids enter one by one with a delay
- **Floating Pill Navbar** — glass-blurred nav fixed at the top center
- **Dot Grid Hero** — radial dot pattern behind the name
- **Fully Responsive** — works on mobile, tablet, and desktop
- **Zero Dependencies** — no JavaScript frameworks, no CSS libraries, no build tools

---

## 🗂️ Project Structure

```
portfolio/
├── index.html      ← All content lives here (sections clearly labeled)
├── style.css       ← All styling lives here (numbered table of contents)
└── README.md       ← You're reading this
```

Both files must stay in the **same folder** — `index.html` links to `style.css` directly.

---

## 🚀 Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen intro with name, role, bio, CTA buttons, and floating stat badges |
| **About** | Bio text + 4 stat cards (CGPA, LeetCode, Projects, Certs) |
| **Skills** | 4 grouped rows — Languages, MERN Stack, CS Concepts, Tools |
| **Projects** | 3 project cards with bullet points, tech tags, and GitHub links |
| **Achievements** | 4 highlight cards — LeetCode badge, Hackathon, Coordinator, Oracle cert |
| **Education** | Animated vertical timeline — B.Tech → Intermediate → School |
| **Certifications** | Grid of 4 certification cards |
| **Contact** | Centered card with Email, LinkedIn, GitHub, LeetCode, and Phone rows |

---

## ✏️ How to Update Content

The HTML file has clear section labels and inline comments on every editable value.
Use **Ctrl + F** (Find) in any text editor to jump straight to what you need.

### Common updates:

| What to change | Search for in `index.html` |
|---|---|
| CGPA | `UPDATE CGPA HERE` — appears in 4 places |
| LeetCode count | `Update LeetCode count` |
| Add a new project | Copy a `PROJECT CARD` block (marked with `─── START ───` / `─── END ───`) |
| Add a skill | Find the right `SKILLS ROW` and add `<span class="pill">SkillName</span>` |
| Add a certification | Copy any `.citem` block inside the `CERTIFICATIONS` section |
| Add an achievement | Copy any `.acard` block inside the `ACHIEVEMENTS` section |
| Update email | Search `balrajukonne@gmail.com` — update both the `href` and visible text |
| Update phone | Search `6300361060` — update both `href="tel:..."` and visible text |

### To highlight a skill pill (makes it glow cyan):

```html
<!-- Normal pill -->
<span class="pill">SkillName</span>

<!-- Highlighted / featured pill -->
<span class="pill f">SkillName</span>
```

---

## 🎨 Customising the Design

All design tokens live in `style.css` under **Section 1 — CSS Variables**.
Change one value and it updates everywhere on the site:

```css
:root {
  --cyan:   #4fd1c7;   /* primary accent color  */
  --violet: #9f7aea;   /* secondary accent       */
  --amber:  #f6ad55;   /* label / tag color      */
  --bg:     #05080f;   /* page background        */
  --text:   #e2e8f0;   /* body text              */
  --muted:  #718096;   /* secondary / muted text */
}
```

`style.css` has a **numbered table of contents** at the very top — jump to any section number to find the right styles fast.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 — custom properties, grid, flexbox, `backdrop-filter`, keyframe animations |
| Scripting | Vanilla JavaScript — IntersectionObserver, requestAnimationFrame |
| Fonts | [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts |
| Hosting | GitHub Pages  |

---

## 📦 Deployment — GitHub Pages

1. Make sure `index.html` and `style.css` are in the **root** of your repo
2. Go to **Settings → Pages** in your GitHub repo
3. Set source to `main` branch, folder `/` (root)
4. Your site goes live at `https://<your-username>.github.io`

---

## 📁 Push to Existing GitHub Pages Repo

```bash
# Clone your repo
git clone https://github.com/Balrajukonne2629/Balrajukonne2629.git

# Drop index.html, style.css, README.md into the folder, then:
git add index.html style.css README.md
git commit -m "✨ Portfolio redesign — glassmorphism + MERN stack"
git push origin main
```

---

## 📸 Design Inspiration

UI style inspired by **[21st.dev](https://21st.dev)** — dark editorial glassmorphism with aurora backgrounds, pill navbars, and smooth scroll animations.

---

## 👤 Author

**Balraju Konne**
B.Tech Information Technology — CBIT, Hyderabad (2024–2028)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-balrajukonne-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/balrajukonne-319247348)
[![GitHub](https://img.shields.io/badge/GitHub-Balrajukonne2629-black?style=flat&logo=github)](https://github.com/Balrajukonne2629)
[![LeetCode](https://img.shields.io/badge/LeetCode-balrajukonne-orange?style=flat&logo=leetcode)](https://leetcode.com/u/balrajukonne)

---

*Built from scratch — no templates, no frameworks. Just HTML, CSS, and JavaScript.*
