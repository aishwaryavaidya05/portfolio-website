# Aishwarya Vaidya · Portfolio

A responsive, animated personal portfolio built with **React**, showcasing AI/ML, data analytics and frontend projects. Designed with a calm navy, cream and sky-blue palette and deployed on **Vercel**.

**Live site:** [https://aishwarya-vaidya-portfolio.vercel.app/](https://aishwarya-vaidya-portfolio.vercel.app/)

## Highlights

- **Modern UI/UX:** a cohesive navy, cream and light-blue design system, with Playfair Display and DM Sans typography and alternating light and dark sections.
- **Fully responsive:** fluid typography and layouts with CSS Grid and Flexbox that adapt across desktop, tablet and mobile.
- **Delightful animation:** an animated SVG retro-computer mascot (blinking eyes, twinkling sparkles), a typewriter speech bubble, a custom boba-cup cursor and smooth hover and scroll transitions.
- **Interactive project showcase:** category tabs with a swipeable, scroll-snapping carousel, plus a detail page for each project.
- **Smart navigation:** sticky header with scroll-aware active links and a mobile menu.
- **Accessible by default:** semantic HTML, ARIA labels and `prefers-reduced-motion` support.

## Sections

Home · About · Experience (with certificates) · Research · Projects · Skills · Contact

## Tech Stack

| Area | Tools |
|---|---|
| Framework | React, Vite |
| Styling | Plain CSS (custom properties, Grid, Flexbox, keyframe animations) |
| Icons | lucide-react |
| Deployment | Vercel |

## Getting Started

```bash
# install dependencies
npm install

# start the dev server
npm run dev

# create a production build
npm run build
```

## Project Structure

```
├── public/          # images and static assets (profile photo, article images)
├── src/
│   ├── App.jsx      # components and portfolio content
│   ├── App.css      # styles, theme tokens and animations
│   └── main.jsx     # app entry point
├── index.html
└── package.json
```

## Customizing

All content (experience, projects, skills, article pages) lives as plain data at the top of `src/App.jsx`. Update the arrays there and the UI follows. Theme colors are CSS variables at the top of `src/App.css`.

## Deployment

Deployed with [Vercel](https://vercel.com). Every push to `main` triggers a new production build.

## Contact

[LinkedIn](https://www.linkedin.com/in/aishwarya-vaidya-) · [GitHub](https://github.com/aishwaryavaidya05) · vaidyaaishwarya05@gmail.com
