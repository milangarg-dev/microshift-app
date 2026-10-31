# MicroShift

The website for the MicroShift iPhone and iPad app, published with GitHub Pages at https://milangarg-dev.github.io/microshift-app/.

| Page | What it is |
| --- | --- |
| `index.html` | The home page: every feature, with screenshots, and "Coming soon" until the app is on the App Store |
| `support.html` | Support: contact email and common questions (the App Store's Support URL) |
| `privacy.html` | Privacy Policy, for the app and this website |
| `terms.html` | Terms of Use |

`style.css` styles every page. `images/` holds the logo and icons (made from the app's `Logo` and `AppIcon` image sets), and `images/screens/` holds the app screenshots (iPhone 17 Pro, light mode, 599 × 1304, taken in the Simulator with sample assignments). Retake the screenshots when a screen they show changes.

The site has no cookies, analytics, trackers or third-party files: fonts are the device's own, and every picture is in this repo. Keep it that way, or update the Privacy Policy's "This website" section.

MicroShift supports English only.

## When MicroShift is on the App Store

1. Download the black "Download on the App Store" badge (US English, SVG) from Apple's [App Store marketing guidelines](https://developer.apple.com/app-store/marketing/guidelines/) and save it, unchanged, as `images/app-store-badge.svg`. Don't redraw, recolor or crop it.
2. In `index.html`, search for `App Store:`. There are two spots, in the hero and in the "Coming soon" section. In each, uncomment the badge, replace `APP_STORE_URL` with the app's App Store link (from App Store Connect, like `https://apps.apple.com/app/id1234567890`), and delete the `coming-soon` label beside it.
3. Change the remaining "Coming soon" wording: the nav button (`nav-cta`, on every page), the hero's eyebrow, the "MicroShift is coming soon." section and its heading, and the Support page's intro.
4. Remove the "MicroShift isn't available yet…" note from the footer of `index.html`, and the sentence saying it isn't available yet from `terms.html`'s "This website" section.
5. Keep the trademark notice in the footer. Apple asks for it wherever its badge or product names appear.
