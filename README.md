# TransformHER Coaching App

This project is an installable Progressive Web App and a Capacitor-ready base for Android and iOS.

## Test locally
Use a local web server, because installation/offline features do not work when opening `index.html` directly:

```bash
npm install
npm run serve
```

## Install on a phone as a PWA
Host this folder on HTTPS (for example Netlify, Vercel or GitHub Pages), open the URL in Chrome/Safari, then choose **Add to Home Screen**.

## Prepare for Google Play / App Store

```bash
npm install
npx cap add android
npx cap add ios
npx cap sync
```

Android builds require Android Studio. iOS builds and App Store submission require a Mac with Xcode and an Apple Developer account.

## Data
The current version stores data locally on the device. Before a public multi-user launch, add authentication, secure cloud storage, privacy policy, terms, consent and account deletion.
