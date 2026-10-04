# Avolumi 初芽记 Landing Page

This public repository contains only the dependency-free marketing site for Avolumi 初芽记. It includes the landing page, support page, and privacy-policy URL used by App Store Connect; it contains no iOS application source code.

## Local preview

Run from the repository root:

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## GitHub Pages

The workflow at `.github/workflows/deploy-landing-page.yml` packages the site root and deploys it when a commit reaches `main`.

After the workflow succeeds, GitHub will show the published URL in the workflow summary. This repository's expected project-site URL is `https://andyzheung.github.io/avolumi-landing/`.

The page links to the live App Store listing at `https://apps.apple.com/app/id6807916555`.
