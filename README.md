# Legal Consultancy Landing Page

A professional landing page built with HTML, Tailwind CSS, and JavaScript.

## Installation

1. Install dependencies:
```bash
npm install
```

## Development

Build CSS once:
```bash
npm run build-css
```

Watch for changes and rebuild automatically:
```bash
npm run watch-css
```

## Production

For production, build the CSS with minification:
```bash
npm run build-css
```

The built CSS file will be in `dist/output.css`.

## Project Structure

```
landingPage/
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
├── styles.css          # Additional custom styles (legacy)
├── package.json        # NPM dependencies
├── tailwind.config.js  # Tailwind configuration
├── src/
│   └── input.css       # Tailwind source file
└── dist/
    └── output.css      # Built Tailwind CSS (generated)
```

## Features

- Responsive design
- Dark/Light mode toggle
- Preloader animation
- Form validation
- Testimonials slider
- Dynamic form fields
- Smooth animations and hover effects

## Notes

- Tailwind CSS is installed locally (not using CDN)
- Run `npm run build-css` after making changes to `src/input.css` or `tailwind.config.js`
- Use `npm run watch-css` during development for automatic rebuilding

