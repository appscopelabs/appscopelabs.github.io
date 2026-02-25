# appscopelabs.github.io

Landing page for AppScope Labs.

## Deployment
- Auto deploys to GitHub Pages via .github/workflows/deploy-pages.yml on push to `main`.
- Configure repo settings: **Pages → Build and deployment → Source: GitHub Actions**.

## Pending integration
- Replace `index.html` with Luna's final HTML.
- Add Polar checkout URLs from Eli.
- Add OG image and analytics snippet.


### Firebase fallback deployment
Set repo secret `FIREBASE_SERVICE_ACCOUNT_APPSCOPE_SAAS` with service-account JSON to enable `.github/workflows/deploy-firebase.yml`.
