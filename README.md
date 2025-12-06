# EACL 2026 Abjad NLP Shared Task: Medical Text Classification in Arabic

Official website for the EACL 2026 Abjad NLP Shared Task focused on medical text classification in Arabic.

## Website

The website is automatically deployed via GitHub Pages at:
https://balajinaga.github.io/EACL2026-Abjad-NLP-SharedTask/

## Deployment

This site uses GitHub Actions for automatic deployment:
- Any push to the `main` branch triggers automatic deployment
- Deployment typically completes within 2-5 minutes
- The workflow can also be triggered manually from the Actions tab

## Local Development

To view the site locally:
1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server: `python -m http.server 8000`

## Repository Structure

```
.
├── index.html          # Main website page
├── css/
│   └── style.css       # Stylesheet
├── js/
│   └── main.js         # Navigation JavaScript
├── images/             # Images and assets
├── 404.html            # Custom 404 error page
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions deployment workflow
```

## GitHub Pages Configuration

To enable GitHub Pages for this repository:

1. Go to repository Settings → Pages
2. Under "Build and deployment":
   - Source: Select "GitHub Actions"
3. The site will be available at the GitHub Pages URL

## Contributing

To update the website:
1. Make changes to the HTML, CSS, or JS files
2. Commit and push to the `main` branch
3. GitHub Actions will automatically deploy the changes
