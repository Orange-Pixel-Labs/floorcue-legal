# floorcue-legal

Public legal and support pages for FloorCue.

This repository intentionally contains only public legal/support content used for app store submission and user-facing support links. The main FloorCue app repository remains private.

## GitHub Pages URLs

- Home: https://orange-pixel-labs.github.io/floorcue-legal/
- Privacy Policy: https://orange-pixel-labs.github.io/floorcue-legal/privacy/
- Delete Account: https://orange-pixel-labs.github.io/floorcue-legal/delete-account/
- Support: https://orange-pixel-labs.github.io/floorcue-legal/support/

## Local preview

From the repository root:

```bash
python3 -m http.server 8080
```

Then open:

- http://localhost:8080/
- http://localhost:8080/privacy/
- http://localhost:8080/delete-account/
- http://localhost:8080/support/

## Deployment (GitHub Pages via Actions)

1. In GitHub repository settings, open **Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push to `main` (or run the workflow manually).
4. The workflow at `.github/workflows/pages.yml` deploys this static site.

## App Store / Play Console checklist

- [ ] Add Privacy Policy URL
- [ ] Add Delete Account URL (if account creation exists)
- [ ] Match Apple privacy labels to actual app behavior
- [ ] Match Google Play Data Safety answers to actual app behavior
- [ ] Link these pages from the app Settings screen
