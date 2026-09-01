MY MONEY MANAGER - PHONE INSTALLATION

1) Unzip this folder.
2) Upload the WHOLE folder to an HTTPS web host such as Netlify or GitHub Pages.
3) Open the HTTPS link on your phone.

ANDROID (Chrome):
- Open the website
- Tap the browser menu
- Choose Install app / Add to Home screen

IPHONE (Safari):
- Open the website
- Tap Share
- Choose Add to Home Screen

IMPORTANT:
- The app stores your records on that phone/browser.
- Use Settings > Backup JSON regularly.
- To move phones: Backup JSON on the old phone, then Restore JSON on the new phone.
- Offline mode works after the website has been opened once while online.

UPDATE v2.2
- Creating a Debtor record automatically decreases Current Balance (money given out).
- Receiving money from a Debtor automatically increases Current Balance.
- Creating a Creditor record automatically increases Current Balance (money received).
- Paying money to a Creditor automatically decreases Current Balance.
- Existing debtor/creditor records and payment records are reconciled into the cash ledger on startup.
- Linked debt payments can no longer be accidentally removed from the cash ledger.
- Service worker cache updated so GitHub Pages receives new app versions more reliably.

WHEN UPDATING GITHUB:
Replace index.html and sw.js at minimum. Replacing all files with this package is recommended.
After GitHub Pages deploys, open/reload the app online. If the installed shortcut still shows the old version,
close and reopen it, or refresh the website in Chrome/Safari once.
