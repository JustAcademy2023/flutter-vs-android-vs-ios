# flutter-vs-android-vs-ios

A single-page, responsive landing page comparing **Flutter, React Native, native Android, and native iOS** development, built as an IDE-inspired visual guide for learners trying to pick a mobile development path.

Live link placeholder: `https://<your-username>.github.io/flutter-vs-android-vs-ios/`

## About

This page answers one question: *Flutter vs native Android vs iOS, which mobile development path should you choose?* Instead of a generic comparison chart, it's framed like a code editor, with a tab bar for each platform, four "file panel" cards laying out what each stack actually feels like to learn, a quick fit-finder section, and a strip of further-reading links for anyone who wants to go deeper.

It was built for Pune-based learners specifically, with every course link pointing to JustAcademy's live, instructor-led Pune training tracks.

## Preview

- Dark, code-editor inspired hero with an animated tab bar and blinking cursor
- Four colour-coded comparison panels (Flutter, React Native, native Android, native iOS), each with its own accent colour instead of one-size-fits-all cards
- A "which one fits you" section pairing a quick decision list with a short pull-quote block
- A horizontally scrollable further-reading strip
- Fully responsive down to mobile, with a lightweight CSS-only nav toggle (no external JS dependency)
- Every link on the page is a real, clickable, `target="_blank"` anchor tag

## Tech stack

- Plain HTML5 and CSS3, no build step, no framework
- Google Fonts: Space Grotesk (display), IBM Plex Sans (body), IBM Plex Mono (code accents)
- Zero JavaScript dependencies; the mobile nav uses a CSS checkbox toggle

## Folder structure

```
flutter-vs-android-vs-ios/
├── index.html
└── README.md
```

## Getting started

Clone the repo and open the file directly, no build tools required.

```bash
git clone https://github.com/<your-username>/flutter-vs-android-vs-ios.git
cd flutter-vs-android-vs-ios
open index.html
```

### Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set the source to the `main` branch, root folder.
4. Your page will be live at `https://<your-username>.github.io/flutter-vs-android-vs-ios/`.

## Links referenced on the page

**Course tracks (Pune)**
- Flutter training in Pune — `https://www.justacademy.co/course-detail/pune/flutter-training-in-pune`
- React Native training in Pune — `https://www.justacademy.co/course-detail/pune/react-native-training-in-pune`
- Android app development in Pune — `https://www.justacademy.co/course-detail/pune/android-app-development-in-pune`
- iOS training in Pune — `https://www.justacademy.co/course-detail/pune/ios-training-in-pune`

**Further reading**
- Flutter vs native Android vs iOS, full comparison blog
- Flutter developer roadmap 2026
- Android app development career guide
- iOS developer roadmap 2026
- Mobile app development careers in India, 2026

## License

Free to use and adapt for JustAcademy's own properties.
