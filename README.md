# Tardeed — Privacy Policy

The public privacy policy for **ترديد / Tardeed**, the Quran memorization app.
Hosted with GitHub Pages and linked from the app's Google Play listing.

- `index.html` — the whole page. Arabic (RTL) by default, English toggle.
- `assets/` — brand mark and icon.

## Notes

Both languages live in the markup; the inactive one is hidden with CSS keyed off
`<html lang>`, so the policy still reads with JavaScript disabled. The toggle
flips `lang`/`dir` and remembers the choice. `?lang=en` opens the English version
directly.

To update the policy text, edit both the `data-lang="ar"` and `data-lang="en"`
sections in `index.html`, and bump the date in both `.effective-date` spans.
