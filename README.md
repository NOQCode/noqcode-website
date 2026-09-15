# NOQCode Website

A polished, static personal brand website for NOQCode, presenting Nico Ohm, selected technical expertise, and the PractiPrep roadmap in a compact interactive interface.

The project combines a minimal portfolio-style landing page with expandable information cards, a metallic WebGL background, responsive mobile behavior, and a privacy-friendly static setup without accounts, tracking, or backend services.

## Live Website

[Open the NOQCode website](https://www.noqcode.de)

## Project Overview

The website was created as a focused public presence for NOQCode. Its primary goal is to introduce the person behind the brand, show relevant technical expertise, and connect visitors to the PractiPrep project without turning the page into a large marketing site.

The interface centers around two compact cards:

- **Nico Ohm / Expertise** introduces the technical profile and links to GitHub.
- **PractiPrep / Roadmap** summarizes the current product milestones and links to the live PractiPrep website.

Both cards use the same interaction model and visual language, keeping the page balanced on desktop while stacking naturally on mobile.

## Key Features

- Static single-page website
- Responsive layout for mobile, tablet, and desktop
- Expandable profile and project cards
- Personal expertise overview with timeline-inspired styling
- PractiPrep roadmap with completed and planned milestones
- GitHub and PractiPrep website links
- Custom NOQCode favicon and brand mark
- Profile and product imagery optimized for the page design
- WebGL-powered metallic background with interaction feedback
- Static fallback background for browsers without reliable WebGL support
- Reduced-motion support for users who prefer less animation
- No account system, analytics integration, database, or backend API

## Privacy and Safety

This repository contains only the public static website.

- No API keys, tokens, secrets, or environment variables are included.
- No authentication flow is connected.
- No database or backend service is used by the website.
- No form submission or personal-data collection is implemented.
- No analytics script, tracking pixel, or cookie-based service is connected.
- All visible personal and contact information is intentional public website content.

Because the project is static, publishing it does not expose private runtime infrastructure or user data.

## Technology

The project intentionally uses a lightweight, dependency-free frontend stack:

- Semantic HTML5
- Modern CSS with responsive layout rules and design tokens
- Vanilla JavaScript for card interactions and WebGL rendering
- WebGL for the animated metallic background
- Static image assets for profile and brand visuals
- GitHub for version control and public source hosting

No build pipeline, package installation, environment variables, or runtime backend is required.

## Project Structure

```text
NOQCode_Website/
├── index.html                              Complete website, styling, and interaction logic
├── NOQCode_Profile_GitHub_Silver_1024.png NOQCode brand mark and favicon source
├── Pic_Nico_head.png                       Profile image used in the expertise card
├── logo_grayscale.png                      PractiPrep logo used in the roadmap card
├── .gitignore                              Local ignore rules
└── README.md                               Project documentation
```

## Run Locally

Clone the repository:

```bash
git clone https://github.com/NOQCode/noqcode-website.git
cd noqcode-website
```

Start any local static file server. For example, with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

You can also open `index.html` directly, although a local web server provides behavior closer to a hosted environment.

## Deployment

The website is designed to be deployed as a static site. It can be hosted through any static hosting provider, including Vercel, GitHub Pages, Netlify, or a traditional web server.

Because the project has no build step and no backend, deployment serves the repository files directly. No secrets or environment variables are required.

## Design Direction

The visual system uses a dark metallic background, restrained typography, glass-like cards, cyan accent details, and subtle interaction feedback. The goal is to feel technical, calm, and premium without overloading the page with content.

The page is intentionally compact: the first view gives a strong brand signal, while the expandable cards reveal more context only when the visitor wants it.

## Project Scope

This repository is intended to demonstrate:

- a personal brand landing page,
- a compact expertise presentation,
- a public product roadmap preview,
- static frontend implementation without a framework,
- privacy-conscious public source code.

It is not a backend application, dashboard, or data-collection service.

## Author

Created by [Nico Ohm](https://github.com/Nico-Ohm).
