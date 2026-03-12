# RESIST

Single-file web game prototype (`index.html`) for **RESIST — A Journey From Cell to Self**.

## Run locally

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/index.html`.

## Deploying live with GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`.

### One-time setup

1. Push this branch to GitHub.
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Ensure your default/public branch is one of: `main`, `master`, or `work` (or edit the workflow trigger).

### After setup

Every push to a configured branch automatically deploys `index.html` to GitHub Pages.
