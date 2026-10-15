RentWise PWA - how to put it online (no coding needed)

Easiest: go to app.netlify.com/drop and drag this whole unzipped folder onto the page.
You get a free https link. Open it on your phone, then:
  iPhone (Safari): Share > Add to Home Screen
  Android (Chrome): menu > Install app
Alternative: GitHub Pages or any https web host. A PWA only installs from https (or localhost).
Update later: change index.html, then bump the version in sw.js (rentwise-v1 -> rentwise-v2) so phones refresh.
