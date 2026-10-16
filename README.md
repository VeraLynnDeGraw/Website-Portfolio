# Website Template

A lightweight, customizable website starter built with HTML, CSS, and JavaScript, with public hosting through Firebase.

**Live Demo:** https://wesite-template.web.app  
**Source Code:** https://github.com/VeraLynnDeGraw/Website-Template

## Overview

Website Template is a simple starting point for building and publishing a website without requiring a front-end framework, a package installation process, or a complex build pipeline.

The project demonstrates a straightforward approach to web development: keep the structure understandable, make the experience interactive, and make deployment accessible.

It is designed to be explored, customized, and reused as a foundation for personal projects, portfolio pages, prototypes, and small web experiences.

## Purpose

The goal of this project is to provide a practical, reusable starting point for turning an idea into a working website.

Rather than introducing unnecessary complexity, the template keeps its core technologies visible and approachable. Developers can inspect the source, understand how the page works, modify its appearance and behavior, and publish their own version.

## Features

- **HTML, CSS, and JavaScript:** Core web technologies without a required front-end framework.
- **Interactive experience:** A dark visual design with an amber light effect that visitors can explore.
- **Simple customization:** A single primary HTML file containing the page structure, styling, and interaction logic.
- **Public deployment:** Hosted through Firebase Hosting.
- **Reusable foundation:** Suitable for experiments, personal websites, prototypes, and portfolio projects.
- **Version-controlled configuration:** Firebase Hosting configuration is included in the repository.

## Technologies

| Technology | Purpose |
| --- | --- |
| HTML | Page structure and content |
| CSS | Visual presentation and styling |
| JavaScript | Interactive behavior |
| Git and GitHub | Version control and source hosting |
| Firebase Hosting | Public website deployment |

## Getting Started

### View the live website

Visit [https://wesite-template.web.app](https://wesite-template.web.app).

### Clone the repository

```bash
git clone https://github.com/VeraLynnDeGraw/Website-Template.git
cd Website-Template
```

### Run it locally

You can open `index.html` directly in a browser. Alternatively, if Python is installed, run:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

Stop the local server with `Ctrl+C`.

## Make It Your Own

1. Edit `index.html` to change the content, styling, and interactive behavior.
2. Preview your changes locally.
3. Create your own GitHub repository to maintain your customized version.
4. Configure Firebase Hosting with a Firebase project you control if you want to publish your own copy.

The existing Firebase configuration points to the original project. A new deployment should use your own Firebase project rather than unintentionally publishing to the original site.

## Deployment

This project uses Firebase Hosting. The `firebase.json` file defines the hosting configuration, and `.firebaserc` associates the original project with its Firebase project ID.

For your own deployment, install the [Firebase CLI](https://firebase.google.com/docs/cli), authenticate, and initialize Hosting for your own Firebase project.

## What This Project Demonstrates

This repository provides a practical example of:

- Building a small web experience with core front-end technologies.
- Creating an interactive interface.
- Organizing source code for reuse and customization.
- Using Git and GitHub to manage project history.
- Configuring and deploying a static website with Firebase Hosting.
- Documenting a project so another developer can run and adapt it.

## Project Status

The initial website is deployed and publicly accessible. The template can be extended with additional pages, improved accessibility, automated deployment, testing, and other features as the project evolves.

## License

See the [LICENSE](LICENSE) file for the terms governing reuse and distribution.
