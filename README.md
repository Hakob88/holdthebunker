# Hold the Bunker support site

Support page (`index.html`) and privacy policy (`privacy/index.html`) for the App Store, as plain
static files for GitHub Pages. No build step and no external requests; one small inline script
moves the screenshot carousel (`screenshots/`, web copies of the iPhone 6.3" App Store screenshots).

Contact address on both pages: `holdthebunker@gmail.com`. To publish, copy the contents of this folder to the root of the GitHub Pages repository and
set the custom domain under Settings → Pages.

App Store Connect:
- Support URL: `https://<your domain>/`
- Privacy Policy URL: `https://<your domain>/privacy/`

The privacy policy describes what the app does (checked against the code, November 2026): no data
collected, progress kept on the device, Game Center through Apple, local network only for
multiplayer with nearby devices. Update it if the app ever adds networking, analytics, ads or
purchases.
