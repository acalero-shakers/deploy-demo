# Deploy Demo

Minimal static site used to demo a CI/CD pipeline on GitHub.

**Pipeline:** `git push` → GitHub Actions → GitHub Pages

## How it works

1. Every push to `main` triggers the [Deploy workflow](.github/workflows/deploy.yml)
2. Actions uploads the static site as a Pages artifact
3. GitHub Pages serves the latest version

## Live site

The deployed site is available on GitHub Pages (see the **Environments** section
of this repo, or the link on the right sidebar).
