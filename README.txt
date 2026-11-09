MY BUDGET — iPhone installable web app

This ZIP contains the first functional build of My Budget:
- Dashboard with the five agreed categories and percentages
- Deposit allocation using defaults or temporary overrides
- Spending from the chosen category, with any shortfall taken from Other
- Tap transactions in history to edit or delete them
- Category percentage settings, add category, and delete with balance distribution
- Local browser storage and JSON backup/restore
- App manifest, home-screen icons, and offline service worker

INSTALLATION
The ZIP cannot be installed directly from the iPhone. First upload the ZIP contents to a static web host that serves the files over HTTPS. Then on the iPhone:
1. Open the HTTPS address in Safari.
2. Tap Share.
3. Choose Add to Home Screen.
4. If shown, enable Open as Web App.
5. Tap Add.

DATA & BACKUPS
Data is saved in Safari's local storage on this iPhone/browser profile. Export a backup regularly in Settings. Clearing Safari website data can erase local app data; restore from your exported JSON backup if needed. The app does not connect to a bank or send budget data to a server.

IMPORTANT TESTING NOTE
This is a first build. Try it with sample values and export a backup before relying on it for important records. A hosted HTTPS address is still needed before installation.
