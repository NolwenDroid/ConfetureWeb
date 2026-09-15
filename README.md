# Confeture site

Official website for Confeture by NolwenDroid:

- `/` — B2C page for participants;
- `/organizers/` — B2B page for event organizers;
- `/privacy-policy.html` — shared privacy policy for the Android and iOS apps.

Production: https://confeture.nolwendroid.ru

## GitHub Pages

GitHub Pages publishes the `main` branch from the repository root. The `CNAME`
file binds the deployment to `confeture.nolwendroid.ru`; DNS must contain a
`CNAME` record from `confeture` to `nolwendroid.github.io`.

## Local preview

From this directory, run:

```sh
npm run build
npm run start -- --port 8765
```

Then open `http://localhost:8765/` or `http://localhost:8765/organizers/`.

## Distribution

The website does not distribute APK files. All installation links point to the
official Google Play listing:

https://play.google.com/store/apps/details?id=com.nolwendroid.confeture

## Current screenshots

`assets/screens/` contains real Android (OnePlus 8) and iOS (iPhone 8 Plus) captures, exported as WebP at 620 px and native width. Both landing pages use these captures without painting over the app UI. The `public/` copies support the existing local preview runtime; keep styles, scripts, support, privacy and screen assets synchronized with the static GitHub Pages files. iOS is preparing for App Store publication; add its installation link only after release.
