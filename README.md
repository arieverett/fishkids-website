# Fish Kids website

Static reproduction of the original fishkidsgame.super.site page, built from the owner-provided Chrome webpage save and Notion HTML export.

## Contents
- `index.html` — full webpage content, layout and hyperlinks.
- `css/` — local copies of the original stylesheets used by the captured page.
- `assets/` — original image assets from the Notion export and a fish favicon.
- `.nojekyll` — enables static GitHub Pages hosting without Jekyll processing.

## Preview
Open `index.html` in a browser, or use VS Code's Live Server extension.

## Deployment
Copy **the contents of this folder** into your existing `fish-kids-game` Git repository, replacing its empty `index.html` and existing empty `assets/` folder. Commit and push on `main`. On GitHub, go to **Settings → Pages**, and select **Deploy from a branch → main → /(root)**. A GitHub Pages address will then be available after deployment.

## External content and existing links
- YouTube gameplay video: embeds `gBF-LDynUZc` from YouTube. Playback requires a connection and can depend on video/embed availability.
- Play button: original external p5.js game, `https://editor.p5js.org/arieverett/full/XRgiijiGI`.
- Donation and pricing links: original Venmo address, `https://account.venmo.com/u/summerthekid`.
- Home/nav link: updated to point to the new site rather than redirecting to Super.
- Source Files link: updated to this repository (`https://github.com/arieverett/fish-kids-game`).
- The displayed contact address is `hello@fishkidsgame.com`, but the original website's link opens `ari.everett@asu.edu`. This mismatch has intentionally been preserved until you choose which inbox to use.

Content, photos and layout remain editable directly in HTML and CSS. No Super or Notion account is required to serve this static website. The Inter font is loaded from Google Fonts if available and falls back to installed system fonts. The video and game remain externally hosted.
