# Already Paying

Tap the bills you already pay and see which ones give first responders a discount, how much it's worth, and how to claim it.

- Live app: https://jukes31ryan.github.io/already-paying/
- Install: open the link on your phone, then "Add to Home Screen" (iPhone) or "Install app" (Android/Chrome).
- Private: nothing you tap leaves your phone. No accounts, no tracking.

## Updating deals

All deals live in `deals.json`. Edit a deal, change its `lastVerified` date, and commit. The app picks up the new file on next open.
Deals marked `"source": "secondary"` came from comparison or deal sites and should be confirmed on the company's own page.
