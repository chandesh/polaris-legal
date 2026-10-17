# Polaris - legal and support pages

Static pages that back the App Store listing for **Polaris**, a fully offline
daily-noticing app for iPhone. Hosted with GitHub Pages.

- `support.html` - Support URL (contact via the issue tracker)
- `privacy.html` - Privacy Policy URL
- `index.html` - Landing page linking to both

## App Store Connect URLs

| Field | URL |
| --- | --- |
| Support URL | https://chandesh.github.io/polaris-legal/support.html |
| Privacy Policy URL | https://chandesh.github.io/polaris-legal/privacy.html |

No build step. Edit the HTML, commit, and push to `main`; GitHub Pages serves
the new version within a minute or two.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
