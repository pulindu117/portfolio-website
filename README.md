# Personal Portfolio Website

A responsive personal portfolio website built from scratch with HTML, CSS, and JavaScript — showcasing my background, skills, and projects as a software engineering undergraduate.

🔗 **Live site:** https://pulindu117.github.io/portfolio-website/#portfolio

## Overview

This site is a single-page portfolio covering:

- **About** — background, skills, experience, and education (tabbed layout)
- **Services** — Web Development, Machine Learning/NLP, and Process Automation
- **Portfolio** — featured projects with links to their repositories
- **Contact** — a working contact form connected to Google Sheets, plus a downloadable CV

## Features

- Fully responsive layout with a mobile-friendly slide-out nav menu
- Tabbed content sections (Skills / Experience / Education) with no page reload
- Contact form that submits directly to a connected Google Sheet via Google Apps Script
- One-click CV download
- Icons via Font Awesome

## Tech Stack

- **HTML5** — structure and semantic markup
- **CSS3** — styling and responsive layout
- **JavaScript (vanilla)** — tab switching, mobile menu toggle, form submission handling
- **Google Apps Script + Google Sheets** — backend for the contact form
- **Font Awesome** — icon library

## Project Structure

```
├── index.html       # Main page markup
├── style.css         # Styling and layout
├── Assets/           # Images, logo, and downloadable CV
└── README.md
```

## Getting Started

To run this locally:

1. Clone the repo
   ```bash
   git clone https://github.com/pulindu117/portfolio-website.git
   ```
2. Open `index.html` in your browser — no build step or server required.

## Contact Form Setup

The form submits to a Google Apps Script Web App endpoint tied to a Google Sheet. To use your own:

1. Create a Google Sheet with headers matching the form fields (`Name`, `Email`, `Message`).
2. Set up a Google Apps Script bound to the sheet that accepts POST requests and appends form data as a new row.
3. Deploy the script as a Web App and update the `scriptURL` constant in `index.html` with your deployment URL.

## Author

**Pulindu Pasanjith**
Software Engineering Undergraduate, SLTC Research University

- GitHub: [@pulindu117](https://github.com/pulindu117)
- Email: pulindupasanjith@gmail.com

## License

This project is open for reference and learning purposes. Feel free to fork it, but please don't copy the content as-is for your own portfolio.
