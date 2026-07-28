# shruti-bist — portfolio

A single-page portfolio built as a working Linux terminal — type real commands, browse experience like `systemctl` output, and filter skills like `grep`.

**Live site:** https://cookie-shruti.github.io *(once GitHub Pages is enabled — see below)*

---

## What's on it

- **An actual terminal** — type `whoami`, `experience`, `projects`, `education`, `skills`, `contact`, `ls`, `help`, or `clear` into the prompt and it responds and scrolls to the matching section. Quick-command chips are there too for anyone who'd rather click.
- **Experience, `systemctl`-style** — each role at SOTI shown as a service unit (`active (running)` / `active (exited)`) with role + skillset.
- **Projects, explained properly** — each repo gets a problem statement and four key features, plus links to GitHub and (where available) the write-up.
- **Skills as an interactive tool inventory** — grouped into categories with real technology logos, and a live `grep`-style filter box that dims non-matching tools as you type.
- **Education & certifications** — rendered as `cat education.txt` / `cat certifications.txt` output.
- **A polybar-style top bar** — workspace-number navigation, a live clock, and a running "uptime" counter since the start of the career.

No frameworks, no build step — one self-contained `index.html` (HTML/CSS/vanilla JS), fonts and skill-logo icons loaded from CDN.

## Running locally

Just open the file — no server or install required:

```bash
git clone https://github.com/cookie-shruti/cookie-shruti.github.io.git
cd cookie-shruti.github.io
open index.html   # or double-click it
```

## Deploying (GitHub Pages)

1. Repo is named `cookie-shruti.github.io` so GitHub treats it as the personal root site.
2. `index.html` sits in the repo root.
3. In **Settings → Pages**, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Site goes live at `https://cookie-shruti.github.io` a minute or two after saving.

Push (or re-upload) an updated `index.html` any time — Pages redeploys automatically.

## Tech stack shown on the site

AWS · Microsoft Azure · Docker · GitHub Actions · Jenkins · Argo CD · Terraform · Kubernetes · Bash · Python · RHEL · Ubuntu · Windows Server · Prometheus · Grafana · NGINX Ingress · SonarQube · Nexus · Jira · Postman · Git · Salesforce

## Contact

- Email: shruti.bist33@gmail.com
- GitHub: [github.com/cookie-shruti](https://github.com/cookie-shruti)
- LinkedIn: [linkedin.com/in/shruti-bist-369324188](https://www.linkedin.com/in/shruti-bist-369324188/)
