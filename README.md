# Bondi

Bondi is a responsive agency landing page design built with HTML, CSS, and Bootstrap. The page currently includes a navigation bar, hero section, and a services/features section, with local image and icon assets.

## Technologies

- HTML5
- Bootstrap 5 (CSS and bundled JavaScript are included locally)
- Custom CSS in `css/bondi.css`
- Font Awesome assets included locally
- Google Fonts (Roboto), loaded from Google Fonts

## Preview

Open `index.html` in a web browser. No package installation or build step is required. For local development, you can also serve the project directory with any static file server.

## Project structure

```text
Bondi/
├── index.html          # Landing page markup
├── css/
│   ├── bondi.css       # Project styles
│   ├── bootstrap.min.css
│   └── all.min.css     # Icon styles
├── js/
│   ├── bootstrap.bundle.min.js
│   └── all.min.js
├── imgs/               # Page and portfolio images
└── webfonts/           # Local icon fonts
```

## Notes

- Bootstrap, Font Awesome, images, and webfonts are stored in the repository and referenced with relative paths.
- The Roboto font is requested from Google Fonts, so that font requires an internet connection. The page remains usable if the external font cannot load, with the browser's fallback font.
- `Preview.png` is a visual reference image. `Bondi.psd`, if present, is the editable design source and is not required to run the page.
