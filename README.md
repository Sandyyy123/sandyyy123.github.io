> **Proprietary - All Rights Reserved.** (c) 2026 Sandeep Grover. This repository is licensed to Sandeep Grover and may **not** be used, run, copied, modified, distributed, or used to train models without prior written permission. Public visibility does not grant a license. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

---

# sandyyy123.github.io

The personal AI/ML portfolio site of Sandeep Grover, served as a GitHub Pages site.

Live site: https://sandyyy123.github.io/

## Overview

This repository holds a single-page static website that presents Sandeep Grover's AI/ML portfolio. The page is a self-contained `index.html` (HTML with inline CSS, no JavaScript and no external libraries) that lists 50 public project repositories grouped into 10 subject domains. Each project is shown as a card with a short description, the tools used, a headline metric, a link to its GitHub repository, and a link to its own live demo page under `sandyyy123.github.io`.

## What is inside

- **Hero section** with a summary line: "50 production-ready repositories across 10 domains" and a small stats row:
  - 50 Public Repos
  - 10 Domains
  - 97% Best Accuracy
  - 12+ Years Experience
- **Domain navigation bar** with ten in-page anchor links, one per domain.
- **Ten domain sections**, each with a title, a one-line description, a project count, and a grid of project cards:
  - Finance & Quantitative Analysis (9 projects)
  - Healthcare & Medical AI (4 projects)
  - Computer Vision (5 projects)
  - Classical NLP & Text Processing (4 projects)
  - Time Series & Forecasting (5 projects)
  - Recommendation Systems (3 projects)
  - LLM & Generative AI (9 projects)
  - Business Intelligence & Analytics (3 projects)
  - Content & Publishing AI (4 projects)
  - Analytical Tools & Simulations (4 projects)
- **50 project cards** (counts above sum to 50). Each card links to its GitHub repository (`github.com/Sandyyy123/<project>`) and to a live demo page (`sandyyy123.github.io/<project>/`).
- **Footer** linking back to the GitHub profile.

## Tech stack

- Static HTML (one `index.html` file). GitHub reports the repository as 100% HTML.
- Inline CSS for styling (a dark theme with an indigo and purple accent palette).
- No JavaScript, no build step, no external scripts or stylesheets, and no Jekyll configuration are present in the repository.
- Hosting: GitHub Pages (Pages is enabled and the build status is "built").

## Repository structure

```
.
├── index.html    # The entire portfolio page (HTML + inline CSS)
├── LICENSE       # Proprietary, all-rights-reserved license
├── NOTICE        # Ownership and usage notice
└── README.md     # This file
```

## How it is served and local preview

The site is published through GitHub Pages from the default branch (`main`) and is live at https://sandyyy123.github.io/.

Because the site is a single static HTML file with no build step, you can preview it locally by opening `index.html` directly in a browser, or by serving the folder over a simple local HTTP server, for example:

```bash
# example: serve the repo root on http://localhost:8000
python3 -m http.server 8000
```

Then open http://localhost:8000/ in a browser.

## Author

**Dr. Sandeep Grover** - [github.com/Sandyyy123](https://github.com/Sandyyy123)
