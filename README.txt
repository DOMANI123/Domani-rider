DOMANI RIDER — INSTALLABLE HOME-SCREEN APP (PWA)

WHAT THIS IS
This is the installable DOMANI RIDER account manager for Android Chrome.
It opens like an app (without normal browser tabs) and can work offline after
its first successful online load. It is not an APK.

FILES
- index.html: the account manager
- manifest.webmanifest: app name, icon and standalone display settings
- sw.js: offline app-shell cache
- icons/: home-screen icons

PUBLISH USING GITHUB PAGES (PHONE)
1. Create a GitHub repository named domani-rider (Public is simplest for Pages).
2. Extract this ZIP on your phone.
3. In the repository choose Add file > Upload files.
4. Upload the CONTENTS of this folder to the repository root. Do not upload only
the ZIP and do not put the files inside an extra nested folder.
5. Commit the uploaded files.
6. Open repository Settings > Pages.
7. Under Build and deployment, choose Deploy from a branch.
8. Choose branch main and folder /(root), then Save.
9. Wait for GitHub Pages to publish. Open the Pages URL shown there in Chrome.
10. Load the app once while online. In Chrome's three-dot menu choose
    Install app or Add to Home screen.

USING IT OFFLINE
After the first online load and successful service-worker setup, launch it from
the home-screen icon. The app shell is cached for offline use. New installation,
first load, and updates require internet access.

YOUR RECORDS AND PRIVACY
Income, expenses, fuel, distance and service records are stored locally in the
app's browser storage on this phone. They are not automatically synced to
GitHub or another phone. Export records regularly and keep the backup somewhere
safe. Clearing Chrome/site data or uninstalling/resetting the app may erase
local records. Export a backup from the old version and import it into this
installed version if you already have records to preserve.

IMPORTANT
A PWA must be served over HTTPS. Opening index.html directly from Downloads
will not enable installation or offline caching. GitHub Pages provides HTTPS.
