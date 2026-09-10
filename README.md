# bb_gt — geekingthings.com

Personal résumé site and portfolio for Brannon Breau, ServiceNow Developer.
Static HTML/CSS with a little vanilla JavaScript — no build step, no dependencies.

## Contents

| Path | Description |
|------|-------------|
| `index.html` | Main résumé / landing page (summary, skills, experience, education, certifications, projects) |
| `sn-reference.html` | ServiceNow developer reference — a categorized cheat-sheet of scripting notes and snippets |
| `projects/project-template.html` | Reusable layout template for individual project write-ups |
| `images/` | Favicons, web app manifest, and certification badge images |

### Not tracked in this repo

The following are kept locally but excluded via `.gitignore`:

- `*.pdf` — résumé and certification PDFs (`resume/`, `certs/`)
- `projects/*.html` — individual project pages (only `project-template.html` is tracked)

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Tech

- Semantic HTML5, hand-written CSS (custom properties, flex/grid layout)
- Google Fonts: Space Grotesk, Inter, JetBrains Mono
- No frameworks, no bundler

## Links

- Site: https://geekingthings.com
- GitHub: https://github.com/brannon-breau
- LinkedIn: https://linkedin.com/in/bbreau
- Credly: https://www.credly.com/users/brannon-breau
