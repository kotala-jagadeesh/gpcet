# GPCET Website (Sample Homepage)
Veiw the site : https://kotala-jagadeesh.github.io/gpcet/"
A responsive, single-page homepage for **G. Pulla Reddy College of Engineering & Technology (GPCET), Kurnool, Andhra Pradesh**.

> **Note:** This is an unofficial sample project. The content is placeholder text and is not taken from the official website ([gpcet.ac.in](https://gpcet.ac.in)). Replace it with verified information before any public use.

## Features

- Single `index.html` file with no dependencies or build step
- Responsive layout for mobile, tablet and desktop
- Automatic dark mode based on system settings
- Sticky navigation with smooth scrolling
- Sections: About, Departments, Admissions, Notices and Contact
- Keyboard-friendly focus styles

## Project structure

```
.
├── index.html   # Page markup, CSS and JavaScript
└── README.md
```

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Open `index.html` in any web browser.

No server or installation is required.

## Customisation

- **Content:** Edit the text inside each `<section>` in `index.html`.
- **Colours:** Change the CSS variables in the `:root` block at the top of the `<style>` tag (`--ink`, `--gold`, `--bg`, and so on).
- **Logo:** Replace the `.crest` element in the header with an `<img>` tag pointing to the official logo.
- **Departments:** Add or remove `.card` links in the Departments section and point each `href` to its page.
- **Contact details:** Add the official phone number and email in the Contact section.

## Deployment

### GitHub Pages

1. Push the project to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, then save.
4. The site will be available at `https://<your-username>.github.io/<your-repo>/`.

## Tech stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (footer year only)

## Contributing

Suggestions and improvements are welcome. Fork the repository, create a branch, commit your changes and open a pull request.

## Disclaimer

This project is not affiliated with or endorsed by GPCET. College names and trademarks belong to their respective owners.

