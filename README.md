# Vera Lynn DeGraw | Website Portfolio

A personal portfolio built with HTML, CSS, and JavaScript, and a practical example of turning a reusable website template into a personalized web experience.

**Portfolio:** https://veralynndegrawportfolio.web.app/

**Source Code:** https://github.com/VeraLynnDeGraw/Website-Portfolio

**Starting Template:** https://github.com/VeraLynnDeGraw/Website-Template

## Overview

This repository contains my personal portfolio and documents its evolution from an initial website template into a customized, independently maintained website.

The project demonstrates how a small, accessible foundation can become a personal web presence through deliberate changes to visual identity, content, layout, and presentation.

The site uses core web technologies rather than requiring a front-end framework or a complex build process.

## Explore the Project

Once the latest version has been deployed, these pages will be available from the portfolio's Firebase Hosting site.

- **[Personal Portfolio](https://veralynndegrawportfolio.web.app/)** — The current portfolio, featuring my projects, interests, and approach to building software.
- **[Original Template Reference](https://veralynndegrawportfolio.web.app/template-reference/)** — A preserved copy of the original Website-Template starting point.
- **[First Portfolio Concept](https://veralynndegrawportfolio.web.app/portfolio-evolution/)** — An early personalized version, beginning with the idea that "Ideas deserve a chance to grow."

These reference pages illustrate the starting point and an early stage of customization. They are preserved separately from the main portfolio.

## Project Goals

- Create a personal portfolio that reflects my identity and work.
- Demonstrate a real-world use case for Website-Template.
- Preserve earlier versions so the project's evolution remains visible.
- Keep the source understandable and approachable.
- Use version control and clear documentation to support future maintenance.
- Publish a lightweight static website with Firebase Hosting.

## Features

- Responsive portfolio layout.
- Custom visual identity and botanical framing.
- Project, interest, and contact sections.
- HTML, CSS, and JavaScript in a lightweight static site.
- Preserved template and portfolio reference pages.
- Version-controlled source and hosting configuration.

## Technologies

| Technology | Purpose |
| --- | --- |
| HTML | Page structure and content |
| CSS | Layout, responsive styling, and visual identity |
| JavaScript | Client-side behavior |
| Git and GitHub | Version control and source hosting |
| Firebase Hosting | Static website hosting |

## Run Locally

Clone this repository:

```bash
git clone https://github.com/VeraLynnDeGraw/Website-Portfolio.git
cd Website-Portfolio
```

Start a local server with Python:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000 in your browser.

Stop the server with `Ctrl+C`.

The root `index.html` is the main source page. The `public/` directory contains the files configured for Firebase Hosting.

## Deploy to Firebase Hosting

This project uses the Firebase project `veralynndegrawportfolio`.

Install and authenticate the [Firebase CLI](https://firebase.google.com/docs/cli), then run the deployment command from the repository directory:

```bash
firebase deploy --only hosting --project veralynndegrawportfolio
```

The `firebase.json` configuration publishes the `public/` directory. Keep the project ID explicit when deploying so the portfolio is not accidentally published to the original template's Firebase project.

## Project History

The repository preserves earlier HTML versions as development references. The original template and first portfolio concept are copied into dedicated folders under `public/` for separate viewing.

These snapshots help document the transition from a reusable starting point to a personalized website. The current portfolio remains the main version.

## License

See [LICENSE](LICENSE) for the terms governing reuse and distribution.
