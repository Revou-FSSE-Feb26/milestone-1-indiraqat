# Indira Qatrunnada - Personal Website
### Milestone 1 | RevoU FSSE Feb26

---

## Overview

This is my personal website built as part of **Milestone 1** for the RevoU Full Stack Software Engineering program. It serves as a digital portfolio and personal introduction page, sharing who I am, my background, projects, and a way to get in touch.

Building on the HTML structure from Milestone 1, this update adds a dedicated CSS stylesheet to style and improve the visual appearance of the website.

The site is hosted live on GitHub Pages and accessible to anyone.

🔗 **Live site:** [https://revou-fsse-feb26.github.io/milestone-1-indiraqat](https://revou-fsse-feb26.github.io/milestone-1-indiraqat)

---

## Features Implemented

### Module 1 — HTML Structure
- **Home Section** — Introduction with name and tagline
- **About Me Section** — Bio, education, work experience, skills, and interests & hobbies
- **Projects Section** — Table listing current and past projects with description, tech used, and status
- **Contact Section** — Form with required fields (name, email, message), optional dropdown for reason, checkboxes for preferred contact method, and reset/submit buttons
- **Sticky Navigation Bar** — Links to jump directly to each section, sticks to top on scroll
- **Footer** — Credits and GitHub link
- **Material Symbols Icons** — Google icon font used in the Interests & Hobbies section
- **Semantic HTML** — Proper use of `<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`, `<blockquote>`, `<form>`

### Module 2 — CSS Styling
- **External Stylesheet** — All styles in a separate `index.css` file linked to `index.html`
- **Animations** — Fade-up entrance animations on page load using `@keyframes`, staggered across sections
- **Font Hierarchy** — Different sizes, weights, and colors for `h1`, `h2`, `h3`, and `p` to create clear visual hierarchy
- **Color Theme** — Consistent warm brown and cream tones throughout the page
- **CSS Grid Layout** — Used in the hero section, about section, education & skills columns, and hobbies grid
- **Flexbox Layout** — Used in the navigation bar, footer, and education card elements
- **max-width** — Main content capped at 1100px for comfortable reading on wide screens
- **Background Image** — Subtle dot pattern using `radial-gradient` with `background-size`
- **Responsive Images** — Profile photo uses `max-width: 100%`, `height: auto`, and `object-fit: cover`
- **Hover Effects** — On nav links, hero photo, education card, skill pills, hobby cards, table rows, and buttons
- **Transitions & Animations** — Smooth transitions on all interactive elements
- **Education Card** — Styled card with degree name, Cum Laude badge, university, and GPA tag
- **Skills Pills** — Grouped pill/tag chips by category with hover fill effect
- **Hobby Cards** — Icon cards in a two-column grid with Google Material icons
- **Styled Form** — Inputs, textarea, select, and buttons styled with consistent colors, rounded corners, and focus highlight
- **Responsive Design** — Two breakpoints using media queries:
  - Tablet (768px and below)
  - Mobile (600px and below)

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and all content |
| CSS3 | Styling, layout, animations, hover effects, and responsive design |
| Google Fonts — Material Symbols | Icons for the Interests & Hobbies section |
| Git | Version control |
| GitHub Pages | Deployment and hosting |

---

## File Structure

```
/
├── index.html       # Main HTML file
├── style.css        # Stylesheet
├── profile.jpg      # Profile photo used in the hero section
└── README.md        # This file
```

---

## How to Access the Website

1. Visit the live link: [https://revou-fsse-feb26.github.io/milestone-1-indiraqat](https://revou-fsse-feb26.github.io/milestone-1-indiraqat)
2. Use the sticky navigation bar at the top to jump to any section
3. Fill in the contact form to get in touch

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Revou-FSSE-Feb26/milestone-1-indiraqat.git
   ```
2. Open `index.html` in any browser — no setup or installation needed.

---

*Made by Indira Qatrunnada · RevoU FSSE Feb26*
