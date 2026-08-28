# nightkeys-site

Public website for **Nightkeys**, a Mac app that lights your keyboard using your display.

Served by GitHub Pages from `main` at the repository root.

| Page | Used for |
|---|---|
| `index.html` | **Support URL** in App Store Connect (required) |
| `privacy.html` | **Privacy Policy URL** in App Store Connect (required, Guideline 5.1.1(i)) |

This repo is public because GitHub Pages on a free account only publishes from public
repositories. It contains the website only — the app source and business material live
in a separate private repo.

## Before going live

Replace `SUPPORT@EXAMPLE.COM` in both files with a real, monitored address.

## Notes

- Both pages are self-contained: no build step, no dependencies, no external requests.
- They adapt to light and dark mode via `prefers-color-scheme`.
- If a custom domain is added later, point it here — the page URLs stay valid.
