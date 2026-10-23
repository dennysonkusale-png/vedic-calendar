# Panchang · The Vedic Calendar

**A gentle, inclusive Vedic calendar for everyone** — a live panchang, festivals with their stories and scriptural roots, and the history of the world's calendars.

| | |
|---|---|
| **Live website** | https://dennysonkusale-png.github.io/vedic-calendar/ |
| **Android app** | [Download the APK](https://github.com/dennysonkusale-png/vedic-calendar/releases/latest) (136 KB · Android 5.0+) |

---

## What it does

- **Today at a glance** — tithi, paksha, nakshatra, vara, yoga, karana, moon phase, sunrise and sunset, computed live from the positions of the Sun and Moon, with an optional "use my location".
- **The calendar** — month and year views showing every festival day, with a live moon-phase wheel.
- **Every festival, with its story** — 42 festivals across 2026 and 2027 (84 dated entries). Each opens to the narrative behind the day, how it is observed, why it matters, and the Puranas, Vedas, Samhitas, Upanishads or epics it draws on.
- **The calendars explained** — the Vedic/Hindu, Gregorian, Saka, Vikram Samvat, Hijri, regional Indian, and Buddhist/other calendars, each with its history and origins.
- **Learn** — a gentle introduction to Vedic time (tithis, nakshatras, why the extra month exists, ayanamsa) and a small glossary.
- **My calendar** — choose your region and tradition, and save favourites privately in your browser.
- **Four languages** — English, हिंदी (Hindi), मराठी (Marathi), संस्कृतम् (Sanskrit).

## Design

The interface uses a cool neutral canvas with flat white surfaces, hairline borders and a single vermilion accent. Headings are set in Bricolage Grotesque, body text in Plus Jakarta Sans, and Devanagari in Mukta. Light and dark themes are both supported, and the theme choice is remembered.

## Run it

It is a single self-contained HTML file with no build step, no dependencies and no tracking.

- Open `index.html` in any browser, or
- Host it anywhere — GitHub Pages (as here), Netlify, Cloudflare Pages, or any static server.

## Android app

The APK is a thin WebView wrapper around the same `index.html`, bundled inside so the app works fully offline.

1. Download `vedic-calendar.apk` from the [latest release](https://github.com/dennysonkusale-png/vedic-calendar/releases/latest).
2. Tap it on your phone. Android will ask you to allow installing from this source — enable it and continue.
3. The build is **debug-signed**, which is fine for direct install and testing, but it is not signed for the Google Play Store. Publishing there would need a proper release keystore.

## Notes on the data

- Festival dates for 2026 and 2027 are cross-checked against widely used panchangs for India. Because Hindu festivals follow a lunar tithi, a date can shift by a day between regions and between Smarta and Vaishnava traditions — where sources differ, the more widely observed date is shown.
- Today's panchang values are computed in the browser from low-precision Sun and Moon positions and are approximate. Treat them as a helpful guide, and confirm ritual timings with your local panchang or priest.
- The Hindi, Marathi and Sanskrit text is machine-assisted translation, shown alongside the English for reference. A careful read-through by native speakers is recommended before relying on it.
- Scriptural links are given as the traditional basis of each observance. Where an account is folklore or later custom rather than scripture, it is described as such.

## Contributing

Corrections to festival dates, translations, or scriptural references are very welcome — please open an issue or a pull request.

## Licence

No licence has been chosen yet. If you intend others to reuse this, add a `LICENSE` file (MIT and Apache-2.0 are common choices for projects like this).
