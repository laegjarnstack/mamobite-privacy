# MamoBite Privacy Policy

Public privacy policy pages for the [MamoBite](https://github.com/laegjarnstack/MamoBite) mobile app.

## Pages

| Language | URL |
|----------|-----|
| Turkish (default) | `/` |
| English | `/en/` |

## GitHub Pages

This repository is published with GitHub Pages from the `main` branch root.

Live URL: https://laegjarnstack.github.io/mamobite-privacy/

## Updating content

Source of truth for policy text lives in the main MamoBite repo:

`supabase/functions/privacy-policy/content.ts`

Regenerate static HTML:

```bash
cd ../MamoBite
npx tsx scripts/export-privacy-policy-html.ts
```

Then commit and push changes in this repository.
