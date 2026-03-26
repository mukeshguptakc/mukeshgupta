# mukeshkcgupta.in

Personal portfolio and resume website for **Mukesh Gupta** — Member of Technical Staff III at Cohesity, with 10+ years of experience in distributed storage, data protection, and cloud-native backend engineering.

🌐 **Live site:** [mukeshkcgupta.in](https://mukeshkcgupta.in)

---

## Pages

| Page | Description |
|------|-------------|
| **Home** | Hero section with tagline and quick links |
| **About** | Bio, background, and interests |
| **Skills** | Color-coded skill grid — languages, systems, cloud, storage, data protection |
| **Projects** | Thematic areas of expertise: NAS/SAN, Cloud, Mentorship |
| **Resume** | Online resume (no contact details) with experience timeline and LinkedIn link |

---

## Tech Stack

- **Jekyll** — static site generator, natively supported by GitHub Pages
- **Custom CSS** — dark theme, no frameworks
- **Fonts** — Inter (UI) + JetBrains Mono (code/labels) via Google Fonts
- **Hosting** — GitHub Pages with custom domain

---

## Local Preview

### Option A — Jekyll (full build)

Requires Ruby 3.x and Bundler:

```bash
gem install bundler
bundle install
bundle exec jekyll serve
# Open http://localhost:4000
```

### Option B — Static preview (no Ruby needed)

Open `preview.html` directly in any browser — fully self-contained, no dependencies.

---

## Structure

```
mukeshgupta/
├── _config.yml          # Jekyll site config
├── _layouts/
│   └── default.html     # Shared layout with top nav
├── assets/css/
│   └── style.css        # Full site styles
├── index.html           # Home
├── about.md             # About
├── skills.md            # Skills
├── projects.md          # Projects
├── resume.md            # Online resume (LinkedIn only, no contact)
├── preview.html         # Self-contained static preview
└── CNAME                # Custom domain config
```

---

## Links

- LinkedIn: [linkedin.com/in/mukesh-gupta-847a54105](https://www.linkedin.com/in/mukesh-gupta-847a54105/)
- GitHub: [github.com/mukeshguptakc](https://github.com/mukeshguptakc)
