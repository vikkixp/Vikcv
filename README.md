# ATS-Friendly CV / Resume Website

A clean, professional, single-page CV/Resume website optimized for **Dubai (UAE)** and **India** job markets. Built with pure HTML + CSS — no JavaScript frameworks required.

## ✨ Features

- **ATS-Friendly** — Semantic HTML, standard section headings, clean hierarchy (`h1` → `h2` → `h3`), no tables for layout, no images for text
- **Dubai & India Optimized** — Includes sections commonly expected in both markets: Personal Details, Nationality, Visa Status, Languages, etc.
- **Print-Ready** — Dedicated `@media print` CSS so you can save as PDF directly from the browser (`Ctrl+P` / `Cmd+P`)
- **Responsive** — Looks great on desktop, tablet, and mobile
- **Modern Design** — Dark navy + white + subtle blue accent color scheme with Google Fonts (Inter)
- **Download as PDF** — One-click button that triggers `window.print()` (hidden when printing)

## 📁 File Structure

```
├── index.html   — The CV/Resume page
├── style.css    — All styles (screen + print)
└── README.md    — This file
```

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Open `index.html`** in any web browser
3. **Customize** the placeholder content with your own details (see below)

### Saving as PDF

- Click the **"⬇ Download as PDF"** button at the top of the page, or
- Use your browser's print function (`Ctrl+P` / `Cmd+P`) and select **"Save as PDF"**

## ✏️ How to Customize

Open `index.html` in any text editor and replace the placeholder content:

| Section | What to Change |
|---------|---------------|
| **Header** | Replace "John Doe", job title, phone numbers, email, LinkedIn URL, and location |
| **Professional Summary** | Write your own 3-4 sentence summary |
| **Key Skills** | Replace with your actual skills |
| **Work Experience** | Add your roles, companies, dates, and bullet points |
| **Education** | Your degree, university, and grades |
| **Certifications** | Your actual certifications and year obtained |
| **Languages** | Languages you speak and proficiency levels |
| **Personal Details** | Your nationality, visa status, DOB, etc. |

### Tips for ATS Optimization

- Keep section headings standard (e.g., "Work Experience", "Education", "Key Skills")
- Use plain text for skills — avoid skill bars, charts, or graphics
- Include relevant keywords from the job description
- Use reverse chronological order for work experience
- Spell out acronyms at least once (e.g., "Amazon Web Services (AWS)")

## 🎨 Customizing the Design

Edit `style.css` to change:

- **Colors** — Modify CSS variables in `:root` at the top of the file
- **Fonts** — Change the Google Fonts import in `index.html` and update `--font-main`
- **Spacing** — Adjust padding and margin values as needed

## 📋 Sections Included

1. Full Name & Contact Information
2. Professional Summary
3. Key Skills
4. Work Experience (reverse chronological)
5. Education
6. Certifications & Training
7. Languages
8. Personal Details (Nationality, Visa Status, DOB)
9. References

## 🌍 Market-Specific Notes

### Dubai / UAE
- Personal details (nationality, visa status, DOB) are commonly expected
- Language skills are important — include Arabic if applicable
- Visa/work permit status helps recruiters assess eligibility

### India
- Personal details section is common in Indian CVs
- Education with CGPA/percentage is standard
- Include all relevant certifications

## License

This project is open source. Feel free to use and modify for your personal or professional use.
