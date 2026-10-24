# Panchang · The Vedic Calendar

**A gentle, inclusive Vedic calendar for everyone** — a live panchang, festivals with their stories and scriptural roots, and the history of the world's calendars.

| | |
|---|---|
| **Live website** | https://dennysonkusale-png.github.io/vedic-calendar/ |
| **Android app** | [Download the APK](https://github.com/dennysonkusale-png/vedic-calendar/releases/latest) · Android 5.0+ · works offline |

---

## What it does

- **Today at a glance** — tithi, paksha, nakshatra, vara, yoga, karana, moon phase, sunrise and sunset, computed live from the positions of the Sun and Moon.
- **Pick your place** — a location control in the top right: search 72 cities, use your device's location, or enter coordinates directly. Sunrise, sunset and the moon data are computed for your latitude and longitude, and your choice is remembered.
- **The calendar** — month and year views showing every festival day, with a live moon-phase wheel.
- **Every festival, with its story** — 42 festivals across 2026 and 2027 (84 dated entries). Each opens to the narrative behind the day, how it is observed, why it matters, and the Puranas, Vedas, Samhitas, Upanishads or epics it draws on.
- **The calendars explained** — the Vedic/Hindu, Gregorian, Saka, Vikram Samvat, Hijri, regional Indian, and Buddhist/other calendars, each with its history and origins.
- **Learn** — a gentle introduction to Vedic time (tithis, nakshatras, why the extra month exists, ayanamsa) and a small glossary.
- **My calendar** — choose your region and tradition, and save favourites privately in your browser.
- **Four languages** — English, हिंदी (Hindi), मराठी (Marathi), संस्कृतम् (Sanskrit).

## Design

The interface uses a cool neutral canvas with flat white surfaces, hairline borders and a single vermilion accent. Headings are set in Bricolage Grotesque, body text in Plus Jakarta Sans, and Devanagari in Mukta. Light and dark themes are both supported, and the theme choice is remembered.

## No third-party dependencies

Everything here is our own work: no component library, no icon pack, no template, no stock imagery, no CDN scripts, no analytics. The icons are hand-written inline SVG, and every line of CSS and JavaScript is ours.

The three typefaces are **embedded in the file** (SIL Open Font License 1.1, which expressly permits embedding and commercial use), so the page makes **no external requests at all** — verified by loading it with the network fully blocked.

## Run it

A single self-contained HTML file — no build step, no dependencies, no tracking, and nothing fetched from anywhere.

- Open `index.html` in any browser, or
- Host it anywhere — GitHub Pages (as here), Netlify, Cloudflare Pages, or any static server.

## Android app

The APK is a thin WebView wrapper around the same `index.html`, bundled inside. Because the page carries its own typefaces, the app renders the same offline as online.

1. Download `vedic-calendar.apk` from the [latest release](https://github.com/dennysonkusale-png/vedic-calendar/releases/latest).
2. Tap it on your phone. Android will ask you to allow installing from this source — enable it and continue.
3. The build is **debug-signed**, which is fine for direct install and testing, but it is not signed for the Google Play Store. Publishing there would need a proper release keystore. Builds from v1.2 onward share a single signing key and install over each other; upgrading from v1.1 or earlier needs an uninstall first.

## Notes on the data

- Festival dates for 2026 and 2027 are cross-checked against widely used panchangs for India. Because Hindu festivals follow a lunar tithi, a date can shift by a day between regions and between Smarta and Vaishnava traditions — where sources differ, the more widely observed date is shown.
- Today's panchang values are computed in the browser from low-precision Sun and Moon positions and are approximate. Treat them as a helpful guide, and confirm ritual timings with your local panchang or priest.
- The Hindi, Marathi and Sanskrit text is machine-assisted translation, shown alongside the English for reference. A careful read-through by native speakers is recommended before relying on it.
- Scriptural links are given as the traditional basis of each observance. Where an account is folklore or later custom rather than scripture, it is described as such.
- Places in the location picker are matched against a built-in list, which is what makes it work offline. Arbitrary place names are not geocoded, so a town that is not listed needs its coordinates entered directly.

## Contributing

Corrections to festival dates, translations, or scriptural references are very welcome — please open an issue or a pull request.

## Licence

No licence has been chosen yet. If you intend others to reuse this, add a `LICENSE` file (MIT and Apache-2.0 are common choices for projects like this).
