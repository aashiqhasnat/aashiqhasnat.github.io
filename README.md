# Aashiq Hasnat | Portfolio

Personal portfolio and root GitHub Pages site for **Aashiq Hasnat**, Indie Mobile & Game Developer.

**Live:** [https://aashiqhasnat.github.io/](https://aashiqhasnat.github.io/)

## Overview

- Single-page static portfolio styled after shadcn/ui's minimal Zinc palette (light default with persisted dark mode toggle, Geist typography, responsive `max-w-6xl` layout).
- Showcases current Android apps & games with direct Google Play and privacy policy links.
- Hosts root domain verification files (`app-ads.txt`) required by Google AdMob.

## Featured Releases

| App | Platform | Store | Privacy Policy |
| :--- | :--- | :--- | :--- |
| **Endless Arcade** | Android & Web (Game) | [Google Play](https://play.google.com/store/apps/details?id=com.aashiqhasnat.endlessarcade) | [Policy](https://aashiqhasnat.github.io/privacy-policies/racer/) |
| **Beacon: Private Web Browser** | Android (App) | [Google Play](https://play.google.com/store/apps/details?id=com.aashiqhasnat.beacon_browser) | [Policy](https://aashiqhasnat.github.io/privacy-policies/beacon/) |

## Repository Structure

```text
.
├── index.html                 # Single-page portfolio (HTML + Tailwind CDN)
├── app-ads.txt                # Google AdMob authorized seller record
├── .nojekyll                  # Bypass Jekyll processing on GitHub Pages
└── assets/
    ├── beacon-browser.png     # Beacon Browser Play Store icon
    └── endless-arcade.png     # Endless Arcade Play Store icon
```

## Local Preview

No build step required. Serve the root folder with any static server:

```bash
python -m http.server 8765
```

Then open `http://localhost:8765/`.

## Related Links

- **Privacy Policies Portal:** [https://aashiqhasnat.github.io/privacy-policies/](https://aashiqhasnat.github.io/privacy-policies/)
- **AdMob Verification:** [https://aashiqhasnat.github.io/app-ads.txt](https://aashiqhasnat.github.io/app-ads.txt)
- **Contact:** [aashiqhasnat@gmail.com](mailto:aashiqhasnat@gmail.com)
