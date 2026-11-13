# Store badges

Official artwork downloaded from:

- Apple: https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg
- Google: https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png

The six game pages use the shared `GameDownloadComponent`. Store URLs are preview
values in `src/app/shared/game-download/game-downloads.ts`. Replace both URLs per
game after publishing and set `placeholder: false` to remove the coming-soon note.

QR codes link to `https://puzzoom.com/<game>` and are generated locally by
`scripts/generate-game-qr.py`. Their white background is intentional for scanning
in either website theme. Regenerate them if the destination changes.
