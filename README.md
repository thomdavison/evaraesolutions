# Evarae Solutions

A small, dependency-free marketing site built with HTML, CSS, and JavaScript. GitHub Actions deploys it to GitHub Pages whenever a change is pushed to `main`.

## Before publishing

- In `script.js`, replace `hello@evaraesolutions.com` with the email address that should receive enquiries. The contact form opens the visitor's default email app with the enquiry details filled in; it does not submit to a server.
- The sample website shown in the hero is an illustrative design, not a live client project.

## GitHub Pages deployment

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, set the source to **GitHub Actions**.
3. Push a change to `main`, or run **Deploy website to GitHub Pages** from the **Actions** tab.
4. Visit the deployment URL shown in the workflow run or Pages settings.

No build step, package installation, or server configuration is required. The first deployment may take a few minutes.
