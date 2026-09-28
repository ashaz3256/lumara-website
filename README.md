# Lumara Website

A responsive single-page portfolio site for Lumara, a small software engineering studio. It presents the team's services and showcases three projects: a real-time sports analytics dashboard, a trading journal, and an AI-powered car diagnostic tool.

Built with plain HTML, CSS and JavaScript, with no framework or build step.

## Features

- **Single-page layout** with Home, About, Services, Portfolio and Contact sections and smooth-scroll navigation
- **Filterable portfolio** with hover effects and links to live project demos
- **Contact form** that opens the visitor's email client with the message pre-filled
- **Scroll-triggered animations** using the Intersection Observer API
- **Responsive design** for desktop, tablet and mobile

## Tech Stack

- HTML5, CSS3 (Flexbox, Grid)
- JavaScript (ES6+)
- [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts and [Font Awesome](https://fontawesome.com/) icons, both loaded from a CDN

## Getting Started

The site is static, so there is nothing to install. Either open `index.html` in a browser or serve the folder locally:

```bash
git clone https://github.com/ashaz3256/lumara-website.git
cd lumara-website
npx http-server
```

## Project Structure

```
index.html    Page markup and content
styles.css    Styles, animations and responsive layout
script.js     Navigation, portfolio filtering, form handling and scroll effects
```

## Deployment

The site can be hosted on any static host (Vercel, Netlify, GitHub Pages).

## License

Released under the [MIT License](LICENSE).
