# revedge-puma-web-minicatalog

Mini catalog website for Informatics merchandise, developed as part of the PUMA Student Academic and Technology assignment.

**Live site:** https://caseylilbro.github.io/revedge-puma-web-minicatalog/

## About

Revedge is a one-page merch catalog for Informatics students. Visitors can browse the varsity jacket and other merchandise, then place a pre-order through the linked form.

## Sections

- **Home**: hero with parallax effect
- **Preorder**: varsity jacket highlight with a draggable photo strip
- **Collection**: merchandise cards (shirts, stickers, and more)
- **Contact**: contact details in the footer

## Tech stack

- HTML, CSS, and vanilla JavaScript (single page, no build step)
- [Lenis](https://github.com/darkroomengineering/lenis) for smooth scrolling
- Fonts: [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts) and Dirtyline (custom, 36 Days of Type 2022)

## Project structure

```
.
├── index.html     # the whole page (HTML, CSS, JS)
├── images/        # photos and illustrations used on the page
├── fonts/         # custom font files (Dirtyline)
├── assets/        # favicon and other static assets
├── figma/         # design files and exports
└── README.md
```

## Run locally

No installation needed.

1. Clone or download this repository.
2. Open `index.html` in a browser.

For a local server, use the **Live Server** extension in VS Code: right-click `index.html` and choose **Open with Live Server**.

## Deployment

The site is hosted on **GitHub Pages**, served from the `main` branch (root folder). Every push to `main` updates the live site automatically after a minute or two.

## Notes

- All file paths are relative, so the site works from a subfolder such as `/revedge-puma-web-minicatalog/`.
- File names are case-sensitive on the server. Keep them consistent with the paths in `index.html`.

## Vibe coding

Yes, I vibe coded this, with AI help. Problem with that? Then you're pathetic.

## Author

Muhammad Nabil ([@caseylilbro](https://github.com/caseylilbro))
