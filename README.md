# FightGrid Website

**Official website and privacy policy for the FightGrid Android app.**

## Published privacy policy URL
https://onlydavis34-debug.github.io/FightGrid-Website/privacy.html

## About
This repository hosts a minimal static site that serves FightGrid's Privacy Policy and related legal pages required for Google Play Console. The site is intentionally simple (single `privacy.html`) so it is easy to review and link from the Play Store.

## Files
- `privacy.html` — The full Privacy Policy (HTML). Confirm the following values are correct before publishing:
  - Effective date: 2026-07-09
  - Developer: onlydavis34-debug
  - Contact email: privacy@fightgrid.app
- `README.md` — This file.
- `.gitignore` — Ignore OS/editor files and local build artifacts.
- `LICENSE` — Project license (MIT).

## How to publish (quick)
1. Commit `privacy.html` with the values above confirmed.
2. Push to the `main` branch.
3. In the repo, go to **Settings → Pages** → **Deploy from a branch**.
4. Select **Branch: main** and **Folder: / (root)**, then save.
5. Wait a minute and confirm the page is available at:
   `https://onlydavis34-debug.github.io/FightGrid-Website/privacy.html`
6. Open the URL in an incognito window to verify HTTPS and public access.
7. Paste that URL into Google Play Console → App Content → Privacy Policy.

## Notes for Play Console reviewers
- Provide test credentials in Play Console reviewer notes if any flows require login.
- Ensure the same privacy URL is linked inside the app (Settings → Privacy Policy).
- Complete the Play Console Data Safety form to match the policy.

## License
This repository is licensed under the MIT License. See `LICENSE` for details.
