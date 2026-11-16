# CBArt Studios — website redesign concept

A proposed multipage website for CBArt Studios. This is an **unofficial prototype**, not an approved replacement for the live business site.

## Preview on GitHub Pages

1. Download the ZIP and extract it.
2. Upload **all files and the `assets/` directory** to the public GitHub repository `cbartstudios/cbartstudios.github.io` (replace the temporary `index.html`).
3. Under repository **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/(root)`.
4. Open `https://cbartstudios.github.io/` after GitHub Pages deploys.

The site consists of eight HTML pages, one shared stylesheet (`style.css`), one shared JavaScript file (`site.js`), and original decorative SVG artwork in `assets/`.

## Important before presenting/publishing

- All photographs displayed from Unsplash URLs are illustrative placeholders, **not photographs of CBArt Studios, its staff, students, or facilities**. Replace with authorized studio photos and artwork.
- The abstract artwork SVGs are original placeholder graphics.
- Links labeled for registration, parties, gift cards, and general contact currently direct to the business's **existing website**. Verify those exact links and all current pricing, scheduling, and registration details with the owners before launch.
- Confirm factual copy, service categories, business ownership, and studio location with the owners.
- No business domain or DNS changes are required for this prototype.
- Do not represent this draft as the business's official or approved site until it is accepted by the owners.

## Editing

- Edit global header/footer and page content in `site.js`.
- Edit colors, typography and responsive design in `style.css`.
- The design loads DM Sans and Playfair Display using Google Fonts. It has local fallback fonts.
- Mobile navigation uses a small JavaScript toggle.

## Project status

Initial visual prototype for discussion with Cora and Steve. Not yet production-ready or an online booking/payment service.


## November 2026 About / branding update
- Added the original CBArt logo as `assets/cbart-original-logo.png`.
- Expanded `about.html` content (rendered by `site.js`) with Cora and Steve's story, their bios, and all five instructor profiles.
- The people photos are sourced by HTTPS links from `images.groovetech.io` as shown on CBArt's original About page. They are **not** embedded locally, so they need internet access and may be affected if CBArt changes its image hosting.
- Original source: https://cbartstudios.com/about-us
- Text is condensed from the current bios to avoid changing biographical facts. Check with the studio before treating it as final public copy.

To update GitHub, upload **the contents** of this folder to the repository root, replacing matching files. No DNS or domain changes needed.


## November 14 update
This ZIP includes the real Cora and Steve image in the About page hero, and redesigned Classes and Workshops & Camps pages. Dates, fees and exact schedules are deliberately not invented; all registration links point to the current CBArt website. The site is a public prototype, not the official business site.


## Latest update — Why CBArt?

- The About page now has a dedicated **Why CBArt?** section after the instructors, retaining the seven paragraphs provided by CBArt (including the bold closing paragraph), with four small editorial value cards alongside them.
- The homepage philosophy banner now highlights the CBArt wording about creativity having no age limit and links to the full statement.
- No biographies, photographs, logo, class offerings, navigation or other pages were changed in this update.
- Upload **all files and the assets folder contents**, replacing the existing ones. In this release, the actual changes are only in `site.js` and `style.css`.

## Mission and newsletter update (November 2026)
- Added CBArt's official mission statement verbatim on the homepage, after the introductory strip.
- Added a newsletter invitation above the footer on every page. The button currently links to the existing CBArt website, which displays its newsletter signup. This is not a working in-site email capture form; do not claim subscribers can submit without visiting the existing site.
- Changes are only in `site.js` and `style.css`.


## New: original CBArt homepage video (Nov 15 update)
A “CBArt Studios in Action” click-to-play section was added to the homepage after the offerings cards. The video uses the GrooveVideo `.m3u8` playlist discovered on CBArt’s original site and loads `hls.js` on demand in browsers without built-in HLS playback. The stream is **not** copied into this repository. Playback depends on the external GrooveVideo host allowing playback from GitHub Pages (CORS, hotlink policies and ongoing availability), which could not be verified here. An error message with a link to the original homepage appears if playback fails. No other pages were redesigned.
