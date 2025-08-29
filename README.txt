River Bridge Route Optimizer — Single File (v13)
------------------------------------------------
This ZIP contains a single-page app (index.html) you can deploy by dragging to Netlify Drop.

How to use:
1) Unzip this file.
2) Go to https://app.netlify.com/drop and upload the unzipped folder (the one that contains index.html).
3) Open the .netlify.app URL Netlify gives you.
4) Paste your Google Maps API key (or use the prefilled one), click "Load Google Maps".
5) Paste your stops (one address per line), then click "Optimize Route".
6) Use "Open in Google Maps" for turn-by-turn, check Delivered boxes, capture signatures, add photos, and Print.

Notes:
- Your data stays on-device (localStorage) — nothing is uploaded anywhere.
- Google Directions supports up to 25 total points (start + waypoints + end).
- Driver Mode: append ?driver=1 to the URL to hide all pricing.
- Owner PIN: set a 4-digit PIN to require it when exiting Driver Mode.
- Timezone: ETAs and timestamps use your device's local timezone.

Build date: 2025-08-29T00:07:31
