# Vikas Sharma — Portfolio Website

A modern, professional single-page portfolio website for **Vikas Sharma**, a Sales & Client Acquisition Specialist with 4+ years of experience in B2B/B2C sales, lead generation, and account management.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

- **Modern Dark Theme** — Premium dark design with electric blue gradient accents
- **Smooth Animations** — Scroll-triggered fade-in/slide-up animations using Intersection Observer
- **Particle Background** — Subtle animated particle network in the hero section (vanilla JS)
- **Typing Effect** — Animated tagline cycling through key roles
- **Glassmorphism Cards** — Frosted glass card effects throughout
- **Fully Responsive** — Mobile-first design that works on all devices
- **Print-Friendly** — Clean print styles for ATS/CV purposes
- **SEO Optimized** — Semantic HTML, Open Graph tags, proper heading hierarchy
- **No Dependencies** — Pure HTML, CSS, and JavaScript — no frameworks or libraries

## 📁 Project Structure

```
├── index.html              # Main HTML file
├── styles.css              # All styles with CSS custom properties
├── script.js               # Interactions, animations, particles
├── Vikas_Sharma_CV.pdf     # Downloadable CV (placeholder)
└── README.md               # This file
```

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/vikkixp/Vikcv.git
   cd Vikcv
   ```

2. Open `index.html` in your browser, or use a local server:
   ```bash
   # Using Python
   python3 -m http.server 8000

   # Using Node.js
   npx serve .
   ```

3. Visit `http://localhost:8000`

## 🎨 Customization

### Theme Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --bg-primary: #0a0a0f;
    --accent: #4f8fff;
    --accent-gradient: linear-gradient(135deg, #4f8fff, #a855f7);
    /* ... more variables */
}
```

### Content

All content is in `index.html`. Update:
- Personal details in the Hero and About sections
- Work experience in the Timeline section
- Skills in the Skills section
- Education details
- Contact information and social links

### Profile Photo

Replace the SVG placeholder in the About section's `.image-placeholder` div with an `<img>` tag:

```html
<div class="image-frame">
    <img src="your-photo.jpg" alt="Vikas Sharma">
</div>
```

### Contact Form

The form currently uses a `mailto:` fallback. To enable a real form backend:

1. Sign up at [Formspree](https://formspree.io)
2. Replace the form `action` URL in `index.html`
3. Remove the `e.preventDefault()` in `script.js`

### CV Download

Replace `Vikas_Sharma_CV.pdf` with your actual CV file.

## 🌐 Deploy on GitHub Pages

1. Push your code to a GitHub repository
2. Go to **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at `https://<username>.github.io/<repo-name>/`

## 📱 Sections

| Section | Description |
|---------|-------------|
| **Hero** | Full-viewport intro with particle animation, typing effect, and CTA buttons |
| **About** | Profile summary, key stats (4+ years, 3 companies, 2 countries), and tags |
| **Experience** | Vertical animated timeline with 3 roles and detailed bullet points |
| **Skills** | Categorized skill cards — Sales & Marketing, Technical Tools, Outreach |
| **Education** | PGDBM from Symbiosis Institute of Management Studies |
| **Contact** | Email, phone, location info + contact form |
| **Footer** | Copyright and attribution |

## 📄 License

This project is open source and available for personal use.
