# Confeture site

Official website for Confeture by NolwenDroid:

- `/` — B2C page for participants;
- `/organizers/` — B2B page for event organizers;
- `/privacy-policy.html` — privacy policy for the Android app.

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
