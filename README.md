# Content Services Presentations

Static presentation project for Content Services materials.

## Current Presentation

- [SEO Content Services Proposal](./content-services-proposal/)

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

The root page redirects to `content-services-proposal/`.
