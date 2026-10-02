PRICE DESK — PHONE APP (GitHub Pages)

This folder is the phone version of Price Desk. It contains NO data: your vendors,
prices and history are never uploaded. They only travel in the JSON file you send
yourself on WhatsApp, and are stored on the phone.

ONE-TIME SETUP
1. github.com -> New repository, e.g. "pricedesk" (Public is fine - there is no data inside).
2. Upload all files in this folder (index.html, sw.js, manifest.webmanifest, the 3 icons).
3. Repository Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: / (root) -> Save.
4. After a minute the app is at:  https://<your-github-username>.github.io/pricedesk/
5. On the Galaxy, open that link in Chrome -> menu (three dots) -> "Install app"
   (or "Add to Home screen"). Price Desk now opens from the home screen like an app, even offline.

UPDATING LATER
Upload the new index.html over the old one. The phone picks it up automatically
(the next time you open the app, or the time after).
