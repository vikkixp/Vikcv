# Vik — Personal Portfolio

A modern, responsive single-page portfolio website built with vanilla HTML, CSS, and JavaScript. Features a dark color scheme, smooth animations, and a clean design.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)

## 🚀 Quick Start

Simply open `index.html` in your browser — no build tools or dependencies required.

```bash
# Or use a local server for the best experience:
npx serve .
# or
python3 -m http.server 8000
```

## 📁 Project Structure

```
├── index.html    # Main HTML structure
├── styles.css    # All styles and responsive design
├── script.js     # Interactivity and animations
└── README.md     # This file
```

## ✏️ How to Customize

### Personal Information

Edit `index.html` to replace placeholder content:

| What to change | Where to find it |
|---|---|
| **Name** | Search for "Vik" — appears in the hero section, nav logo, and footer |
| **Tagline** | `.hero-tagline` — "Full-Stack Developer & Creative Problem Solver" |
| **Bio** | `.about-text` — the two paragraphs in the About section |
| **Stats** | `.about-stats` — years of experience, projects, clients |
| **Profile image** | Replace the `.about-image-placeholder` div with an `<img>` tag |
| **Email** | Search for "hello@example.com" in the contact section |
| **Location** | Search for "San Francisco, CA" |
| **Social links** | Update the `href` attributes in `.social-links` |
| **Page title** | `<title>` tag in the `<head>` |

### Skills

Edit the four `.skill-card` blocks in the Skills section. Each card has:
- An emoji icon (`.skill-icon`)
- A title (`<h3>`)
- A list of skills (`<ul>`)

### Projects

Edit the `.project-card` blocks in the Projects section. For each project:
1. Update the gradient background or replace with an `<img>` tag
2. Change the title, description, and tags
3. Update the "Live Demo" and "Source Code" links

### Colors & Theme

Edit the CSS variables at the top of `styles.css`:

```css
:root {
  --bg-primary: #0a0a0f;       /* Main background */
  --bg-secondary: #12121a;     /* Alternate section background */
  --bg-card: #1a1a2e;          /* Card backgrounds */
  --text-primary: #e4e4e7;     /* Main text color */
  --text-secondary: #a1a1aa;   /* Muted text color */
  --accent: #6366f1;           /* Primary accent (indigo) */
  --accent-hover: #818cf8;     /* Accent hover state */
}
```

### Fonts

The site uses [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts. To change it, update the `<link>` tag in `index.html` and the `--font` variable in `styles.css`.

### Contact Form

The contact form currently logs submissions to the console. To make it functional:
- Integrate with [Formspree](https://formspree.io), [Netlify Forms](https://www.netlify.com/products/forms/), or a custom backend
- Edit the form handler in `script.js` (search for `contact-form`)

## 🎨 Features

- **Responsive** — Mobile, tablet, and desktop layouts
- **Dark theme** — Modern dark color scheme with accent colors
- **Smooth scrolling** — CSS smooth scroll with JS fallback
- **Scroll animations** — Elements fade in as you scroll
- **Active nav highlighting** — Navigation updates based on scroll position
- **Mobile menu** — Hamburger menu for small screens
- **No dependencies** — Pure HTML, CSS, and JavaScript

## 📄 Deployment

This is a static site — deploy it anywhere:

- **GitHub Pages**: Push to a repo and enable Pages in settings
- **Netlify**: Drag and drop the folder, or connect your repo
- **Vercel**: Import the repo for instant deployment

## 📝 License

Feel free to use this template for your own portfolio. Attribution is appreciated but not required.
