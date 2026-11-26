# PoteOS

PoteOS is a browser-based desktop prototype with a calm, nature-inspired interface. It runs as a static site and is published with GitHub Pages.

## Project structure

- `index.html` — page shell and metadata
- `assets/css/poteos.css` — layout, themes, and animations
- `assets/js/poteos.js` — desktop, app, window, and local settings behavior
- `assets/img/poteos-mark.svg` — PoteOS favicon
- `.github/workflows/pages.yml` — automatic Pages deployment from `main`

No package install or build step is required.

## GitHub Pages

The workflow deploys the site whenever `main` is updated. In the repository settings, choose **Settings → Pages → Build and deployment → Source → GitHub Actions** for the first deployment. GitHub will show the published URL in the Pages settings and in the deployment workflow.

## Local data and limits

Preferences and app data are stored in the current browser. They do not sync between devices. The built-in lock screen is a prototype feature and is not a substitute for the device's own sign-in or disk encryption. Web pages can refuse to display inside PoteOS, and the OS-style power controls do not affect the actual device.
