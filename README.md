# Content Services Presentations

Static presentation project for Content Services materials.

## Available Presentations

- [SEO Content Services Proposal](./content-services-proposal/)
- [Current State and SEO Manager Role](./current-state-and-seo-manager-role/)

## Local Preview

Open `index.html` in a browser, or serve the folder with any static web server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages Deployment

This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

After pushing to GitHub:

1. Open the repository settings.
2. Go to **Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push changes to the `main` branch to publish the site.

The root page lists the available decks. Each deck is available at its own path:

- `/content-services-proposal/`
- `/current-state-and-seo-manager-role/`
