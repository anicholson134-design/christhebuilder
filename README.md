# Chris Smith Builder (Chris the Builder): homepage concept

A single-page sales demo of a new homepage for Chris Smith, Chris the Builder, Orrell, Wigan (https://www.christhebuilder.com/). Only the homepage is built; links scroll within the page. The only thing wired up is WhatsApp: the quote form and the "WhatsApp Chris" button open WhatsApp with the enquiry already written out (`wa.me` link to `WA_NUMBER` in the page script, set to Chris's mobile 07779 142599, which his site lists for WhatsApp). The visitor presses send.

Open `index.html` in a browser, or serve the folder with any static server (`python3 -m http.server`).

## Content and photos

- Copy, awards, contact details and the three customer comments come from christhebuilder.com, mostly in Chris's own words.
- The other job photos come from christhebuilder.com. His site only hosts small (about 320px) versions, so they were upscaled and lightly sharpened; ask Chris for originals before going live.
- The four before and after pairs (rear extension, garage into living room, re-roof, terraced house facelift) are Chris's own photos, supplied by Alec from his Facebook. The same after shots are used on the Extensions, Garage Conversions and Roofing service cards.
- `about-1.jpg` is the public profile photo from his Facebook page. Facebook posts, photos and reviews need a login, so nothing else was taken from Facebook.
- Hero video is free Mixkit stock bricklaying footage (same clips as the Stringfellow demo), not Chris's own.

## Branding

Colours follow his logo banner (`assets/img/logo.jpg`): brick red `#9B2F1F`, orange `#EE6A1C` for buttons, and yellow `#FFD21F` for highlights, on a warm near-black in place of navy. The trust bar carries the logo's red to yellow gradient.

## Deploy

`.github/workflows/deploy.yml` publishes the repo root to GitHub Pages on every push to `main` (Pages source: GitHub Actions).
